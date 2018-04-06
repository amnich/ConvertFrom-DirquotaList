# ConvertFrom-DirquotaList

Convert output from Dirquota quota list to an object
	

	PS > & Dirquota quota list | ConvertFrom-DirquotaList
	
	QuotaPath     : D:\Share\user
	SharePath     : {\\SERVER\Share\user}
	LimitGB       : 3,5
	UsedGB        : 3,4
	UsedPC        : 97
	AvailableGB   : 0,1
	AvailablePC   : 3
	PeakGB        : 13,75
	PeakDate      : 2018-01-22 12:44
	Template      : Share template
	TemplateMatch : Matches template
	LimitType     : Soft
	Status        : Enabled
	
Original code from Technet gallery by Ben Wilkinson https://gallery.technet.microsoft.com/scriptcenter/Find-and-Report-on-cc49120e

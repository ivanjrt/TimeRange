# TimeRange for PowerShell
This will allow to determine a Time & Date Range and allow to create an action
This is for PowerShell


````Ruby
    [int]$nowH     = (get-date).Hour
    [int]$nowM     = (get-date).Minute
    [double]$now   = -join $nowH + '.'  + $nowM
    [String]$today = (get-date).DayOfWeek
    if ($now -gt 9 -and $now -le 17.45 -and $today -ne "Saturday" -and $today -ne "Sunday") {$pingQuery = 18} else {$pingQuery = 125}
````

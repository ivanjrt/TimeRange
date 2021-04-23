# TimeRange
This will allow to determine a Time Range and allow to create an action
This is for PowerShell


````Ruby
    [int]$nowH   = (get-date).Hour
    [int]$nowM   = (get-date).Minute
    [double]$now =   -join $nowH + '.'  + $nowM
    if ($now -gt 9 -and $now -le 17.45) {$speedVariable = 15} else {$speedVariable = 125}
````

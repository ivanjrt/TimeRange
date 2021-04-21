# TimeRange
This will allow to determine a Time Range and allow to create an action
This is for PowerShell


````Ruby
$now = (get-date -F "HH:MM")
If (( $now -gt "9:00") -and ($now -lt "23:45")) {write 'something'}
````

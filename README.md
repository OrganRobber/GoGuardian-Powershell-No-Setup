# GoGuardian-Powershell-No-Setup
$usernameinsertnameinsert = read-host -prompt "Whats your Username (ex. Jblog5854)"

if (test-path "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanhE") {

$current = "Off"


$onoff = read-host -prompt "Gogaurdian On or Off

It is currently $current"

}

Else {

$current = "On"

$onoff = read-host -prompt "GoGuardian On or Off

It is currently $current"

}

If ($onoff -eq "on") {

move-item -path "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanh" -destination "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default"; rename-item "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanhE" -newname "haldlgldplgnggkjaafhelgiaglafanh"; get-process -name msedege | stop-process

}

if ($onoff -eq "off") {

rename-item -path "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanh" -newname "haldlgldplgnggkjaafhelgiaglafanhE"; move-item -path "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\haldlgldplgnggkjaafhelgiaglafanh" -destination "C:\Users\\$usernameinsertnameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions"; get-process -name msedge | Stop-Process

}

if ($onoff -notin $onoffoptions) {

Write-Host "ERROR: You must pick exactly on or off, if you put anything else it will be ignored and nothing will happen..."

Write-Host " "

}

$clearhost = read-host -prompt "clear terminal (enter y or n)"

if ($clearhost -eq "y") {

clear-host
}

if ($clearhost -notin $clearhostoptions) {

Write-Host "ERROR: You must put exactly y or n, if you put anything else it will be ignored and nothing will happen"

Write-Host " "
}

$onoffoptions = @(

"on"

"off"

)

If (Test-path -path "C:\Users\elock7767\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanhE") {
break
}

Else {

If (Test-Path -path "C:\Users\elock7767\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanh\3.0.6267.1_0") {

break

}


rename-item -path "C:\Users\\$usernameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanh" -newname "haldlgldplgnggkjaafhelgiaglafanhE"; new-item -Type Directory -path "C:\Users\\$usernameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions" -name "haldlgldplgnggkjaafhelgiaglafanh"

}

$clearhostoptions = @(

"y"

"n"

)

if (test-path "C:\Users\\$usernameinsert\AppData\Local\Microsoft\Edge\User Data\Default\Extensions\haldlgldplgnggkjaafhelgiaglafanhE") {

$current = "Off"

clear-host

if ($onoff -notin $onoffoptions) {

Write-Host "ERROR: You must pick exactly on or off, if you put anything else it will be ignored and nothing will happen..."

Write-Host " "

}

 }

Else {

$current = "On"


$onoff = read-host -prompt "GoGuardian On or Off
It is currently $current"

if ($onoff -notin $onoffoptions) {

"ERROR: You must pick exactly on or off, if you put anything else it will be ignored and nothing will happen..."

Write-Host " "

}

}

$clearhost = read-host -prompt "clear terminal (enter y or n)"

if ($clearhost -eq "y") {

clear-host

}

if ($clearhost -notin $clearhostoptions) {

Write-Host "ERROR: You must put exactly y or n, if you put anything else it will be ignored and nothing will happen"

Write-Host " "

}

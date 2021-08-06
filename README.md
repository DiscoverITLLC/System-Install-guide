# System-Install-guide
guide

Step 1
````bash
bash -c  "$(curl -sL https://raw.githubusercontent.com/DiscoverITLLC/MagicMirror_scripts/master/raspberry.sh)"
````
Step 2
````bash
bash -c  "$(curl -sL https://raw.githubusercontent.com/DiscoverITLLC/MagicMirror_scripts/master/upgrade-script.sh)"
````
Step 3
````bash
bash -c  "$(curl -sL https://raw.githubusercontent.com/DiscoverITLLC/MagicMirror_scripts/master/upgrade-script.sh)" apply
````
Step 4
````bash
bash -c "$(curl -sL https://raw.githubusercontent.com/DiscoverITLLC/MagicMirror_scripts/master/screensaveroff.sh)"
````
Step 5
````bash
bash -c "$(curl -sL https://raw.githubusercontent.com/DiscoverITLLC/MagicMirror_scripts/master/fixuppm2.sh)"
````

# System remote control
//Acceda a la interfaz remota en http://Here your ip:8080/remote.html (reemplace con la dirección IP)
Apy key(bc2e979db92f4741afad01d5d18eb8e2) APK

Android app:
https://github.com/DiscoverITLLC/MM-Remote/raw/main/MM-Remote.apk

Application for WINDOWS:
https://github.com/DiscoverITLLC/MM-Remote/raw/main/MM-Remote_Linux.zip

Linux application:
https://github.com/DiscoverITLLC/MM-Remote/raw/main/MM-Remote_Windows.zip

Step 6
````bash
bash -c "$(curl -s https://raw.githubusercontent.com/DiscoverITLLC/MMM-Remote-Control/master/installer.sh)"
````
Step 7
````bash
bash -c "$(curl -s https://raw.githubusercontent.com/DiscoverITLLC/MMM-Videoplayer/master/installer.sh)"
````
Step 8
````bash
bash -c "$(curl -s https://raw.githubusercontent.com/DiscoverITLLC/MMM-BackgroundSlideshow/master/installer.sh)"
````

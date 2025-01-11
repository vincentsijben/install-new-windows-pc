# install-new-windows-pc

Following [this YouTube tutorial](https://www.youtube.com/watch?v=LMN17-i10Ng).

## Backup your stuff
* If you have a Windows Product Key, make a note of it. The install asks for it later on.
* Create an export file for your Steam deck, BEACN software and OBS scenes/settings.

## Installation
* Follow instructions https://www.youtube.com/watch?v=LMN17-i10Ng&t=120s (2:00 till 5:51)
* Optional: Use UniGETUI to check current installed apps, so you can install those easier later on. Follow instructions https://www.youtube.com/watch?v=LMN17-i10Ng&t=351s (5:51 till 7:03)<br>
Installed it through https://www.marticliment.com/unigetui/. I checked 1Password, Discord, Dropbox, Elgato Stream Deck, OBS Studio, VLC.

## Booting from USB
I had to go to BIOS - Boot - Secure mode and set the "OS Type" from "Windows UEFI mode" to "Other OS".

* Follow instructions https://www.youtube.com/watch?v=LMN17-i10Ng&t=513s (8:33 till 12:39). Boot from the USB Device. 
* When installing, click "i dont have a product key" and "Windows 11 Pro".
* The installation process took 11:15 minutes.

## Installation finished
* Install official Game-Ready NVIDIA drivers from nvidia's website.
* Optional: On the desktop, open the shortcut UWScript and install UniGETUI to install your software.
* Run windows update, download and install updates, restart.

## Activate Windows and install/activate Office
If you don't have a Windows or Office product key:
* Run Powershell in admin mode (right click windows startmenu, choose Terminal Admin or Powershell Admin) and copy paste: `irm https://get.activated.win | iex` (also see [Linus Tech Tips](https://youtu.be/yJkRd9py5mA?si=MqnCXkSb10iWScy3&t=471)).
* Press 1 to activate Windows
* Press 2 and then 3 and download Office through "Office C2R Installers ❤️, search for "dutch" and install through Link ❤️.
* When Office is done installing, go back to Powershell and press 1 to activate it.

## Debloat Windows
Optional

* Open Powershell in admin mode and run `irm https://christitus.com/win | iex`.
* Click on tab "Tweaks" and click "Standard".
* Also mark "Change Windows Terminal default: Powershell 5 -> Powershell 7".
* Click "Run Tweaks". In the powershell windows you can see the progress.
* Click on the "Install" tab and check Chrome and Steam. Click on "Install Selected" on top.

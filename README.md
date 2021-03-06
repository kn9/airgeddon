#airgeddon
This is a multi-use bash script for Linux systems to audit wireless networks.<br>
<img src="https://raw.githubusercontent.com/v1s1t0r1sh3r3/airgeddon/master/airgeddon_banner.png" title="We'll conquer the earth!!">

#Features
- Interface mode switcher (Monitor-Managed).<br>
- DoS over wireless networks with different methods.<br>
- Assisted Handshake file capture.<br>
- Cleaning and optimizing Handshake captured files.<br>
- Offline password decrypt on WPA/WPA2 captured files (dictionary and bruteforce).<br>
- Compatibility with many Linux distros (see requirements section).<br>
- Easy targeting and selection in every section.<br>
- Controlled Exit. Cleaning tasks and temp files. Option to keep monitor mode if desired.<br>
- Multilanguage support and autodetect OS language feature (see supported languages section).<br>
- Help hints in every zone/menu for easy use.<br>
- Auto-update. Script checks for newer version if possible.<br>

#Requirements
Bash version 4 or later needed.<br>
<br>
Tested on these compatible Linux distros:<br>
*-Kali 2.0 and 2016.1*<br>
*-Wifislax 4.11.1 and 4.12*<br>
*-Backbox 4.5.1*<br>
*-Parrot 2.2.1*<br>
*-Blackarch 2016.01.10*<br>
*-Cyborg Hawk 1.1*<br>
*-Debian 7 (Wheezy) and 8 (Jessie)*<br>
*-Ubuntu/Xubuntu 15.10 and 16.04*<br>
*-OpenSUSE Leap 42.1*<br>
*-CentOS 6 and 7*<br>
*-Gentoo 20160514*<br>
*-Fedora 24*<br>
*-Red Hat 7 (Maipo)*<br>
<br>
Anyway, can be used with any Linux distro if you have installed the tools what script needs. The script checks for them at the beginning.<br><br>
Essential tools: <- *the script doesn't work if you don't have installed all of them*<br>
`iwconfig iw awk airmon-ng airodump-ng aircrack-ng xterm`<br><br>
Optional tools: <- *not necessary to work, only needed for some features*<br>
`wpaclean crunch aireplay-ng mdk3`<br><br>
Update tools: <- *not necessary to work, only used for auto-update*<br>
`curl`<br>
<br>
Impossible compatibility for Mac OSX at the moment. Some reasons:<br>
*-Bash version* <- it can be avoided upgrading to 4 or later, this is not the problem<br>
*-Aircrack suite* <- this suite for OSX doesn't support airodump and aireplay<br>
*-Wireless tools* <- iwconfig doesn't exists for OSX, and airport command can't be used. It generates very different outputs<br>

#Disclaimer
This script must be used only for educational purposes and Pen testing.<br>
Use it only on your own networks.<br>
We are not responsible of its use.<br>
This script is under GPLv2 (or later) License.<br>

#Use
Under some distros like Kali Linux must be launched only using bash (not sh). Example `bash /path/airgeddon.sh`<br>
Under Wifislax Linux and others, it can be launched using bash or sh. Example `sh /path/airgeddon.sh`<br>
If you launch the script using sh and a *"Syntax error"* appears, launch it with bash instead of sh.<br>

#Supported Languages
English, Spanish, French and Catalan.<br>

#Project Collaboration
You can join the project:<br>
-Translations to other languages are welcome.<br>
-More distros support compatibility.<br>
-New features.<br>
-Testing and feedback is needed too.<br>

#Changelog
See <a href="https://github.com/v1s1t0r1sh3r3/airgeddon/blob/master/changelog.txt" target="_blank">Changelog</a> file to review changes.<br>

#Special Thanks to
**Kcdtv** for French translations, beta testing, suggestions about new features and support received.<br>
**El padrino** for Catalan translations.<br>
**USUARIONUEVO** and Wifislax staff for helping me to improve the script and for suggestions about new features.<br>

#Donate
If you enjoyed the script, feel free to give a donation. Invite me a coffee sending me a fraction of a bitcoin:<br>
*3HcTA8H91oPRcd5eu1uJf165sbknQtUSzU*<br>
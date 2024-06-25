# Kali_Linux_OSINT_VM

<div align="center">
  <br>
  <img src="https://github.com/owerdogan/wallpapers-for-kali/blob/main/kali-red/red-kali16x9.jpg" alt="kali linux dragon logo" width="65%" height="65%">  
</div>
<br><br>

## Over 100+ OSINT Tools

Python(pipx):

ghunt,
socialscan,
holehe,
xeuledoc,
waybackpy,
changedetection.io,
archivebox,
internetarchive,
search-that-hash,
name-that-hash,
h8mail,
domain-stats,
gitem,
whisper-ctranslate2,
checkdmarc,
shodan,
netlas,
postleaks,
postleaksNg

GitHub Repositories:

Elasticsearch-Crawler,
blackbird,
Carbon14,
maigret,
Cr3dOv3r,
BridgeKeeper,
Elevate,
pwnedOrNot,
phoneinfoga,
EXIF-scanner,
LittleBrother,
WhatsMyName-Python,
gron,
sherloq,
spiderfoot,
theHarvester,
Spiderpig,
WikiLeaker,
ID-entify,
ReverseIP,
UhOh365,
Anon-SMS,
instashell,
Wordlister,
netlas-scripts,
Fresh-Resolvers,
lazyegg,
TrashSearch,
agg,
X-osint,
anonphisher,
proxybroker2,
yt-dlp

Apt Package Manager:


tor, ufw, gospider, hakrawler, gobuster, ruby-dev, ffuf, seclists, youtubedl-gui, filezilla, libreoffice,
httrack, webhttrack, sherlock, eyewitness, sublist3r, photon, recon-ng, python3-venv, jq, pipx,
snapd, mediainfo-gui, kali-tools-crypto-stego, neovim, cargo, asciinema,
marble, qgis, finalrecon, ugrep, bloodhound, bing-ip2hosts,
mat2, gallery-dl, libimage-exiftool-perl, stegosuite, exifprobe, ruby-bundler, mpg123,
thunderbird, sq, python3-lxml, libre-dev, exiflooter, flowblade, dumpsterdiver,
npm, wpscan


Snap Packages:

youtube-dl-pro,
joplin-desktop,
ngrok,
localxpose,
telegram-desktop


## **Install:**

Install <a href="https://www.virtualbox.org/">VirtualBox</a> on host PC.

Create a new <a href="https://www.kali.org/get-kali/#kali-platforms">Kali Linux</a> Virtual Machine on VirtualBox. Or, import the <a href="https://www.kali.org/get-kali/#kali-platforms">Pre-built Virtual Machine</a>.

Install Kali Linux on Virtual Machine. Or import pre-built Virtual Machine. 

Start Virtual Machine

Update and Upgrade

Install Github

```console

git clone https://github.com/midnit3Z0mbi3/Kali_Linux_OSINT_VM.git

chmod +x *.sh

sudo bash kali_osint_setup.sh

bash kali_osint_tools_pipx.sh

sudo bash snoint.sh

```

**Change DNS:**

```console

sudo bash change_dns.sh

reboot

```

**How to install the latest version of Go:**

Download the latest version of <a href="https://go.dev/dl/">Go</a>

Extract the archive file

```console

sudo tar -C /usr/local -xzf /home/$USER/Downloads/go{version of GO}linux-amd64.tar.gz

Make sure your PATH contains /usr/local/go/bin

echo $PATH | grep "/usr/local/go/bin"

nano .zshrc

export PATH="/usr/local/go/bin:$PATH"

```

**Install go packages:**

```console

bash go.sh

```
<br>


## **Downloads:**


<a href="https://protonvpn.com/">Protonvpn</a>, <a href="https://www.torproject.org/download/">Tor Browser</a>, 
<a href="https://github.com/jgraph/drawio-desktop/releases/tag/v23.0.2">Draw.io</a>, 
<a href="https://www.google.com/earth/about/versions/">Google Earth Pro</a>, 
<a href="https://support.google.com/chrome/a/answer/9025903?hl=en">Google Chrome</a>, 
<a href="https://go.dev/dl/">Go</a> 




## **firefox extensions:**

firefox containers, ublock origin, downthemall, bulk media downloader, fireshot, nimbus, singleFile, exifviewer, user agent switcher, image search options, reveye reverse search,

search by image, ressurrect pages, web archives, copy selected links, onetab, stream detector, joplin webclipper, foxyproxy, adguard, javascript toggle on and off, ghunt companion, download all images, keepassxc

the firefox extension store, firefox ADD-Ons, has a lot of useful AI web extensions, and other extensions that can aid in your research. 

## **chrome web store extensions:**

InVID WeVerify, ublock origin, adguard, downthemall, fireshot,  singleFile, onetab, reveye reverse search, web archives

the chrome web store has a lot of useful AI web extensions, and other extensions that can aid in your research.

## **OSINT Techniques:**

If you have read 
<a href="https://www.osinttechniques.com/">OSINT Techniques</a> by Michael Bazzell 

I would recommend using the search tools he provides. As well as the flow charts and templates.

***REMEBER*** to update the $PATH you must edit the .zshrc file, not the .bashrc

nano .zshrc 
<br>
<h2>
  
## **Anonymize virtual machines with <a href="https://www.whonix.org/wiki/Download">Whonix</a> for an extra layer of security:**

</h2>


<br>
<div align="center">

  <img src="Anonymizing_virtual_machines_with_Whonix.png" width="80%" height="80%">
  
</div>
<br><br><br>



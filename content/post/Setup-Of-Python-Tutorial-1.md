+++
authors= "Gitesh Wagh"
title = " Installation and Setup of Python and VS Codium - Python Tutorials For Beginners #1 "
date = "2023-04-02"
categories = "Python"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial",
]
+++
******
#### Hello Friends👋,  
You know that Python is the most straightforward programming language for 
beginners. Today, We will see how to download and set up Python with VS Codium. 
VS Codium is an Integrated Development Environment (IDE). VS Codium is a simple 
and powerful tool for coding. 

VS Codium provides many important and latest features. VS Codium is a lightweight but powerful tool. VS Codium helps you a lot in your coding journey. I use VS Codium for coding and web development. I also use VS Codium for building this site. 

So Let's Get Started. 

### Step 1: Download the Python interpreter.

Use only the official website of Python for downloading Python interpreter.   Download an interpreter for your operating system. The process is too simple. Download and install it like software.  
[Official Website Of Python](https://www.python.org/)

If you didn't understand, Watch the video tutorial. [Click Here](https://youtu.be/dDfX_AyokjM)

### Step 2: Download VS Codium

Go to the browser and search VS Codium download. Open the official website, download the zip file from GitHub, and install it.
 [Official Website Of VS Codium]( https://vscodium.com/)

<img title="VS Codium" alt="VS Codium" src="/images/VSCodiumDownload.jpg">

### Alternative Methods

**Install with Brew (Mac)**
If you are on a Mac and have Homebrew installed:
```
brew install --cask vscodium
```
Note for Mac OS X Mojave users: if you see “App can’t be opened because Apple cannot check it for malicious software” when opening VSCodium the first time, you can right-click the application and choose Open. This should only be required the first time opening on Mojave.

**Install with Windows Package Manager (WinGet)**
If you use Windows and have Windows Package Manager installed:
```ruby
winget install vscodium
```

**Install with Chocolatey (Windows)**
If you use Windows and have Chocolatey installed (thanks to @Thilas):
```ruby
choco install vscodium
```

**Install with Scoop (Windows)**
If you use Windows and have Scoop installed:
```ruby
scoop bucket add extras
scoop install vscodium
```

**Install with snap (Linux)**
VSCodium is available in the Snap Store as Codium, currently maintained by the VSCodium project. If your GNU/Linux distribution has support for snaps:
```ruby
snap install codium --classic
```

**Install on Parrot OS**:
VSCodium is pre-installed in Parrot OS.
In case you don’t find it by default, you can retrieve it from the official Parrot repo
```ruby
sudo apt update && sudo apt install codium
```

**Install on Nix(OS)**
VSCodium is available in Nixpkgs. You can install it by adding vscodium to environment.systemPackages in configuration.nix, or locally:
```ruby
nix-env -iA nixpkgs.vscodium
```

**Install on Arch Linux**
VSCodium is available on the AUR (Arch User Repository), and can be installed with an AUR Helper.
Examples:
**Aura**:
```ruby
sudo aura -A vscodium-bin
```
**Yay**:
```ruby
yay -S vscodium-bin
```
Use a Package Manager (deb/rpm, provided by VSCodium related repository)
@paulcarroty has set up a repository for VSCodium. The instructions below are 
adapted from there with CDN mirror. Any issues installing VSCodium using your 
package manager should be directed to that repository’s issue tracker.
@jtagcat set up an hourly mirror of @paulcarroty’s repository.
To use the mirror, you may replace paulcarroty.gitlab.io/vscodium-deb-rpm-repo 
with vscodium.c7.ee in your package manager configuration.

**Install on Debian / Ubuntu (deb package)**:
Add the GPG key of the repository:
```ruby
wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.
gpg \
    | gpg --dearmor \
    | sudo dd of=/usr/share/keyrings/vscodium-archive-keyring.gpg
```
**Add the repository**:
```ruby
echo 'deb [ signed-by=/usr/share/keyrings/vscodium-archive-keyring.gpg ] 
https://download.vscodium.com/debs vscodium main' \
    | sudo tee /etc/apt/sources.list.d/vscodium.list
```
**Update then install vscodium**(if you want vscodium-insiders, then replace 
codium by codium-insiders):
```ruby
sudo apt update && sudo apt install codium
```

**Install on Fedora / RHEL / CentOS / RockyLinux / OpenSUSE (rpm package)**:
Add the GPG key of the repository:
```ruby
sudo rpmkeys --import https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/-/
raw/master/pub.gpg
```
**Add the repository**:
Fedora/RHEL/CentOS/Rocky Linux:
```ruby
printf "[gitlab.com_paulcarroty_vscodium_repo]\nname=download.vscodium.
com\nbaseurl=https://download.vscodium.com/rpms/
\nenabled=1\ngpgcheck=1\nrepo_gpgcheck=1\ngpgkey=https://gitlab.com/paulcarroty/
vscodium-deb-rpm-repo/-/raw/master/pub.gpg\nmetadata_expire=1h" | sudo tee -a /
etc/yum.repos.d/vscodium.repo
```
**OpenSUSE/SUSE**:
```ruby
printf "[gitlab.com_paulcarroty_vscodium_repo]\nname=gitlab.
com_paulcarroty_vscodium_repo\nbaseurl=https://download.vscodium.com/rpms/
\nenabled=1\ngpgcheck=1\nrepo_gpgcheck=1\ngpgkey=https://gitlab.com/paulcarroty/
vscodium-deb-rpm-repo/-/raw/master/pub.gpg\nmetadata_expire=1h" | sudo tee -a /
etc/zypp/repos.d/vscodium.repo
```
**Install the software**: (if you want vscodium-insiders, then replace codium 
by 
codium-insiders)
**Fedora/RHEL/CentOS/Rocky Linux**:
```ruby
sudo dnf install codium
```
**OpenSUSE/SUSE**:
```ruby
sudo zypper in codium
```

**Flatpak Option (Linux)**
VSCodium is (unofficially) available as a Flatpak app and here’s the build 
repo. If your distribution has support for flatpak, and you have enabled the 
flathub repo, you can install VSCodium via the command line:
```ruby
flatpak install flathub com.vscodium.codium
```
…or by opening the flatpakref file from Flathub. VSCodium can also be found in 
GNOME Software if you have gnome-software-plugin-flatpak installed (as 
recommended in the Flathub setup instructions).

**Source :-**
https://vscodium.com/
******

# Watch Video Tutorial On Youtube :-

{{< youtube dDfX_AyokjM >}}


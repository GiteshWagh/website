+++
authors= "Gitesh Wagh"
title = " Installation and Setup of Python and VS Codium - Python Tutorials For Beginners #1 "
date = "2023-04-02"
categories = "Python"
toc="true"
tags = [
  "Programming", 
  "Coding",
  "python",
  "PythonTutorial",
]
+++

## Introduction To Python
Python is the most straightforward programming language. Python is a versatile and widely-used programming language that was created by **Guido van Rossum** and released in **1991.**
It has gained immense popularity due to its readability, simplicity, and extensive libraries.

**Python is used for various purposes, including:**
1. Web Development (Server-Side):
* Python can power dynamic websites and web applications.
* Popular web frameworks like **Django, Flask, and FastAPI** are built using Python.

2. Software Development:
* Python is excellent for creating desktop applications, command-line tools, and utilities.
* It’s widely used in fields like data science, machine learning, and artificial intelligence.

3. Mathematics and Scientific Computing:
* Python provides powerful libraries like **NumPy**, **SciPy**, and **Pandas** for numerical computations and data analysis.
* It’s a favorite among **researchers**, **scientists**, and **engineers**.

4. System Scripting:
* Python is great for automating repetitive tasks, managing files, and interacting with the operating system.

## Download Python interpreter.

Note : Use only the [**Official Website Of Python**](https://www.python.org/) for downloading Python interpreter. Download an interpreter for your operating system. The process is too simple. Download and install it like software. Download according to your operating system of computer.   
  
[**Click Here To Download Python For Windows**](https://www.python.org/downloads/windows/)   
[**Click Here To Download Python For Linux**](https://www.python.org/downloads/source/)  
[**Click Here To Download Python For MacOS**](https://www.python.org/downloads/macos/)


If you didn't understand, [**Watch the video tutorial.**](https://youtu.be/dDfX_AyokjM)

<img title="Python Download" alt="Python Download" src="/images/PythonDownload.png">

*********
  
   
  
## Introduction To VS Codium

VS Codium is a free and open-source code editor that’s very similar to Visual Studio Code (VS Code). The key difference is that VS Codium removes all the proprietary components and services from Microsoft, making it fully transparent and telemetry-free. It’s like a privacy-focused version of VS Code. While both editors support extensions, VS Codium doesn’t include proprietary ones by default. So, if you value open-source software and want more control over your development environment, VSCodium is a great choice! 🚀🔍

Here’s a quick comparison between the two:

**VS Code:**
* Supports more extensions, including proprietary ones.
* Backed by Microsoft, so there’s extensive community support and rich documentation.
* Some parts are proprietary, which bothers some users.

**VS Codium:**
* Uses the MIT license, allowing modification and distribution without restrictions.
* No telemetry is enabled by default.
* Fewer extensions compared to VS Code, but it’s growing.

Remember, both tools have their strengths, so choose the one that aligns with your preferences! 😊

## Download VS Codium

Go to the browser and search VS Codium download. Open the official website, download the zip file from GitHub, and install it.
 [Official Website Of VS Codium]( https://vscodium.com/)

<img title="VS Codium" alt="VS Codium" src="/images/VSCodiumDownload.jpg">  

**********  
    
       
### Alternative Methods  

#### Install with Brew (Mac)  
If you are on a Mac and have Homebrew installed:
```
brew install --cask vscodium
```
Note for Mac OS X Mojave users: if you see “App can’t be opened because Apple cannot check it for malicious software” when opening VSCodium the first time, you can right-click the application and choose Open. This should only be required the first time opening on Mojave.

#### Install with Windows Package Manager (WinGet)  
If you use Windows and have Windows Package Manager installed:
```
winget install vscodium
```

#### Install with Chocolatey (Windows)  
If you use Windows and have Chocolatey installed (thanks to @Thilas):
```
choco install vscodium
```

#### Install with Scoop (Windows)   
If you use Windows and have Scoop installed:
```
scoop bucket add extras
scoop install vscodium
```

#### Install with snap (Linux)  
VSCodium is available in the Snap Store as Codium, currently maintained by the VSCodium project. If your GNU/Linux distribution has support for snaps:
```
snap install codium --classic
```

#### Install on Parrot OS    
VSCodium is pre-installed in Parrot OS.
In case you don’t find it by default, you can retrieve it from the official Parrot repo
```
sudo apt update && sudo apt install codium
```

#### Install on Nix(OS)   
VSCodium is available in Nixpkgs. You can install it by adding vscodium to environment.systemPackages in configuration.nix, or locally:
```
nix-env -iA nixpkgs.vscodium
```

#### Install on Arch Linux  
VSCodium is available on the AUR (Arch User Repository), and can be installed with an AUR Helper.
Examples:
##### Aura  
```
sudo aura -A vscodium-bin
```
##### Yay 
```
yay -S vscodium-bin
```
Use a Package Manager (deb/rpm, provided by VSCodium related repository)
@paulcarroty has set up a repository for VSCodium. The instructions below are 
adapted from there with CDN mirror. Any issues installing VSCodium using your 
package manager should be directed to that repository’s issue tracker.
@jtagcat set up an hourly mirror of @paulcarroty’s repository.
To use the mirror, you may replace paulcarroty.gitlab.io/vscodium-deb-rpm-repo 
with vscodium.c7.ee in your package manager configuration.

#### Install on Debian / Ubuntu (deb package)   
Add the GPG key of the repository:
```
wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.
gpg \
    | gpg --dearmor \
    | sudo dd of=/usr/share/keyrings/vscodium-archive-keyring.gpg
```
##### Add the repository  
```
echo 'deb [ signed-by=/usr/share/keyrings/vscodium-archive-keyring.gpg ] 
https://download.vscodium.com/debs vscodium main' \
    | sudo tee /etc/apt/sources.list.d/vscodium.list
```
#### Update then install vscodium  
(if you want vscodium-insiders, then replace 
codium by codium-insiders):  
```
sudo apt update && sudo apt install codium
```

#### Install on Fedora / RHEL / CentOS / RockyLinux / OpenSUSE (rpm package)  
Add the GPG key of the repository:  
```
sudo rpmkeys --import https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/-/
raw/master/pub.gpg
```
##### Add the repository   
Fedora/RHEL/CentOS/Rocky Linux:  
```
printf "[gitlab.com_paulcarroty_vscodium_repo]\nname=download.vscodium.
com\nbaseurl=https://download.vscodium.com/rpms/
\nenabled=1\ngpgcheck=1\nrepo_gpgcheck=1\ngpgkey=https://gitlab.com/paulcarroty/
vscodium-deb-rpm-repo/-/raw/master/pub.gpg\nmetadata_expire=1h" | sudo tee -a /
etc/yum.repos.d/vscodium.repo  
```
#### OpenSUSE/SUSE   
```
printf "[gitlab.com_paulcarroty_vscodium_repo]\nname=gitlab.
com_paulcarroty_vscodium_repo\nbaseurl=https://download.vscodium.com/rpms/
\nenabled=1\ngpgcheck=1\nrepo_gpgcheck=1\ngpgkey=https://gitlab.com/paulcarroty/
vscodium-deb-rpm-repo/-/raw/master/pub.gpg\nmetadata_expire=1h" | sudo tee -a /
etc/zypp/repos.d/vscodium.repo
```
#### Install the software
(if you want vscodium-insiders, then replace codium by codium-insiders)    
#### Fedora/RHEL/CentOS/Rocky Linux   
```
sudo dnf install codium
```
#### OpenSUSE/SUSE   
```
sudo zypper in codium
```

#### Flatpak Option (Linux)   
VSCodium is (unofficially) available as a Flatpak app and here’s the build 
repo. If your distribution has support for flatpak, and you have enabled the 
flathub repo, you can install VSCodium via the command line:

```
flatpak install flathub com.vscodium.codium
```
…or by opening the flatpakref file from Flathub. VSCodium can also be found in 
GNOME Software if you have gnome-software-plugin-flatpak installed (as 
recommended in the Flathub setup instructions).

**Source:**  
https://vscodium.com/


## Recommended Content 
1. [Why Coding Will Become The Most Valuable Skill In The Future?](https://giteshwagh.com/post/why-coding-will-become-the-most-valuable-skill-in-the-future/#tools-for-coding)  
2. [Basics Of Python - Python Tutorials For Beginners #2](https://giteshwagh.com/post/basics-of-python-tutorial-2/)  
3. [Variables And DataTypes - Python Tutorials For Beginners #3](https://giteshwagh.com/post/variables-and-datatypes-python-tutorial-3/)  

## Watch Video Tutorial


{{< youtube dDfX_AyokjM >}}


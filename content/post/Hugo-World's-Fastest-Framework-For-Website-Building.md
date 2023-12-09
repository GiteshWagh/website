+++
authors= "Gitesh Wagh"
title = " Hugo : World's Fastest Framework For Website Building 🔥 "
date = "2023-08-15"
categories = "Web Development"
description = ""
tags = [
    "hugo",
    "gohugo",
    "Web Development"
]
featureImage = "/images/Hugo.png"
thumbnail = "/images/Hugo.png"
toc = true
+++

Hey Guys👋,                                                                            

Let's Learn Everything About Hugo: The World's fastest Framework For Website Development.


## What Is Hugo?                                                                      

Hugo is the world's fastest framework for website building. Hugo is a fast and modern static site generator. Hugo is based on the Go programming language. It supports multiple free hosting platforms like Github, Gitlab, Netlify, etc. Hugo provides us with various templates for web designing at zero cost. Hugo is one of the popular frameworks for building a website in a few minutes. Hugo uses Go, HTML, CSS, etc. for its rich content.

# Hugo Features

* Zero cost for building a website.  
* Free hosting.  
* Fast speed( At **<1ms** per page ).    
* No coding skills are required.  
* Secure and responsive site.  
* Amazing themes and template support.    
* Image processing.  
* Support **Go, HTML, CSS, etc.** programming languages for new features.  
* Support **Github, Gitlab, Netlify, etc.**  
* Amamzing content management.  

## How To Download Hugo?

For downloading Hugo go to **[gohugo.io.](https://gohugo.io/installation/)** Which is the official website of Hugo. We use various methods For downloading Hugo.

Use Following Commands As Per Your Operating System For Downloading Hugo.

### 1. Windows

1. Chocolatey  

Chocolatey is a free and open-source package manager for Windows. This will install the extended edition of Hugo:

```
choco install hugo-extended
```

2. Scoop  

Scoop is a free and open-source package manager for Windows. This will install the extended edition of Hugo:

```
scoop install hugo-extended
```

3. Winget  

Winget is Microsoft’s official free and open-source package manager for Windows. This will install the extended edition of Hugo:

```
winget install Hugo.Hugo.Extended
```

4. Docker  

Erlend Klakegg Bergheim graciously maintains Docker images based on images for Alpine Linux, Busybox, Debian, and Ubuntu.

```
docker pull klakegg/hugo
```

### 2. Linux                                                                      

1. Snap                                                                              

Snap is a free and open-source package manager for Linux. Available for most distributions, snap packages are simple to install and are automatically updated.

The Hugo snap package is strictly confined. Strictly confined snaps run in complete isolation, up to a minimal access level that’s deemed always safe. The sites you create and build must be located within your home directory, or on removable media.

This will install the extended edition of Hugo:

```
sudo snap install hugo
```

To enable or revoke access to removable media:

```
sudo snap connect hugo:removable-media
sudo snap disconnect hugo:removable-media
```

To enable or revoke access to SSH keys:

```
sudo snap connect hugo:ssh-keys
sudo snap disconnect hugo:ssh-keys
```

2. Homebrew    

Homebrew is a free and open-source package manager for **macOS and Linux.** This will install the extended edition of Hugo:

```
brew install hugo
```

Repository packages  

Most Linux distributions maintain a repository for commonly installed applications. Please note that these repositories may not contain the latest release.

3. Arch Linux  

Derivatives of the Arch Linux distribution of Linux include EndeavourOS, Garuda Linux, Manjaro, and others. This will install the extended edition of Hugo:

```
sudo pacman -S hugo
```

4. Debian  

Derivatives of the Debian distribution of Linux include elementary OS, KDE neon, Linux Lite, Linux Mint, MX Linux, Pop!_OS, Ubuntu, Zorin OS, and others. This will install the extended edition of Hugo:

```
sudo apt install hugo
```

You can also download Debian packages from the latest release page.

5. Fedora  

Derivatives of the Fedora distribution of Linux include CentOS, Red Hat Enterprise Linux, and others. This will install the extended edition of Hugo:

```
sudo dnf install hugo
```

6. openSUSE  

Derivatives of the openSUSE distribution of Linux include GeckoLinux, Linux Karmada, and others. This will install the extended edition of Hugo:

```
sudo zypper install hugo
```

7. Solus  

The Solus distribution of Linux includes Hugo in its package repository. This will install the standard edition of Hugo:

```
sudo eopkg install hugo
```

8. Docker  

Erlend Klakegg Bergheim graciously maintains Docker images based on images for Alpine Linux, Busybox, Debian, and Ubuntu.

```
docker pull klakegg/hugo
```

### 3. MacOS

1. Homebrew  

Homebrew is a free and open-source package manager for macOS and Linux. This will install the extended edition of Hugo:

```
brew install hugo
```

2. MacPorts  

MacPorts is a free and open-source package manager for macOS. This will install the extended edition of Hugo:

```
sudo port install hugo
```

3. Docker  

Erlend Klakegg Bergheim graciously maintains Docker images based on images for Alpine Linux, Busybox, Debian, and Ubuntu.

```
docker pull klakegg/hugo
```

## Required Elements

1. [Install Hugo (extended edition, v0.112.0 or later)](https://gohugo.io/installation/)

2. [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Important Commands

Create a main directory or folder of your website. Site_Name is the name of the folder:

```
hugo new site Site_Name
```

Go to the main directory:

```
cd Site_Name
```

Initialize a Git repository in the current directory:

```
git init
```

Watch the site on your device on localhost:1313 :

```
hugo server
```

Saw Hugo version:

```
hugo version:
```

The result is something like:

```
hugo v0.105.0-0e3b42b4a9bdeb4d866210819fc6ddcf51582ffa+extended linux/amd64 BuildDate=2022-10-28T12:29:05Z VendorInfo=snap:0.105.0
```

For saw other commands:

```
hugo help
```

To get help with a subcommand, use the --help after command. Ex:

```
hugo server --help
```

For building site. It creates a public directory of the site. A public directory is important for publishing a site:

```
hugo
```

## Directories

Each theme of Hugo contains its unique directory structure. Each directory of the site is important.

### 1. archetypes

The archetypes directory contains templates and settings for content. **[See Details](https://gohugo.io/content-management/archetypes/)**

### 2. assets

The assets directory mainly contains CSS, Javascript, and Sass scripts. **[See Details](https://gohugo.io/hugo-pipes/introduction/)**

### 3. config

The config directory is very important. It contains configuration files to configure, design, and arrange the site. **[See Details](https://gohugo.io/getting-started/configuration/#configuration-directory)**

### 4. content

The content directory contains the content of the website. It mainly contains markdown files. It contains blogs on the site. **[See Details](https://gohugo.io/content-management/organization/)**

### 5.i18n

The directory i18n helps to use multiple languages. **[See Details](https://gohugo.io/content-management/multilingual/)**

### 6. public

The public directory is a published website. It helps to host the site. **[See Details](https://gohugo.io/getting-started/usage/#build-your-site)**

### 7. resources

The resources directory contains important scripts of code and images.

### 8. static

The static directory is one of the important directory of the site and contains fonts, logos, images, icons, etc... **[See Details](https://gohugo.io/content-management/static-files/)**

### 9.themes

The directory theme contains **[themes](https://themes.gohugo.io/)** of the site.

> **Source - https://gohugo.io/documentation/**
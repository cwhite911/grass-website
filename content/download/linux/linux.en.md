---
type: "pages"
layout: "os"
---

## Download GRASS for Linux {#linux}

{{< support-button style="outline" text="Support Us">}}

## Installation

Install grass package on your Linux distribution. Have a look at [Repology](https://repology.org/project/grass-gis/versions)
              for an extended list of GRASS packages or directly check the [packaging status](https://repology.org/badge/vertical-allrepos/grass-gis.svg?exclude_unsupported=1&exclude_sources=modules,site&minversion=%3Cspan%3E%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%20%208.4.1%20%20%20%20%20%20%20%20%20%20%20%20%3C/span%3E&columns=3) to quickly know which GRASS version is currently available for your distro.

### Ubuntu

Add the ubuntugis-unstable PPA to your system:

    sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable

Update your package list:

    sudo apt update

Install with the following shell command:

    sudo apt install grass

For more information visit [ubuntugis-unstable](https://launchpad.net/~ubuntugis/+archive/ubuntu/ubuntugis-unstable).

### Generic 64-bit

Download the latest weekly GRASS binary [snapshot](https://grass.osgeo.org/grass84/binary/linux/snapshot/).

    curl -O https://grass.osgeo.org/grass84/binary/linux/snapshot/grass-8.4.2dev-x86_64-pc-linux-gnu-18_07_2025-install.sh

Make the script executable:

    chmod +x grass-8.4.2dev-x86_64-pc-linux-gnu-18_07_2025-install.sh

Install with the following shell command:

    sh grass-8.4.2dev-x86_64-pc-linux-gnu-18_07_2025-install.sh

For more information visit [snapshot](https://grass.osgeo.org/grass84/binary/linux/snapshot/).

### Debian

Install with the following shell command:

    sudo apt install grass

For more information visit [Debian GRASS](https://packages.debian.org/grass).

### Fedora

Install with the following shell command:

    sudo dnf install grass

For more information visit [Fedora GRASS](https://packages.fedoraproject.org/pkgs/grass/grass/).

### Arch Linux

Install with the following shell command:

    sudo pacman -S grass

For more information visit [Arch Linux GRASS](https://aur.archlinux.org/packages/grass/).

### EPEL8

Install with the following shell command:

    sudo yum install grass

For more information visit [EPEL8 (RHEL8/Centos8) packages](https://packages.fedoraproject.org/pkgs/grass/grass/).

### Gentoo

Install with the following shell command:

    sudo emerge grass

For more information visit [Gentoo GRASS](https://packages.gentoo.org/packages/sci-geosciences/grass).

### OpenSUSE

Install with the following shell command:

    sudo zypper install grass

For more information visit [OpenSUSE GRASS](https://build.opensuse.org/package/show/Application:Geo/grass).

## Compile and install

To compile and install GRASS from source, follow these steps from the [GRASS wiki](https://grasswiki.osgeo.org/wiki/Compile_and_Install).

## Contribute

Please consider a financial contribution to the GRASS project to help us improve and maintain the software.

{{< support-button style="solid" text="Support Us">}}

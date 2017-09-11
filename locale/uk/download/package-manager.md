---
layout: page.hbs
title: Installing Node.js via package manager
---

# Installing Node.js via package manager

***Note:*** The packages on this page are maintained and supported by their respective packagers, **not** the Node.js core team. Please report any issues you encounter to the package maintainer. If it turns out your issue is a bug in Node.js itself, the maintainer will report the issue upstream.

----------------------------

* [Arch Linux](#arch-linux)
* [Debian and Ubuntu based Linux distributions](#debian-and-ubuntu-based-linux-distributions)
* [Enterprise Linux and Fedora](#enterprise-linux-and-fedora)
* [FreeBSD and OpenBSD](#freebsd-and-openbsd)
* [Gentoo](#gentoo)
* [NetBSD](#netbsd)
* [openSUSE and SLE](#opensuse-and-sle)
* [macOS](#macos)
* [SmartOS and illumos](#smartos-and-illumos)
* [Void Linux](#void-linux)
* [Windows](#windows)

----------------------------

## Arch Linux

Node.js and npm packages are available in the Community Repository.

```bash
pacman -S nodejs npm
```


## Debian and Ubuntu based Linux distributions

Also including: **Linux Mint**, **Linux Mint Debian Edition (LMDE)**, **elementaryOS** and others.

Node.js is available from the [NodeSource](https://nodesource.com) Debian and Ubuntu binary distributions repository (formerly [Chris Lea's](https://github.com/chrislea) Launchpad PPA). Support for this repository, along with its scripts, can be found on GitHub at [nodesource/distributions](https://github.com/nodesource/distributions).

**NOTE:** If you are using Ubuntu Precise or Debian Wheezy, you might want to read about [running Node.js >= 4.x on older distros](https://github.com/nodesource/distributions/blob/master/OLDER_DISTROS.md).

```bash
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Alternatively, for Node.js v6:

```bash
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
sudo apt-get install -y nodejs
```

***Optional***: install build tools

To compile and install native addons from npm you may also need to install build tools:

```bash
sudo apt-get install -y build-essential
```

**Available architectures:**

* **i386** (32-bit)
* **amd64** (64-bit)
* **armhf** (ARM 32-bit hard-float, ARMv7 and up: _arm-linux-gnueabihf_)

**Supported Ubuntu versions:**

* **Ubuntu 14.04 LTS** (Trusty Tahr)
* **Ubuntu 16.04 LTS** (Xenial Xerus)

**Supported Debian versions:**

* **Debian 7** (wheezy)
* **Debian 8 / stable** (jessie)
* **Debian testing** (stretch, aliased to jessie)
* **Debian unstable** (sid)

A Node.js package is also available in the [official repo](http://packages.debian.org/search?searchon=names&keywords=nodejs) for Debian Sid (unstable), Jessie (testing) and Wheezy (wheezy-backports) as "nodejs". It only installs a `nodejs` binary.

The [nodejs-legacy package](http://packages.debian.org/search?searchon=names&keywords=nodejs-legacy) installs a `node` symlink that is needed by many modules to build and run correctly.
The Node.js modules available in the distribution official repositories do not need it.

**Supported Linux Mint versions:**

* **Linux Mint 17 "Qiana"** (via Ubuntu 14.04 LTS)
* **Linux Mint 17.1 "Rebecca"** (via Ubuntu 14.04 LTS)
* **Linux Mint 17.2 "Rafaela"** (via Ubuntu 14.04 LTS)
* **Linux Mint Debian Edition (LMDE) 2 "Betsy"** (via Debian 8)

**Supported elementary OS versions:**

* **elementary OS Freya** (via Ubuntu 14.04 LTS)

**Supported Trisquel versions:**

* **Trisquel 7 "Belenos"** (via Ubuntu 14.04 LTS)

**Supported BOSS versions:**

* **BOSS 5.0 "Anokha"** (via Debian 7)

## Enterprise Linux and Fedora

Including **Red Hat® Enterprise Linux®** / **RHEL**, **CentOS** and **Fedora**.

Node.js is available from the [NodeSource](https://nodesource.com) Enterprise Linux and Fedora binary distributions repository. Support for this repository, along with its scripts, can be found on GitHub at [nodesource/distributions](https://github.com/nodesource/distributions).

Note that the Node.js packages for EL 5 (RHEL5 and CentOS 5) depend on the **[EPEL](https://fedoraproject.org/wiki/EPEL)** repository being available. The setup script will check and provide instructions if it is not installed.

Run as root on RHEL, CentOS or Fedora, for Node.js v4 LTS Argon:

```bash
curl --silent --location https://rpm.nodesource.com/setup_4.x | bash -
```

Alternatively for Node.js v6:

```bash
curl --silent --location https://rpm.nodesource.com/setup_6.x | bash -
```

Alternatively for Node.js 0.10:

```bash
curl --silent --location https://rpm.nodesource.com/setup | bash -
```

Then install, as root:

```bash
yum -y install nodejs
```

***Optional***: install build tools

To compile and install native addons from npm you may also need to install build tools:

```bash
yum install gcc-c++ make
# or: yum groupinstall 'Development Tools'
```

**Available architectures:**

* **i386** (32-bit, not available for EL7)
* **x86_64** (64-bit)

**Supported Red Hat® Enterprise Linux® versions:**

* **RHEL 5** (32-bit and 64-bit)
* **RHEL 6** (32-bit and 64-bit)
* **RHEL 7** (64-bit)

**Supported CentOS versions:**

* **CentOS 5** (32-bit and 64-bit)
* **CentOS 6** (32-bit and 64-bit)
* **CentOS 7** (64-bit)

**Supported CloudLinux versions:**
* **CloudLinux 6** (32-bit and 64-bit)

**Supported Fedora versions:**

* **Fedora 21 (Twenty One)** (32-bit and 64-bit)
* **Fedora 20 (Heisenbug)** (32-bit and 64-bit)
* **Fedora 19 (Schrödinger's Cat)** (32-bit and 64-bit)

**Other distributions known to be supported:**

* **Oracle Linux** (mirrors RHEL very closely)
* **Amazon Linux** (tested on 2014.03)

### Alternatives

Official **Fedora** [Node.js](https://apps.fedoraproject.org/packages/nodejs) and [npm](https://apps.fedoraproject.org/packages/npm) packages are available in Fedora 18 and later.  Install with:

```bash
sudo yum install nodejs npm
```

In a hurry for the latest updates?  [Grab them from updates-testing.](https://fedoraproject.org/wiki/QA:Updates_Testing)

**Enterprise Linux** (RHEL and CentOS) users may use the Node.js and npm packages from the [EPEL](https://fedoraproject.org/wiki/EPEL) repository.

Install the appropriate *epel-release* RPM for your version (found on the [EPEL](https://fedoraproject.org/wiki/EPEL) repository homepage), then run:

```bash
sudo yum install nodejs npm --enablerepo=epel
```

In a hurry for the latest updates?  [Grab them from epel-testing.](https://fedoraproject.org/wiki/EPEL/testing)

**Available architectures:**

* **i686** (32-bit, not available for EL7)
* **x86_64** (64-bit)
* **armv6hl** (Raspberry Pi, [Pidora](http://pidora.ca) only)
* **armv7hl** (32-bit ARM hard-float, ARMv7 and up, Fedora only)

**Supported Red Hat® Enterprise Linux® versions:**

* **RHEL 6** (i686/x86_64)
* **RHEL 7** (x86_64)

Additionally, versions of **CentOS** and **Scientific Linux** corresponding to the above RHEL versions are also officially supported by all EPEL packages, including nodejs.  Amazon Linux is not officially supported by EPEL due to significant incompatibilities previously reported to the epel-devel mailing list, however you might find that nodejs at least still works.

**Supported Fedora versions:**

* **Fedora Rawhide** (i686/x86_64/armv7hl)
* **Fedora 21** (i686/x86_64/armv7hl)
* **Fedora 20 (Heisenbug)** (i686/x86_64/armv6hl/armv7hl)
* **Fedora 19 (Schrödinger's Cat)** (i686/x86_64/armv7hl)


## FreeBSD and OpenBSD

Node.js is available through the ports system.

```bash
/usr/ports/www/node
```

Development versions are also available using ports

```bash
cd /usr/ports/www/node-devel/ && make install clean
```

Or packages on FreeBSD:

```bash
pkg_add -r node-devel
```

Using [pkg-ng](https://wiki.freebsd.org/pkgng) on FreeBSD

```bash
pkg install node
```

Or the development versions:

```bash
pkg install node-devel
```


## Gentoo

Node.js is available in the portage tree.

```bash
emerge nodejs
```


## NetBSD

Node.js is available in the pkgsrc tree:

```bash
cd /usr/pkgsrc/lang/nodejs && make install
```

Or install a binary package (if available for your platform) using pkgin:

```bash
pkgin -y install nodejs
```


## openSUSE and SLE

[Download Node.js via openSUSE one-click](http://software.opensuse.org/download.html?project=devel%3Alanguages%3Anodejs&package=nodejs).

Available RPM packages for: openSUSE 11.4, 12.1, 12.2, 12.3, 13.1, Factory and Tumbleweed; SLE 11 (with SP1/SP2/SP3 variations).

Example install on openSUSE 13.1:

```bash
sudo zypper ar \
  http://download.opensuse.org/repositories/devel:/languages:/nodejs/openSUSE_13.1/ \
  Node.js
sudo zypper in nodejs nodejs-devel
```


## macOS

Simply download the [Macintosh Installer](http://nodejs.org/#download) direct from the [nodejs.org](http://nodejs.org) web site.

_If you want to download the package with bash:_

```bash
curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg</a>.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg" -target "/"
```

### Alternatives

Using **[Homebrew](http://brew.sh/)**:

```bash
brew install node
```

Using **[MacPorts](http://www.macports.org/)**:

```bash
port install nodejs<major version>

# Example
port install nodejs7
```

Using **[pkgsrc](https://pkgsrc.joyent.com/install-on-osx/)**:

Install the binary package:

```bash
pkgin -y install nodejs
```

Or build manually from pkgsrc:

```bash
cd pkgsrc/lang/nodejs && bmake install
```

## SmartOS and illumos

SmartOS images come with pkgsrc pre-installed.  On other illumos distributions, first install **[pkgsrc](https://pkgsrc.joyent.com/install-on-illumos/)**, then you may install the binary package as normal:

```bash
pkgin -y install nodejs
```

Or build manually from pkgsrc:

```bash
cd pkgsrc/lang/nodejs && bmake install
```


## Void Linux

Void Linux ships node.js stable in the main repository.

```bash
xbps-install -Sy nodejs
```


## Windows

Simply download the [Windows Installer](http://nodejs.org/#download) directly from the [nodejs.org](http://nodejs.org) web site.

### Alternatives

Using **[Chocolatey](http://chocolatey.org)**:

```bash
cinst nodejs
# or for full install with npm
cinst nodejs.install
```

Using **[Scoop](http://scoop.sh/)**:

```bash
scoop install nodejs
```

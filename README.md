# Minigalaxy

A simple GOG client for Linux that lets you download and play your GOG Linux games

![screenshot](screenshot.png?raw=true)

## Features

The most important features of Minigalaxy:

- Log in with your GOG account
- Download the Linux games you own on GOG
- Launch them

In addition to that, Minigalaxy also allows you to:

- Select in which language you'd prefer to download your games
- Change where games are installed
- Search your GOG Linux library
- Show all games or just the ones you've installed
- View the error message if a game fails to launch

## Installation

**Ubuntu/Debian**

```sh
sudo apt-get install git python3-gi python3-gi-cairo gir1.2-gtk-3.0 gir1.2-webkit2-4.0 python3-requests
git clone https://github.com/sharkwouter/minigalaxy.git
cd minigalaxy/bin
./minigalaxy
```

Packages for Ubuntu, Debian and Arch are coming soon!

## Known issues

Expect to see the following issues:

* Using Minigalaxy without an internet connection does not work
* Changing the installation directory makes Minigalaxy unable to detect previously installed games

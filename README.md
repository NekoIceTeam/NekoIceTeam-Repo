<h1 align="center">NekoIceTeam-Repo</h1>

## Navigation
- [Introduction](#introduction)
- [Installation](#installation)
- [License](https://github.com/NekoIceTeam/NekoIceTeam-Repo/blob/main/LICENSE)

## Introduction
NekoIceTeam repo for NekoArchNya projects, also working for ArchLinux

## Installation
1.Add NekoIceCream gpg key 
```
pacman-key -r 80DDC2314727CBD9477EC94D8E02DA8285638FD2
```
```
pacman-key --lsign-key 80DDC2314727CBD9477EC94D8E02DA8285638FD2
```
2. Add NekoIceTeam repo to /etc/pacman.conf
```
[nekoiceteam]
Server = https://nekoiceteam.github.io/NekoIceTeam-Repo/os/$arch
```
3. Sync pacman
```
pacman -Sy
```



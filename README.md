# Linux ( Operating System )

![alt text](https://cdn.wallpapersafari.com/58/27/Bytxi1.jpg)

<script src="https://cdnjs.cloudflare.com/ajax/libs/js-sequence-diagrams/1.0.6/sequence-diagram-min.js" ></script>

## Operating System Layers

- `BIOS` `UEFI`
- `GRUB` `GRUB2`
- `VM Linux` `VM Linuz`
    - `Init Ram Disk`
    - `Init File Systems`
- `Full Kernal`

## Flavours

- `Red Hat` Commercial Linux Ditrubution intended for Servers & WorkStations
- `Fedora` Sponsered by Red Hat
- `Debian` Free & Open-Source Software
- `Others`
    - `Ubuntu`
    - `Linux Mint`
    - `Cent OS`
    - `Suse` `OpenSuse`

## Foundation

### Kernal

Computer Program that allocates System Resources & Coordinate all the Details of the Computer Internals. Users Communicate with `OS` using `Shell`

- `Applications`
    - `Kernal` 
        - `CPU`
        - `Memory`
        - `Devices`

### Shell

It is a Command Line Interpreter (CLI). It translates User Commands to Kernal Understandable Commands

**Shell Script**

Contains List of Shell Commands in the Execution Order 

## Main Directories/Folders

- `cd /boot` Main Boot Folder
- `cd /etc/modules` Linux Modules
- `cd /etc/modprobe.d/` Linux BlackList
- `cat /etc/default/grub` Grub File Configurations

## Linux Basic Commands

| # | Commands | Flags | Args | Description |
| :-: | :--------: | :-----: | :----: | :-----------: |
|  | `pwd` |  |  | Return Complete Current Path |

- `ls *` 
- `vi /etc/modules` To Open a File, To Edit
    - Use `q!` to Quit
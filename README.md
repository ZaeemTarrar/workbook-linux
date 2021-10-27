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

### Global Flags & Commands

`--help` `help` `man`

### Terminal Terms

`Wild Card` `Search` `Flags` `Arguments` `Command Substitution`


| # | Commands | Example | Description |
| :-: | :--------: | :-------: | :----------- | 
| :orange_book: | `pwd` | | Return Complete Current Path |
| :orange_book: | `echo` | `echo -e "Hello World \n Good !"` `echo *` `echo $SHELL` `echo $((2+9))` `echo abc{x,y,z}` `echo Number_{1..5}` `echo file_{a..z}` | To Print | 
| :orange_book: | `sudo` | `sudo npm start` `sudo mkdir hello` | Runs a Commands with Admin Priviliges | 
| :orange_book: | `clear` | | Clears the Console/Terminal |
| :orange_book: | `cd` | `cd "./Movies/"` `cd Videos` | Redirect to the Specified Path | 
| :orange_book: | `ls` | `ls -lh *.py | sort | grep *hello` | Returns the List of Files/Folders |
| :orange_book: | `ln` | `ln -s ./Desktop/test1 baz` | Creates Symbolic Links |
| :orange_book: | `readlink` | `readlink -m baz` | Creates Symbolic Links |
| :orange_book: | `cat` | `cat /etc/default/gurb` | | 
| :orange_book: | `less` |  | |
| :orange_book: | `file` |  | |
| :orange_book: | `grep` | | Used for Search Queries |
| :orange_book: | `sort` | | Used for Sorting |
| :orange_book: | `mv` |  | |
| :orange_book: | `cp` |  | |
| :orange_book: | `rm` |  | |
| :orange_book: | `mkdir` | `mkdir fold1` `mkdir -v -p fold2` `mkdir fold1 fold2` | Creates One or More Folders<br />`p` Hide Message If Already Exists<br />`v` Shows Process Verbose |
| :orange_book: | `rmdir` |  | |
| :orange_book: | `chmod` |  | |
| :orange_book: | `nano` | | Opens an Editor to Edit Files via Terminal |
| :orange_book: | `cal` |  | Shows Calendar |
| :orange_book: | `date` |  | Shows Current Date |
| :orange_book: | `exit` |  | Ternimates the Terminal |
| :orange_book: | `diff` | `diff -s ./Desktop/abc baz` | Reports file differences |
| :orange_book: | `grep` | | |
| :orange_book: | `head` | `head -n 5 abc.txt` | |
| :orange_book: | `tail` | | |
| :orange_book: | `env` | | Shows Global/Environment Variables |
| :orange_book: | `cat` | | Reads a File |
| :orange_book: | `unlink` | | Deletes a File |
| :orange_book: | `touch` | | Creates a File |
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

### Etc

`group` `shadow` `boot` `sudoers` `skel` `.bash*` `yum.repos.d`

| # | Commands | Example | Description |
| :-: | :--------: | :-------: | :----------- | 
| :orange_book: | `pwd` | | Return Complete Current Path |
| :orange_book: | `echo` | `echo -e "Hello World \n Good !"` `echo *` `echo $SHELL` `echo $((2+9))` `echo abc{x,y,z}` `echo Number_{1..5}` `echo file_{a..z}` | To Print | 
| :orange_book: | `sudo` | `sudo npm start` `sudo mkdir hello` | Runs a Commands with Admin Priviliges | 
| :orange_book: | `clear` | | Clears the Console/Terminal |
| :orange_book: | `cd` | `cd "./Movies/"` `cd Videos` | Redirect to the Specified Path | 
| :orange_book: | `ls` | `ls -lh *.py | sort | grep *hello` `ls -Zalh` | Returns the List of Files/Folders |
| :orange_book: | `ln` | `ln -s ./Desktop/test1 baz` | Creates Symbolic Links |
| :orange_book: | `readlink` | `readlink -m baz` | Creates Symbolic Links |
| :orange_book: | `cat` | `cat /etc/default/gurb` | | 
| :orange_book: | `less` |  | |
| :orange_book: | `file` |  | |
| :orange_book: | `grep` | | Used for Search Queries |
| :orange_book: | `sort` | | Used for Sorting |
| :orange_book: | `mv` |  | To Relocate/Rename a Folder/File |
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
| :orange_book: | `fdisk` | |  |
| :orange_book: | `yum` | | |
| :orange_book: | `apt` | | |
| :orange_book: | `apt-get` | | |
| :orange_book: | `mkfs` | | |
| :orange_book: | `tuned` | | |
| :orange_book: | `tuned-adm` | | |
| :orange_book: | `tune2fs` | | |
| :orange_book: | `w` | | |
| :orange_book: | `last` | | |
| :orange_book: | `passwd` | | To set Password |
| :orange_book: | `users` | | |
| :orange_book: | `useradd` | | |
| :orange_book: | `userdel` | | |
| :orange_book: | `usermod` | `usermod -L zaeem` `usermod -U zaeem` | `To Lock/UnLock Account` |
| :orange_book: | `id` | `id zaeem` | |
| :orange_book: | `whoami` | | |
| :orange_book: | `which` | `which passwd` `which bash` `which python` `which pearl` | |
| :orange_book: | `umask` | `umask u-x,g=r,o+w` | |
| :orange_book: | `chmod` | `chmod u-x,g=r,o+w fold1` `chmod 745` | |
| :orange_book: | `setfacl` | `setfacl -d -m group:name:rwx /path/to/your/dir` | Sets Permissions for Specific Folder |
| :orange_book: | `chown` | `chown user:group fold1` | C hange User/Group Access |
| :orange_book: | `chcon` | `chcon -t conf_t fold1` | Change Configuration Type |
| :orange_book: | `restorecon` | `restorecon fold1` | Restore Configurations |
| :orange_book: | `kill` | `kill 5115` | Kills a Process |
| :orange_book: | `ps` | | |
| :orange_book: | `jobs` | | |
| :orange_book: | `rpm` | `rpm -qa` | |
| :orange_book: | `yum` | `yum install something` `yum update something` `yum search something` | |
| :orange_book: | `gcc` | `gcc hello.c` `gcc hello.c -o hello ` | |
| :orange_book: | `make` | `make` `make clean` | |
| :orange_book: | `fg` |  | |
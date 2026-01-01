# Arch Linux & Windows 11 Dual-Boot Resources

Links to everything that helped me get a smooth install and prepare for the ways Windows 11 likes to destroy your setup

## Installation Guides

### Archwiki Must-Reads:
* [Installation Guide](https://wiki.archlinux.org/title/Installation_guide#) 
* [Dual Boot w/Windows Guide](https://wiki.archlinux.org/title/Dual_boot_with_Windows#)


### Dual-Boot Walkthroughs
* [Useful Github Gist focused specifically on Arch x Win11](https://gist.github.com/trustytrojan/360430af7887b94887a0b26f6a4edfa6)
* [Rob Braxman Tech Tutorial](https://www.youtube.com/watch?v=HSZKouwQm9Y)
    * One of the most useful videos since he discusses all the ways you can prevent Windows 11 from overriding your boot partition. 
    > **NOTE**: He dual-boots Ubuntu and mentions to have Linux set the hardware clock to localtime. [The Archwiki](https://wiki.archlinux.org/title/Dual_boot_with_Windows#Time_standard) recommends to make both Windows/Linux [set the hardware clock to UTC](https://wiki.archlinux.org/title/System_time#UTC_in_Microsoft_Windows).


### Arch Install Walkthrough
* [Bread on Penguins Arch Installation Guide](https://www.youtube.com/watch?v=5DHz23VQJxk)

<br>

## Other Tools

### [GParted](https://gparted.org/)
**Disk Partitioning Tool**

If Windows is not letting you shrink the `C:` partition even though you removed hibernation, paging, and system restore files, use GParted to shrink it. It's also very convenient to use to create your Linux partitions.

* [KMD Tech Tutorial](https://www.youtube.com/watch?v=MhPwXJNS4uA)
* [eKiwi Tutorial](https://www.youtube.com/watch?v=vlVXPtJ20hA)


### [Clonezilla](https://clonezilla.org/)
**Disk/Partition Cloning & Imaging Tool**

Take regular backups of your partitions - *especially your boot partition/ESP* - since Windows could override this and destroy your setup.

* [KMD Tech Tutorial](https://www.youtube.com/watch?v=Urfc6B8w0W0)  
* [Rob Braxman Tech Tutorial](https://www.youtube.com/watch?v=Py8b4218cP8*)
* [Veronica Explains Tutorial](https://www.youtube.com/watch?v=qFV19WweP7M)  
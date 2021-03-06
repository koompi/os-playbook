## System Maintenance

Regular system maintenance is necessary for the proper function of your system in the long run. Below are some actions you can take.

### Upgrading the System
It is recommended for you to perform full system upgrades regularly via Upgrading packages to enjoy both the latest bug fixes and security updates, and to avoid having to deal with too many package upgrades that require manual intervention at once.

*Note: When you are requesting support from the community, it will usually be assumed that your system is up to date.* 

*You may view all commands for the following actions at the end of the section.*

### Alerts during an Upgrade
When upgrading the system, be sure to pay attention to the alert notices provided by the system. If any additional actions are required, be sure to do them right away.

### Restart/Reboot after Upgrades
Upgrades are typically not applied to existing processes. You must restart processes to fully apply the upgrade.

### Checking for Orphans/Dropped Packages
After upgrading you may have packages that are no longer needed or that are no longer in the official server.

Those packages will be shown as messages at the end of your system updating. If new packages are needed, it is recommended to install them. Otherwise, if they are no longer needed, they can be removed by removing the command.

### Be Careful with Unofficial Packages
To simplify maintenance, limit the number of unofficial packages and make sure you only install packages of applications and software through commands that have been provided by Archlinux. 

### Update the Mirrorlist
Update system mirror, as the quality of mirrors can vary over time, and some might go offline or their download rate might degrade.

### Clean the Filesystem
It is important to remove unwanted packages from your system.

### Refreshing Key Ring/Signature
If you might face errors with keyring and key signature while updating, just refresh it.

The commands you need to know well in order to maintain your system:

|Name|Commands|
|----|:------:|
|Updating System|pi -Syu|
|Remove Package|pi -Rdd <package keyword>|
|Refresh Mirror|
|Clean Filesystem|pi -Scc|
Refresh Key Ring|sudo pacman-key –refresh-keys|
|Refresh Key Signature|sudo pacman -S archlinux-keyring |

----
----


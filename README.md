# Jamf Connect Menu Bar App Packager


<p align="center">
<img width="512" alt="CantScript Logo" src="https://github.com/cantscript/AxM_API/blob/main/CantScript_Full_DotComV7.png">
</p>


In recent releases of Jamf Connect the menu bar app is not included in favour of using Self Service + for Jamf Pro Admins...but what if you're a Jamf School Admin wanting to keep local and cloud passwords in sync with Connect? In the blog, [Continue To Sync Passwords with Jamf Connect and Jamf School]() we explore the options and workflows.


#### Blog Resources
**[JCMenuPkgr]()** <br>

* Clone or download repo
* Keep JCMenuPkgr.sh in the folder enclosed folder
* Add the extracted Jamf Connect Menu Bar App (see blog for details) to `payload/Applications`
* Run JCMenuPkgr.sh, a resulting pkg will be saved to your desktop.
* There are a number of attributes that should be edited by an Admin to set the name and other attributes of the package
* Logic within the script to produce signed or unsigned pkg depending on your needs

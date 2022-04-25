# litespeed-images

How To Create OpenLiteSpeed + Wordpress Cloud Image:
1. Launch a Server
Choose the Long Term Support version for the base image, e.g. Ubuntu 20.04.

Select a basic plan from the cloud platform.

Server Requirement Suggestions
At least 700 MB of RAM
At least 7GB of Disk space
2. Install OLS + WordPress
You can use a single command to install WordPress easily. It is totally free and does not require any kind of license.

bash <( curl -sk https://mirror.iranserver.com/lscloud/wpimgsetup.sh )
This installation may take around 7~10 minutes to finish.

3. Install Launch script
bash <( curl -sk https://mirror.iranserver.com/lscloud/claunch.sh ) 
This step may clean up all SSH access methods, which means once you exit the server, you will not be able to SSH back

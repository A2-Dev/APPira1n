# APPira1n
Bash script to turn Pi4 running rasbian lite into wireless access point to run checkra1n/webra1n

***Note:***  
This was intended to be installed on a fresh Raspbian install without any other purpose.  
This script will turn your wifi connectivity off and turn it into an access point.  
Shell connections can only be made by connecting to the wireless access point or through an ethernet connection.  
Proceed with caution!

**Install**

```
sudo apt-get -y install git
git clone https://github.com/A2-Dev/APPira1n.git
cd APPira1n
chmod +x APPira1n uninstall update
sudo ./APPira1n
```
**Update chechra1n**
```
cd APPira1n
chmod +x update
sudo ./update
```
**Uninstall**
```
cd APPira1n
chmod +x uninstall
sudo ./uninstall
```

# Rasbian-Auto-Update-Bash-Script
# Expanding on automation of system software installs and updates
# Prince Thai 
# 2/17/2018
#
#!/bin/bash
# This script is inteded to help with the inital system configuration
# in a Raspbian environment. Do Not alter the orginal file in any way.
# Be sure to make a copy of this file and modify the copied file.
#
# This portion of the script will install services that are needed 
# for the sensor set-up. 
#
# ********Important********** You must be the root user or
# part of sudoers to run this script!
#
echo !!!!!!!!!!!!!!!!!!Banner!!!!!!!!!!!!!!!!!!!
echo !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
echo !!Be sure to varify that all packages are!!
echo !!!Installed and up-to-date.!!!!!!!!!!!!!!!
echo !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!! 
apt-get install tcpdump
apt-get install netcat
apt-get install finger
apt-get install nmap
apt-get install update
install update
#
(Do not use this portion of the script)
# This portion of the scrip will initiate a network scan
# nmap -O localhost
# This portion of the script will stop said services
service ssh stop
service tftp stop
service ftp stop
service smtp stop
(Displaying network protocols and ports)
# This portion of thescript will initiate netstat
netstat -vatun 


# addroute

This script is used to add route into Linux Server route table!

Usage: addroute -ip IP/NETMASK -gw GATEWAY -if INTERFACE [-h HELP] 

 -ip  IP/NETMASK          Destination IP with netmask, host should be with netmask 32
 
 -gw  GATEWAY             Gateway of Destination IP
 
 -if  INTERFACE           Interface for routing
 
 -h   HELP                Show the help

Example:

 --------------------------------------------------------------

 Add a route:
 user@host > addroute -ip 1.1.1.1/24 -gw 2.2.2.2 -if eth0

 --------------------------------------------------------------

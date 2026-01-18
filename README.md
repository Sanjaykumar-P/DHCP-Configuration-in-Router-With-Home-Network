# DHCP-Configuration-in-Router-With-Home-Network
Created a LAN Network with Router DHCP Configuration and Printer for Home Network

1 Router
1 Switch
4 Laptop
4 PC
Used Copper Straight cable

I have connected devices using the ethernet cable after that i have configured the private ip address in the LAN network after that I have confiugured the DHCP Server configuration in the Router itself

ip dhcp pool dhcppoolSanjay ------> This is the name for my DHCP Server
network 192.168.0.0 255.255.255.0
default-router 192.168.0.1
dns-server 8.8.8.8
exit
ip dhcp excluded-address 192.168.0.1 192.168.0.10
write


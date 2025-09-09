This is a Home Wireless Network

The devices used are :
Wireless Router
2 PCs
1 Laptop
Cable Splitter
1 TV

The ISP is a cable provider, providing cable TV connection and Internet.

How it works:
ISP (cable provider) provides both cable TV channels connection and Internet access. Both signals travel via same coaxial cable to the cable splitter. Cable splitter splits the signal into two, one for TV and another to cable modem.
Cable Modem filters out internet signals from cable tv signal. Demodulates the analog signal into digital signal for use by the PCs and laptop. It is connected to the home wireless router with a copper straight cable. It also has FastEthernet standard connection to both PCs.
U must setup the IP address using one of the PCs. The IP address is automatically set using DHCP (Dynamic Host Configuration Protocol) and the standard 192.168.0.1 is assigned by the DHCP server of the ISP to your router (default gateway). 
Then the PC through which you access the IP settings gets an IP as well. Along with it, default subnet mask and DNS server get assigned as well. 
Now setup the router configuration by entering the default gateway IP into the web browser. This brings up the config window. Setup the number of users allowed, router password, wireless SSID and SSID password in the various tabs.
Follow the same for the other PC as well, just no need to setup the router config as it is already done. 

Verifying connection:
Click on the TV and under 'status', turn ON the TV. You will see a static image. This proves that the Cable splitter and TV are properly connected
To test wireless setup, click on Laptop. Go to Desktop > PC wireless > Connect > search for the SSID you setup > enter SSID password
Go to Link Information tab to see a successfully connected message. If it is not, check your previous steps.
Go to IP settings and switch from static to DHCP. This allows the router to now "name" your laptop by assigning it an IP and formally including it in the network. Until now, it had connected to the network but could not be recognized as it didnt have an IP address.
Come back to Link information and you will see the updated IP address, DNS server, Subnet mask etc which were previously default values (0.0.0.0)
Go to web browser > in URL line > type : skillsforall.srv
You should see Welcome to Skills for All and an image load in a while. If it is done, then your wireless is setup well. 

Congratulations! You have correctly setup a simple home wireless network!

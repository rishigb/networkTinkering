#Kali

I have done the installation using Virtual Box.

There are 3 types of networks 
1. Bridged (your Kali becomes another ip for the router) 
2. Network Address Translation - The private network translates outgoing traffic from the virtual machine to the local network. On the local network, traffic from the virtual machine will appear to come from the host machine’s IP address
3. Host only - The host-only network limits the virtual machine to a local private network on the host. The virtual machine will be able to communicate with other virtual machines in the host-only network as well as the host machine itself, but it will not be able to send or receive any traffic with the local network or the Internet.

Setting -> Network -> Chose network in Virtual Box. VM Ware is paid, hence not using it.

After selecting bridged network, chose connected wired option to make sure the box is able to connect well.

Internet in my VBox is not working when I use the inbuilt wifi. I am yet to figure out why that is.

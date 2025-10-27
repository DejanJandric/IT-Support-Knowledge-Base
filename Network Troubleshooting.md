# **Network Troubleshooting using PING, TRACERT, IPCONFIG, NSLOOKUP COMMANDS**

**PING**

One of the commands you will be using a lot for network troubleshooting is the “PING” command. PING command allows you to send a signal to another device, and if that device is active, it will send a response back to the sender.

The ping command is a subset of ICMP (Internet Control Message Protocol) and it uses the echo request. So, when you ping a device, you send out an echo request, and if the device you pinged is active or online, you get an echo response.

Pinging can be used to check connectivity problems. When we ping the IP address, or a domain name, we send 4 packets (small, 32 bits of data) to the destination, and the destination responds back with the same 4 packets (Sent = 4, Received = 4, Lost = 0 => solid connection). You’ll be able to see how long the round-trip time is between your computer and the destination. You’ll see a “request timed out” message if packet loss is occurring, and you’ll see an error message if your computer can’t communicate with the remote host at all.

**TRACERT**

Another command, called TRACERT can let you see, the step-by-step route a packet takes to the destination you specify. It sends packets to a destination, asking each Internet router along the way to reply when it passes on the packet. This will show you the path packets take when you send them between your location and a destination.
So, if you send a packet to google.com, before the packet actually reaches the google.com servers, it will go through many different routers before it finally reaches google.com. Or you can use the term HOPS instead of routers. So, if it takes 10 routers to get to google.com, you can instead say, “it took 10 hops”.
This tool can help troubleshoot connection problems. For example, if you can’t communicate with a server, running traceroute may show you where the problem is occurring between your computer and the remote host. (You can see if there is problem with your provider’s routers if the request times out.)

**NSLOOKUP**

The nslookup command will look up the IP addresses associated with a domain name.

This command will fetch the DNS records for a given domain name or IP address. Remember, the IP addresses and domain names are stored in DNS Servers, so the nslookup command lets you query the DNS Records to gather information. (Your computer is constantly querying its DNS servers to translate domain names to IP addresses. This command just allows you to do it manually.)

**IPCONFIG**

Okay, so one of the VERY COMMON and very useful commands is the IPCONFIG command.
The IPCONFIG command displays all current TCP/IP network configuration values.
It gives you basic information to get your IP address, your router’s IP address, DNS server IP address, DHCP server address etc …

# **How to check if two PCs are connected in a network**

So you are trying to establish a network between two computers and you have no idea whether they are setup correctly. To check if the connection is able to send and receive data, windows have a inbuilt service through which we can check the connectivity by sending and receiving some bytes of data from your pc to target computer.
If you have wired them through switch or router, you should always first check the LED on Ethernet port. That LED should be blinking in most of the cases but if it’s not then you might have not connected them properly.
Follow these simple steps to check even if they are connected wirelessly:

1.  Get the IP of target machine.
2.  Open Command Prompt, by hitting (Windows+R) key and then typing cmd. Windows key is placed besides ALT key or you can go to Start > All Programs > Accessories > Command Prompt.

![alt text](https://softnuke.com/wp-content/uploads/2013/12/no-connection.jpg)

3.  Once the Command prompt is open, type “ping <ip address of target machine>”. For example

![alt text](https://softnuke.com/wp-content/uploads/2013/12/connected.jpg)

It will start sending some packets to the machine, if the response is received it means your connection is working fine. But if request timed out then there might be some problem.

Both computers should be in the same workgroup name.
Both computers should have a static IP address and subnet entered in. Gateway should not matter at this point.

PC1:
Workgroup: Workgroup
IP: 192.168.1.100
Subnet: 255.255.255.0

PC2:
Workgroup: Workgroup
IP: 192.168.1.101
Subnet: 255.255.255.0

Go to Start - Run - type CMD and click ok. This brings up a command line prompt (black screen)
You want to "ping" the other computer. From computer one type:
ping 192.168.1.101

From Computer 2 to computer 1:
ping 192.168.1.100

It should come back and reply.

# **USEFUL CMD COMMANDS**

<span style="color:red">ping host</span> (Ping determines if a device or server is reachable and analyzes network responsiveness by delivering tiny data packets and measuring the round-trip time, making it a helpful tool for network troubleshooting and diagnosing connectivity issues.)

<span style="color:red">tracert host</span> (This detailed path analysis helps identify network bottlenecks, latency problems, and potential failure points, making Tracert valuable for troubleshooting network issues and detecting anomalies in network paths.)

<span style="color:red">pathping host</span> (Similar to Tracert, provides extensive information about the network path but with a longer execution time.)

<span style="color:red">Ipconfig</span> (This command is valuable for diagnosing network issues, checking network settings, and quickly viewing key network information.)

<span style="color:red">Getmac</span> (You can retrieve the MAC address of your network device using the Getmac command.​ Network administrators use MAC addresses to control access, choosing which devices are permitted or denied access to the network based on their unique identifiers.)

<span style="color:red">Nslookup host</span> (You can acquire information such as the IP address associated with a domain name or the domain name associated with an IP address by using the Nslookup command. It is a useful tool for rapidly and efficiently diagnosing DNS-related issues, checking DNS configurations, and collecting DNS information.)

<span style="color:red">Netstat</span> (The Netstat command provides information on active TCP connections, listening ports, Ethernet statistics, IP routing tables, and IPv4/IPv6 statistics.)

<span style="color:red">netsh /?</span> (Users can use it to change network interfaces, set network protocols, monitor network statistics, and execute a variety of other network-related tasks. Netsh is especially beneficial for network administrators and sophisticated users who require fine-grained control over network configurations and settings.)

<span style="color:red">Hostname</span> (This is the name by which your computer is identified to other devices and servers on your local network. This name can also be found via the GUI's System information page, however, this command is faster.)

<span style="color:red">arp -a</span> (he Arp command can be used to diagnose network connectivity difficulties, validate MAC address associations, and manage ARP cache entries to guarantee correct network communication between devices.)

<span style="color:red">Systeminfo</span> (This command reveals extensive details such as the Windows 10 version, hostname, Product ID, CPU type and count, RAM configuration, network card information, and installed hotfixes. The output is quite extensive, encompassing crucial system specifics.)

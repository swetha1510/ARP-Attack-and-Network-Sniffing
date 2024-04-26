# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot 2024-04-26 221004](https://github.com/swetha1510/ARP-Attack-and-Network-Sniffing/assets/120623583/95aeac07-65d7-4526-b257-e9e4dea9f62e)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![eh exp 22](https://github.com/swetha1510/ARP-Attack-and-Network-Sniffing/assets/120623583/c1f8eba6-27c5-419f-a11a-63362d55960d)

 dsniff:



In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![eh exp 23](https://github.com/swetha1510/ARP-Attack-and-Network-Sniffing/assets/120623583/f7904ce2-7ece-4d44-90d4-fbf02557626a)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![eh exp 24](https://github.com/swetha1510/ARP-Attack-and-Network-Sniffing/assets/120623583/b7857c25-e220-4747-8351-548000d0a3aa)

Invoke the wireshark and examine the various menus  and controls of the tool:

![eh exp 25](https://github.com/swetha1510/ARP-Attack-and-Network-Sniffing/assets/120623583/92157c12-b061-4e02-be4e-b45c8587701a)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

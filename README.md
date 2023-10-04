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
![u1](https://github.com/Sharmilasha/ARP-Attack-and-Network-Sniffing/assets/94506182/6bc0bf0d-6ed8-4e8e-92b5-74e081949551)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![u2](https://github.com/Sharmilasha/ARP-Attack-and-Network-Sniffing/assets/94506182/c5ddda47-be13-49f3-93d6-a195a05ad7dc)

dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![u3](https://github.com/Sharmilasha/ARP-Attack-and-Network-Sniffing/assets/94506182/d1ea911b-9b8a-46d3-bb2f-1e75d77bb95e)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![u4](https://github.com/Sharmilasha/ARP-Attack-and-Network-Sniffing/assets/94506182/331ffec4-faf1-4abb-b6fa-7b328a8c4950)

Invoke the wireshark and examine the various menus  and controls of the tool:

![u5](https://github.com/Sharmilasha/ARP-Attack-and-Network-Sniffing/assets/94506182/b170127a-b2d8-4ced-8e13-8452f6148df8)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

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
![image](https://github.com/MrSanthosh-dev/ARP-Attack-and-Network-Sniffing/assets/117916573/a21f692b-efe1-43f8-8a71-6bcf1579acf1)


From kali linux issue the command : sudo arpspoof -i eth0 -t 
## OUTPUT:

![image](https://github.com/MrSanthosh-dev/ARP-Attack-and-Network-Sniffing/assets/117916573/fbd4d6af-0217-4b1a-b5ea-426811a61e1e)

 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/MrSanthosh-dev/ARP-Attack-and-Network-Sniffing/assets/117916573/8215314f-6e7c-4174-8847-61346b964aa7)

 In Kali issue the following commands:
 sudo dsnifff
## OUTPUT:

![image](https://github.com/MrSanthosh-dev/ARP-Attack-and-Network-Sniffing/assets/117916573/41a2c226-a014-426f-8bef-92982776f00e)
Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/MrSanthosh-dev/ARP-Attack-and-Network-Sniffing/assets/117916573/7e202808-5599-4005-b892-586686dc354e)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

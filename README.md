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

![Screenshot 2025-05-10 100026](https://github.com/user-attachments/assets/b984f9cd-7900-41fc-bcce-8299bb98a745)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-05-10 100034](https://github.com/user-attachments/assets/90dd031b-84b9-4caa-a6db-c7d8b639f20c)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2025-05-10 100039](https://github.com/user-attachments/assets/501495e7-db5a-4fa5-8e35-6db27901274c)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![Screenshot 2025-05-10 100046](https://github.com/user-attachments/assets/e272420d-7b76-42fa-bf93-5ac4cfd08e8f)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-05-10 100052](https://github.com/user-attachments/assets/459b863d-5a7a-45f1-b9fb-74846052e50a)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

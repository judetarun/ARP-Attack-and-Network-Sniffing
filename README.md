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
<img width="1143" height="628" alt="image" src="https://github.com/user-attachments/assets/2fa0fa82-c6e8-40bc-bbc5-61d778c7b804" />



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="689" height="270" alt="image" src="https://github.com/user-attachments/assets/a2c52ac8-fb2c-4f31-93a7-8486b2760e3f" />

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

<img width="532" height="241" alt="image" src="https://github.com/user-attachments/assets/1ce968e0-7b7d-4ecb-8ff8-9b375b3af761" />

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="766" height="125" alt="image" src="https://github.com/user-attachments/assets/60c6a823-578a-4e1a-86f0-0df7bb4e48d5" />



Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="1914" height="807" alt="image" src="https://github.com/user-attachments/assets/62d70165-cff1-4a1c-88d6-cff8948a54e7" />


ettercap
![alt text](07_ettercap.png)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

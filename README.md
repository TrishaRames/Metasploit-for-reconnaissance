# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:


## OUTPUT:
Find out the ip address of the attackers system

![image](https://github.com/user-attachments/assets/b61492ff-567e-4063-a5c3-0845fbefdf22)
Invoke msfconsole
![image](https://github.com/user-attachments/assets/b4110cff-d0b1-4da5-92c5-d5c4c8b24053)
Type help or a question mark "?" to see the list of all available commands you can use inside msfconsole.
![image](https://github.com/user-attachments/assets/7dfac114-df86-46cb-a71a-cfcf2f466c70)
Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000). msf > nmap -sT 192.168.228.247/24 -p1-1000
![image](https://github.com/user-attachments/assets/f022e6cc-3e64-41b4-ba53-0d84ddc79e8d)

use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.

scan the targets with the command db_nmap as follows. msf > db_nmap 192.168.228.247/24

![image](https://github.com/user-attachments/assets/42be34df-e8a2-4132-b553-0be91821d045)
Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to Metasploit's auxiliary modules and list all the scanner modules. cd /usr/share /metasploit-framework/modules/auxiliary kali > ls -l

![image](https://github.com/user-attachments/assets/326a3f6b-082b-4415-8c3a-840488445041)
Search is a powerful command in Metasploit that you can use to find what you want to locate. msf >search name:Microsoft type:exploit
![image](https://github.com/user-attachments/assets/49ddc160-8566-448e-bcae-f6546ada0f21)
The info command provides information regarding a module or platform

![image](https://github.com/user-attachments/assets/f49006dc-0ede-4ddb-8ee0-16623ad1db83)

## MYSQL ENUMERATION Find the IP address of the Metasploitable machine first. Then, use the db_nmap command in msfconsole with Nmap flags to scan the MySQL database at 3306 port. db_nmap -sV -sC -p 3306 <metasploitable_ip_address>


![image](https://github.com/user-attachments/assets/40a824be-858e-4616-9c22-c82cf248122a)

![image](https://github.com/user-attachments/assets/da8d8efb-da80-4ca1-8335-a7dc1157c3e4)

![image](https://github.com/user-attachments/assets/2796b318-4b93-4dd3-8761-b48728f3261c)

![image](https://github.com/user-attachments/assets/f718f0cc-5892-4351-bfa6-d12e52ffe3a0)




## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

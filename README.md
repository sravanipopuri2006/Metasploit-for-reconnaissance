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
### step4:
use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.

scan the targets with the command db_nmap as follows.
msf > db_nmap 192.168.181.0/24

## EXECUTION STEPS AND ITS OUTPUT:

Find out the ip address of the attackers system
## OUTPUT:
Checking the Port using ifconfig:
<img width="570" height="403" alt="image" src="https://github.com/user-attachments/assets/db91b99e-f73a-4e50-a02f-476a5834f4d4" />

## OUTPUT:
Get into The MsfConsole :
<img width="627" height="479" alt="image" src="https://github.com/user-attachments/assets/3b7d6a21-d5c0-4499-99f7-311ef035fd97" />
<br/>




## OUTPUT:
Using Help Command :
<img width="743" height="592" alt="image" src="https://github.com/user-attachments/assets/3f917ef1-29c5-4307-8352-571556fa9c4c" />
<br/>



## OUTPUT:
<img width="500" height="139" alt="image" src="https://github.com/user-attachments/assets/9bae07e7-74b1-4a51-b7a7-cb9991c51f94" />
<br/>
Port Scanning: Following command is executed for scanning the systems on our local area network with a TCP scan (-sT) looking for open ports between 1 and 1000 (-p1-1000).




Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to Metasploit's auxiliary modules and list all the scanner modules.
cd /usr/share /metasploit-framework/modules/auxiliary
kali > ls -l
## OUTPUT:



Search is a powerful command in Metasploit that you can use to find what you want to locate. 
msf >search name:Microsoft type:exploit
## OUTPUT:
# DB_Nmap :
<img width="594" height="582" alt="image" src="https://github.com/user-attachments/assets/aef9e221-a895-4a18-8c1b-f0afc7482402" />
<br/>
use the db-nmap command to scan and save the results into Metasploit's postgresql attached database. In that way, you can use those results in the exploitation stage later.


### Viewing the metasploit framework on root:
<img width="676" height="371" alt="image" src="https://github.com/user-attachments/assets/9ed56f9d-172d-4d3e-814a-0572ea193dc4" />
<br/>
Metasploit has a multitude of scanning modules built in. If we open another terminal, we can navigate to Metasploit's auxiliary modules and list all the scanner modules. cd /usr/share /metasploit-framework/modules/auxiliary kali > ls -l










## RESULT:
The Metasploit framework for reconnaissance is  examined successfully

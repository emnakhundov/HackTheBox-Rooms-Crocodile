# HackTheBox-Rooms-Crocodile

<img width="1568" height="171" alt="Crocodile_6png" src="https://github.com/user-attachments/assets/253833f6-c268-43ef-9ed2-614a618e687e" />

Target IP :   10.129.55.69

Task_1 : What Nmap scanning switch employs the use of default scripts during a scan?
----------------------------------------------
nmap -sV -sC -T4 -A  10.129.55.69 -o nmap.txt
----------------------------------------------
<img width="808" height="695" alt="Crocodile_1" src="https://github.com/user-attachments/assets/c7f85638-bb9d-4242-a913-324d3b29bed8" />

Answer_1 : -sC

Task_2 : What service version is found to be running on port 21?

Answer_2 :  vsftpd 3.0.3

Task_3 : What FTP code is returned to us for the "Anonymous FTP login allowed" message?

Answer_3 : 230

<img width="1657" height="667" alt="Crocodile_2" src="https://github.com/user-attachments/assets/6cb3133f-1017-464c-bff2-3b1890146f3a" />

Task_4 : After connecting to the FTP server using the ftp client, what username do we provide when prompted to log in anonymously?

Answer_4 : anonymous

Task_5 : After connecting to the FTP server anonymously, what command can we use to download the files we find on the FTP server?

Answer_5 : get

Task_6 : What is one of the higher-privilege sounding usernames in 'allowed.userlist' that we download from the FTP server?

Answer_6 : admin

Task_7 : What version of Apache HTTP Server is running on the target host?

Answer_7 : Apache httpd 2.4.41

Task_8 : What switch can we use with Gobuster to specify we are looking for specific filetypes?

<img width="817" height="615" alt="Crocodile_3" src="https://github.com/user-attachments/assets/9bdc01f0-faa5-420f-b3bf-01169363d223" />

Answer_8 : -x

Task_9 : Which PHP file can we identify with directory brute force that will provide the opportunity to authenticate to the web service?

<img width="1670" height="495" alt="Crocodile_4" src="https://github.com/user-attachments/assets/9e3d3324-caa6-4e4e-822f-76539a9bdd80" />

Answer_9 : login.php

<img width="1670" height="875" alt="Crocodile_5" src="https://github.com/user-attachments/assets/41c8cd22-e7a4-4804-a6d4-e3ee763133c4" />


Submit_flag : c7110277ac44d78b6a9fff2232434d16

Thank you!






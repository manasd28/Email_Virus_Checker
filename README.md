Email Virus Checker 
====================
(Email Virus Checker) It uses IMAP (Internet Mail Access Protocol ) and Python v3 . Real Time Monitoring of new Mail and gets triggered to Extract all the links and attachments and Scans all the links and attachments and give you a status of Mail . If it found that mail contain any Malicious links or Attachments then ask for permission to delete and then delete automatically.


[IMAP(Internet Mail Access Protocol)](https://en.wikipedia.org/wiki/Internet_Message_Access_Protocol)
=====================================

<b>IMAP</b> : Internet Message Access Protocol  is a standard email protocol that stores email messages on a mail server, but allows the end user to view and manipulate the messages as though they were stored locally on the end user's computing device(s). This allows users to organize messages into folders, have multiple client applications know which messages have been read, flag messages for urgency or follow-up and save draft messages on the server.

[VirusTotal](https://en.wikipedia.org/wiki/VirusTotal)
===================================

<b>VirusTotal</b> : VirusTotal inspects items with over 70 antivirus scanners and URL/domain blacklisting services. For more information visit https://support.virustotal.com/hc/en-us/articles/115002126889-How-it-works

Generation of API_KEY 
========================
```
1. Go To Virustotal Website . site : https://www.virustotal.com/gui/home/upload
2. Signup on VirusTotal 
3. You get your free public API_KEY.
```
 Ussage :
====================
```
1. Install Python3
2. Install pip
3. Install all the requirements using : pip install -r requirements.txt  
4. Change Permission of IMAP_Connection.py : chmod a+x IMAP_Connection.py
5. Change Gmail permission to allow less secure apps : ON
6. run : IMAP_Connection [ gmail.id ] [ gmail.password ] [ API_KEY ]
```

<b><i>Now Your Server Start running for new Mails !!! </b></i>



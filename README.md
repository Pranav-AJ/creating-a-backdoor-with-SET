# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 

The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/ac5a1971-c986-41a7-beb5-3a5a6b0e242f)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/4b0331a9-d69e-4b4a-aa93-bbf3cbdea640)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/e286a7e8-ef48-4af3-beef-a1d079ac9ff4)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/bcd61064-7737-4924-ba46-022e53d58e5c)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/18ef03ef-60d3-4558-b1e8-324f77e74cd4)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/77ea47e6-c32b-4d49-bd81-245b56c6a3c9)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/ee090a24-3501-4d39-b8f6-65872e58919c)

SET logs the information regarding the Google credentials:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/103d4669-d038-487d-9aaa-21485bee34d9)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/118904526/a54f4349-612f-4b84-a07a-2330c054a96d)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

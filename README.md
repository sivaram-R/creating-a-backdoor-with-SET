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

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/4a75acf8-bb87-4a6d-98dc-3b791d94ad59)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/b5ed6cb9-84a9-46bd-9dc8-772dda3c9c4e)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/858193aa-a5b9-49b2-bf64-29c21ab4a7d9)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/a8a0f2de-c4d6-41af-b1d8-e24ce955bbbf)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/10a75810-4378-41ca-8ca0-da158eec1b8b)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/9e47900b-3757-4fc2-b28e-e15a1f869e71)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/7cbd8afc-5e94-4071-a50c-5e4cf95598c7)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/e14d0605-f905-43c3-a0d7-d4747a1dbdbd)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![VirtualBox_Windows 7_16_04_2024_08_56_25](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/ddfca21d-cefc-4324-9b8c-c431c483bdd6)

SET logs the information regarding the Google credentials:

![image](https://github.com/Darkwebnew/creating-a-backdoor-with-SET/assets/143114486/11d7e1b1-2a4b-4291-b910-c20ac204c585)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

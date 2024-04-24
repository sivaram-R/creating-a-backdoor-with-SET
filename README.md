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

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/39c6c9f2-48f2-42a5-9159-2c6f77855d4d)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/99d8818b-cd06-4512-861d-5fb08293a458)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/71d3c43f-6ee0-49eb-8dc6-c31a68f3339f)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/09fa6b53-30af-483f-bb99-1a16e7c668a0)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/46227412-7931-4026-898b-fed00dd84b04)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/9aff5cd8-c7fa-4d6d-9bda-325f542185a9)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/631fd023-6a7f-4ff9-a04d-fb10ebe99cbd)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/59f4ad91-6e6a-49d4-abca-a6340fd53612)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/86d78089-f63f-49c0-a441-c3506eb715fe)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/a02d7cdb-7780-4704-8511-430a3507be6c)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/AmirthaRoopaS/creating-a-backdoor-with-SET/assets/143496311/f7891bb0-a249-4549-bf91-8f2522015e05)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

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

![exp7_1](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/c0b67075-0417-473e-b2e2-eb2b6709a4da)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


It displays the following menu and select 2 for Website Attack Vectors:

![exp7_2](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/21b35f21-fdbd-43ef-824f-6b8761d1c905)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![exp7_3](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/ef2f617e-a97f-42b4-b7bd-89131408e701)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![exp7_4](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/4a73b053-30fe-4e9f-afd6-4f2504690f03)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![exp7_5](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/e829a41f-7566-4efa-8246-3e6dc9ef36d5)


It shows the following screen in which the option Google can be selected:


![exp7_6](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/b8b51a6e-0816-4483-b0f0-43d8aa59efa7)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![exp7_7](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/e2a5bbc8-ae24-4cd1-9767-dd6e7b041549)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password


![exp7_acc](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/03f20e03-e907-4864-82a7-f35532e9e28b)


SET logs the information regarding the Google credentials:


![exp7_res](https://github.com/Skanthasishanth/creating-a-backdoor-with-SET/assets/118298456/455d247c-857c-4b7b-8b81-2bd688cd1333)


SET logs the information in the xml file under /root/.set directory:


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

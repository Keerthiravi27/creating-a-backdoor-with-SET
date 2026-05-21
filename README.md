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
## OUTPUT
<img width="1920" height="1057" alt="image" src="https://github.com/user-attachments/assets/03d9adf6-dadc-44bc-bddd-594137cfefe0" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="323" alt="image" src="https://github.com/user-attachments/assets/01ab4264-e461-4a13-aad7-25b4c71aa3e5" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="547" height="211" alt="image" src="https://github.com/user-attachments/assets/dd3a38ee-b58d-4f8b-bf2a-530a15bde52e" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1920" height="307" alt="image" src="https://github.com/user-attachments/assets/32d7b1cc-5ffe-49fa-b674-8989d44434dc" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1920" height="635" alt="image" src="https://github.com/user-attachments/assets/cc5a959a-3f62-4fc1-bf00-064d0de74d72" />



It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1920" height="508" alt="image" src="https://github.com/user-attachments/assets/54fc4b9a-5c96-4d53-b1de-49b1188c1949" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="920" height="1045" alt="image" src="https://github.com/user-attachments/assets/d05bab84-b3dc-4124-907f-fdc06c20320d" />


SET logs the information regarding the Google credentials:
## OUTPUT



<img width="1920" height="1057" alt="image" src="https://github.com/user-attachments/assets/6f46703c-6b81-4785-a772-2f18712674c0" />













## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

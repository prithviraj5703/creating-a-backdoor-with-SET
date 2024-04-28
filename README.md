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

![325464250-ef7b25b6-a477-4153-8066-5df532c07688](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/b5e5dd38-7821-4e2e-952d-d94232f5ac47)

 It displays the following menu and select 2 for Website Attack Vectors: 

![325464403-cf29526b-3edc-4f4d-afa4-27926c2f1f24](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/4bc3a581-acca-4ced-b802-efc7d4f98bf6)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: 

![325464450-45904ce1-8f75-46a2-9591-26748dca14ca](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/779338a4-adc4-4485-a41d-ec5834c1dc17)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![325464498-017d7cc5-e8bf-4bbf-a989-a98446ed662a](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/3d279bf1-fd91-4ef6-936a-3832ecb329c0)

It shows the following screen in which the ip address of the attacker need to be given which is the default value: 

![325464540-12696ddd-643e-4d84-ad46-51ca12acc8b7](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/322f1933-9068-429a-825a-4c241e7ce066)

It shows the following screen in which the option Google can be selected:

![325464570-847305a1-96a5-40c0-82b7-9618558faeee](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/edd80f39-e775-4e0d-949b-a9b7bd4399c0)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![325464610-e03cbefa-1ed1-4158-86e6-4ac20056236a](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/d9ffd355-34d9-4c91-8ff7-1230535b0702)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![325464661-3d4153f4-67e6-408f-898f-b7f636c970cc](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/49b632d9-a0aa-4336-80d0-edfa56e1943e)

SET logs the information regarding the Google credentials: 

![325464702-0d07b841-bc07-40cd-9bd7-f79aed210989](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/6814d5ac-35fa-4716-b3ca-1e164a27aa30)

SET logs the information in the xml file under /root/.set directory: 

![325464750-a9160ebe-7b63-45f6-a059-f59375153548](https://github.com/prithviraj5703/creating-a-backdoor-with-SET/assets/121418418/341bbfcc-d1cf-44bb-b733-5e7a242e410d)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

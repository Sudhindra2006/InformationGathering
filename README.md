# Name: Sudhindra.R
# Reg No: 212224240164
# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="942" height="945" alt="image" src="https://github.com/user-attachments/assets/a246c56e-bbf6-447d-b980-3a18adb503a3" />


### Finding Hosting Company :
<img width="1757" height="774" alt="image" src="https://github.com/user-attachments/assets/51407b08-4693-4cf9-83ef-87199767d606" />

### History of the website :
<img width="1444" height="908" alt="image" src="https://github.com/user-attachments/assets/b03cfe0d-0f1b-430b-b755-887755b64499" />

### ping command :
<img width="955" height="1045" alt="ping exp-2" src="https://github.com/user-attachments/assets/6972f8d6-b85d-44a1-998b-5794e705051c" />

### whois :
<img width="1920" height="1057" alt="whois exp-2" src="https://github.com/user-attachments/assets/19a17145-ad3e-4642-9ec7-7cee926bd640" />

### netcat :
<img width="1920" height="1057" alt="netcat" src="https://github.com/user-attachments/assets/30b60179-7a69-4b63-8bab-e45099c9f1a4" />

### nmap :
<img width="955" height="1045" alt="nmap" src="https://github.com/user-attachments/assets/42d82586-b37b-4ce9-9df3-4d514da46050" />


### whatweb :
<img width="955" height="1045" alt="whatwebb" src="https://github.com/user-attachments/assets/b3989b75-b047-44ee-8efe-b94cba59b8d5" />

### httprint :
<img width="630" height="208" alt="image" src="https://github.com/user-attachments/assets/d2ee2446-08c5-41f1-957f-3b1b181277b1" />


### TCP traceroute :
<img width="955" height="1045" alt="tcp traceroute" src="https://github.com/user-attachments/assets/47571f9e-4b48-4458-b165-6ccd177e2d30" />

### UDP traceroute :
<img width="955" height="1045" alt="udp" src="https://github.com/user-attachments/assets/57bd46c6-e5c3-4eab-ba84-2475e61d9e81" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully

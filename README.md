# InformationGathering
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

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1533" height="825" alt="image" src="https://github.com/user-attachments/assets/20de6213-c548-46b8-8126-8e3c368c2903" />



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output
<img width="974" height="654" alt="image" src="https://github.com/user-attachments/assets/8f01248c-ef87-4702-bef8-5c4fb1833522" />


## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1536" height="803" alt="image" src="https://github.com/user-attachments/assets/3a44c94a-8ab5-4536-8ff8-8632ddec8426" />



## History of the website:
## output
https://web.archive.org/
<img width="1535" height="817" alt="image" src="https://github.com/user-attachments/assets/497b7397-ecdc-4da1-bf38-47edbf4050ae" />


# Webserver Fingerprinting:
<img width="972" height="647" alt="image" src="https://github.com/user-attachments/assets/673a1ff3-c294-4dc2-a115-bce6318fb937" />

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="1034" height="697" alt="image" src="https://github.com/user-attachments/assets/79fc53d2-1397-4b15-ab54-bd359b899126" />



## nmap:
##output

<img width="1022" height="699" alt="image" src="https://github.com/user-attachments/assets/ee2395e0-8d71-4b30-8875-eb053b16cecb" />


## Whatweb
### output
<img width="1024" height="696" alt="image" src="https://github.com/user-attachments/assets/559f77a1-270e-4bb4-9d17-64b1f375d1f4" />
<img width="1332" height="713" alt="image" src="https://github.com/user-attachments/assets/8fb48928-698f-428e-966f-0aaf64d35b68" />
<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/53ca20ed-29f4-4a9a-a5a7-9c30a7210e47" />
<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/2a34a3e4-8ee6-4974-b029-3499efb94e90" />
<img width="1529" height="860" alt="image" src="https://github.com/user-attachments/assets/321328eb-6c93-41f9-a551-60a08cbc6239" />


## httprint
### output
<img width="1017" height="690" alt="image" src="https://github.com/user-attachments/assets/22a29ffc-fb19-4e7a-8dc1-8280122f0e13" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="1014" height="688" alt="image" src="https://github.com/user-attachments/assets/0e15737a-bbbe-4a4a-b8a8-c1becf3065ea" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/d4e0ac18-dad7-4d9a-8d23-1b314c7ee627" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output
<img width="1536" height="864" alt="image" src="https://github.com/user-attachments/assets/34057081-7273-4f2a-89bd-0202e7fbe3ef" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully

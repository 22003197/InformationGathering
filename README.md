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


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/16fdd476-2f12-48c1-9eeb-3d10d9fb885f)
## Finding IP Address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.


  ping saveetha.ac.in


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/865d07e0-2dd2-462e-a6e8-cb3d16c4c156)
## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/8f5e127c-0eba-4469-95e9-b49d9ae5fd20)
##History of the website:
## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/bbf91dd2-078b-4578-b788-e7658c5a5157)
## Web Server Fingerprinting:
## Netcat:


 nc 172.17.52.118 80


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/a5a236e6-cd83-4e83-9fec-f14c4f76f905)
## Nmap:


nmap -p 21 -sV --script=banner ftp.vim.org


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/c1f4bb18-c959-406e-9586-4be3589bfea8)
## Whatweb:


 whatweb infosys.com


 whatweb zoho.com


 whatweb -v -a 3 172.17.52.201


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/360fde4c-e94f-481d-9645-7be8c4578c96)
## httprint:


 httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/25ae16e3-668d-429c-9f98-b1ba0988b936)
## Tracing the location:
## TCP Traceroute:


 sudo traceroute -T www.saveetha.ac.in


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/33e0b061-8385-4096-9a3f-5b2b12a5dc31)
## UDP Traceroute:

 
 sudo traceroute -U www.saveetha.ac.in


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/dd9555c7-30ad-4609-88bf-52bba8f7305c)
## ICMP Traceroute:

 
 sudo traceroute  www.saveetha.ac.in


## OUTPUT:
![image](https://github.com/22003197/InformationGathering/assets/124332243/c506a4ad-9d83-4d3d-b734-2e51be1a44d2)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully

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
## Finding Ip:
ping saveetha.ac.in

## OUTPUT:
![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/461d65c5-2c70-456e-97a8-e6d5ebdcd800)

## Finding the host of the company:
![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/15860d66-ecc0-403c-8a86-130378b6b431)

## History of website:
## OUTPUT:
![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/227f9548-fee4-4ea8-ac9d-b4576da042c7)

## Webserver Fingerprint:

![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/b2f34b8b-89b7-4f88-b75a-58cdb0f26d07)


## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org

## OUTPUT
![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/034a5348-325d-419f-9d17-7e74feaab22b)
## Whatweb:
whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201

## OUTPUT:

![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/e25b6f15-c50a-485c-9ccc-941c7d16410f)


## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

## Output:

![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/1f5fb6a5-4369-45f5-81d6-6d1bc63754e3)
## TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in

## OUTPUT:
![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/5402bc76-a825-42c4-a5d9-712db0a5e6f0)

## UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in

## OUTPUT:

![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/30e0796f-8798-47e0-959b-d8f1a818c360)

## ICMP Traceroute:
sudo traceroute www.saveetha.ac.in
## OUTPUT:

![image](https://github.com/indrajasukumar/InformationGathering/assets/145115195/60f62670-97fe-408a-9044-86cdacf55ccd)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully

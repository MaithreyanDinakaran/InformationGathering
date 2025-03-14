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
![420578020-5cfb7004-0b91-45ea-8f18-8ce1fe9a5ea8](https://github.com/user-attachments/assets/cc061825-580a-4d3f-8157-e8992b6ba160)
## ip2Location
![420578023-a2b8b78c-1bf1-471e-8b29-662ba49deb52](https://github.com/user-attachments/assets/f7da323c-9951-4deb-a0f1-58595d5c74e3)
## History of the website:
![420578028-7bfea196-dc91-44bc-8409-3fc1f5d05fcb](https://github.com/user-attachments/assets/7da49e60-d8a7-4eec-bf63-7c95fe31442a)
## Webserver Fingerprinting:
# Netcat:
```
sudo nc ticfiber.com 80
GET / HTTP/1.1
Host: ticfiber.com
```
## Output:
![420578387-7014ac31-8acd-4881-a40b-3cb3bd23fb74](https://github.com/user-attachments/assets/6229fa8d-be54-4acf-9d81-2245fc9342bb)
# Nmap:
## Output:
![420578375-79fed06b-63cd-4dcd-bb44-21e7eb037b00](https://github.com/user-attachments/assets/65e9fa2e-4aac-4ee4-9596-cec03131e17e)
![420578288-60d40b0f-cf25-4b3c-a18b-94a869b68079](https://github.com/user-attachments/assets/b9429e65-e2f5-464c-bdaf-f6f75cbf6003)
# Whatweb:
## Output:
![420578363-dbe961bc-a2ed-4a7b-a3e9-0892f53d1b31](https://github.com/user-attachments/assets/eb5ed85d-58f3-46a6-8834-ac0565cae960)
## Tracing the Location:
```
TCP Traceroute:
sudo traceroute -T ticfiber.com
```
## Output:
![420578321-4a7e49d0-96af-4621-a73b-9a2444e1ede2](https://github.com/user-attachments/assets/d056dd7e-49ef-4a2c-a059-38dad31255f4)
# UDP Traceroute:
```
sudo traceroute -U ticfiber.com
```
## Output:
![420578298-07c36e9d-7803-4563-94b8-4957939983fc](https://github.com/user-attachments/assets/0442483e-5a2a-426f-91bf-cd2a8bc7c1be)
## ICMP Traceroute:
```
sudo traceroute ticfiber.com
```
## Output:
![420578287-ee2d0734-eaa4-4036-998b-7b1dfd7f66d8](https://github.com/user-attachments/assets/e5c16a39-66be-4dfd-9d2f-b922159c2a46)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully

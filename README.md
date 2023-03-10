# nmap
The Network Mapper, also known as “Nmap,” is a versatile, flexible, and famous tool used to manage and secure networks. It helps administrators to map their networks and security scans.

```bash
nmap -sn 192.168.1.0/24
```
this will tell you all the devices that are connected to your network.
> replace 192.168.1.0 with the IP address of your network
![image](https://user-images.githubusercontent.com/95766110/223596537-6ad53e5e-5615-4e6a-be7d-b25c0639e565.png)


```bash
sudo nmap 192.168.1.1-255
```
![image](https://user-images.githubusercontent.com/95766110/222903976-ef2785fb-44d5-4fc6-8a10-13596f64064f.png)

```bash
sudo nmap -sP 192.168.1.1-255
```
![image](https://user-images.githubusercontent.com/95766110/222903838-dffd40de-5e48-4014-9f2b-35b3109e12b4.png)

```bash
sudo nmap -O 192.168.2.1
```
![image](https://user-images.githubusercontent.com/95766110/222905560-adb7dd33-bd27-47fc-8370-abadb6648ae4.png)


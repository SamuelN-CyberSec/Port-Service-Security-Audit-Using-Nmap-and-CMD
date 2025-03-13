![Audit iditentifiying service](https://github.com/user-attachments/assets/97d72303-55c2-40f3-a2c1-c996143ad6d9)
<img width="960" alt="Audit nmap 2" src="https://github.com/user-attachments/assets/1d0f1ce9-092e-446f-a2f6-3b7e41df2cf0" />
![Audit nmap](https://github.com/user-attachments/assets/6d68aaa5-3c35-48ae-80c8-e5ab4f76516a)
# Port-Service-Security-Audit-Using-Nmap-and-CMD
Open ports are unnecessary service that pose security risk by exposing system to attacks this project Identifies used and unused port, how to Identify and  disable using CMD and Nmap
**Tool Used **
Nmap(Scanning Open Port)
Command Prompt (Managing,Configuration and blocking)
Windows Firewall (For blocking)

**Steps used in the Project**
Scaning Open Port Using Nmap (Running Command on CMD nmap -sS -P- "ADDRESS")
finding Service Runing on Open Port ( netstat -ano | find "PORT NUMBER")
Blocking port using Windows firewall (netsh advfirewall add rule name="Block PORTNUMBER"dir=in action=block protocol=TCP localport=PORTNUMBER)

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

# Windows-Firewall-Configuration-and-Testing
OBJECTIVE:
* To block and unblock Telnet port(23) to verify the working of firewall rules

STEPS:
* Opened Windows defender firewall:Advanced security
- create a new rule:
  Type: port
  Protocol: TCP
  Port: 23
  Action: Block the connection
  
TESTED THE SAME WITH NMAP AND VERIFYING IT 
#nmap -p 23 localhost

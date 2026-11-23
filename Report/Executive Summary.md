# Executive Summary

On Wednesday, 22 January 2025, a malware infection was identified following a 
malicious advertisement that redirected the user to a fake Google Authenticator page, which 
was used to deliver malware to the victim's system. Further investigation of the network traffic in 
Wireshark revealed suspicious communication between the infected internal host and several 
external IP addresses, indicating potential malicious network activity.
<br><br>
Analysis of the recovered PowerShell payload revealed that the malware repeatedly 
contacted an external HTTP Command and Control (C2) server at 5.252.153[.]241, appending 
the infected machine's drive serial number to the URL and attempting to download and execute 
additional code every five seconds. This behavior is consistent with C2 beaconing, allowing the 
attacker to maintain communication with the compromised system and potentially deliver further 
instructions or malicious payloads. 

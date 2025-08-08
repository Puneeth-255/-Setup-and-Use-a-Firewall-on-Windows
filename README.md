# -Setup-and-Use-a-Firewall-on-Windows
Setting up and blocking with Windows Firewall (Advanced Security): 
Access: Open "Windows Defender Firewall with Advanced Security" (search or wf.msc).
New Rule: Go to "Inbound Rules" or "Outbound Rules", click "New Rule". 
Configure: Choose "Port" rule type. 
Specify port(s) and protocol (e.g., 3389/TCP for RDP, 80,443/TCP for web).
Select "Block the connection".
Apply to desired network profiles (Domain, Private, Public).
Name the rule.
Test: Verify the block (e.g., try RDP or web browsing if blocked).
Manage: Right-click rules to Disable, Delete, or modify Properties

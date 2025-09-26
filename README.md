# firewall-testing-task-4
Cyber Security Internship Task 4 - Setup and use a Firewall on Windows : Configure and test firewall rules with screenshots and documentation.
# Task 4: Setup and Use a Firewall (Windows)
## Objective 
Configure and test basic firewall rules to allow or block traffic.
## Tools
- Windows Firewall  
## Steps (Windows Example)
1. Open Windows Firewall → Advanced Settings → Inbound Rules.  
2. Check existing rules.  
3. Create a new rule to block **Telnet (Port 23)**
4. Verify the rule in Inbound Rules list.  
5. Test the rule via Command Prompt: (cmd run as admin)
6. telnet localhost 23
7. Disable or delete the rule to restore the original state:
**Windows:**  
- Inbound Rules → Right-click **Block Telnet (Port 23)** → Select **Disable Rule** (grey) or **Delete** (remove from list)  

# Cyber Home Lab Microsoft Sentinel

## Objective

The Cyber Home Lab project SOC in Azure from scratch. Using a free Azure subscription, I created a Virtual Machine (VM), opening it to the internet as a honeypot, and forwarding logs to a central repository. I then integrate Microsoft Sentinel to analyze real-world attack data.

### Skills Learned

- Creating a Virtual Machine in the Azure Portal.
- Configuring Log Analytics Workspace.
- Forwarding logs and integrating with Sentinel.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Building an attack map to track real-time hacker activity.

### Tools Used

- Used Azure VM to create a Windows 11 machine.
- Used Microsoft Sentinel for log ingestion and analysis.
- Within Sentinel, I used Workbooks to create an attack map.

## Steps

Every screenshot should have some text explaining what the screenshot is about.

Here is the Windows 11 Virtual Machine.
<img width="1865" height="976" alt="Screenshot 2025-07-27 144127" src="https://github.com/user-attachments/assets/efdbb167-0f00-42ac-a10e-d5f962f0c470" />

Here is the Log Analytics workspace, which included the KQL to produce the AttackIP, Computer, TimeGenerated, Cities and Countries of the attacks.
<img width="1869" height="971" alt="Screenshot 2025-07-27 144227" src="https://github.com/user-attachments/assets/181480c3-2bac-4db5-b751-4d16413a09d6" />

Here is the Attack map that shows from around the world.
<img width="1864" height="970" alt="Screenshot 2025-07-27 144334" src="https://github.com/user-attachments/assets/ed6e740c-5451-44f8-820c-9194c19be0ec" />



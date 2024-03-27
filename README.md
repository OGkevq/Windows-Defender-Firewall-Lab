# Windows Defender & Firewall Lab

## Objective

This beginner-friendly lab aimed to teach students how to minimize common security risks by learning to add and update security defenses using Microsoft Defender. It also went over how to configure firewall rules with and without Advanced Security.

### Skills Learned

- Update Threat definitions
- How to run Microsoft Windows Defender Antivirus Quick Scan and view 
- Ability to configure Microsoft Windows Firewall rules
- Inbound rules vs Outbound rules

### Tools Used

- Microsoft Windows Defender

## Steps
This lab was set up on a cloud workspace through Coursera. 
1. Find Windows Defender (Start button-->Settings-->Update And Security-->Windows Security)
2. Update threat protection
   
   ![WindowsFirewall_Lab_UpdateDefenitions (1)](https://github.com/OGkevq/Windows-Defender-Firewall-Lab/assets/159976397/1e7f2db5-b7c5-42e8-b6a4-41d82da64b70)

   Ref1: Going to "Virus and Threat Protections" to Update definitions
4. Run a quick scan  
5. Perform a custom scan targeting the "Downloads" section to identify any threats.
 
   ![WindowsFirewall_Lab_custom scan1](https://github.com/OGkevq/Windows-Defender-Firewall-Lab/assets/159976397/f8ba8a90-b0fe-448c-ac42-9879c1e1af45)

   Ref2: Image of completing a custom scan in the downloads section *In this cloud environment 'Downloads' is empty so scan is quick.

6. Find Windows Security Firewall (Start button-->Settings-->Firewall & Network Protection)  
7. Go to Advanced Settings and Change the Inbound rule for Key Management Service from (Profile "All" Enabled "NO") to (Profile "Domain & Private" Enabled "Yes")
8. Domain "General" tab to Allow the connection and Domain "Advanced" tab to turn off "Public"
9. Duplicate the existing rule, modifying it to block connections for 'Public' networks. Then, activate the modified rule
10. 



Example below.

*Ref 1: Network Diagram*

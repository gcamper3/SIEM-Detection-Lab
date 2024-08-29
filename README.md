# SIEM-Detection-Lab

## Objective

The Detection Lab project aimed to establish a controlled environment within Microsoft Azure for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen my understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Microsoft Azure cloud services to run the environment 
- Security Information and Event Management system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
Step 1: Within Microsft Azure, I created a virtual machine that would essentially become a honeypot to track all events within the environment <br>
Step 2: to make the environment easily accessible I removed all firewalls and opened up all of the ports <br>
Step 3: To track all the attacks I created log analytics to understand the data better and used the default data collection fields
<br>
Step 4: Connect the VM to the log analytics <br>
Step 5: Setup Azure Sentenial to visualize the attack data <br>
Step 6: To get a more detailed log of attackers I implemented a <a href= https://github.com/gcamper3/SIEM-Detection-Lab/blob/main/powershellscript.txt/>PowerShell script</a> <br>
Step 7: I ran the query from earlier to find who has tried to attack the environment and this was the result 
![logs](https://github.com/user-attachments/assets/b257d583-5c87-4f00-a113-2337e5ea856e)<br>
Step 8: To better visualize the data I created the following query(ref 1) and created a visual map(ref 2) with Azure Sentinal to show where attacks were coming from <br>
(ref 1) ![qA18fco](https://github.com/user-attachments/assets/0bfe62d7-0933-4449-a4d4-1cb136e80ea5)<br>
(ref 2) ![FAILED_RDPWORLD_MAP](https://github.com/user-attachments/assets/8897a21b-8a06-4d37-b1f2-10257477c193)<br>



# Detection Lab

## Objective
[Brief Objective - Remove this afterwards]

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned


- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used


- Microsoft Azure
- Security Information and Event Management (SIEM) (Microsoft Sentinel)

  
## Steps


**Step 1. **Create Resource Group in Azure****
![image](https://github.com/user-attachments/assets/2cf69984-ce03-4ee3-9ce3-5fc5a2038984)
**Step 2. Create Virtual Network**
![image](https://github.com/user-attachments/assets/3ccb56c1-84eb-43aa-8cae-a37b25cfedc8)
**Step 2a.**
![image](https://github.com/user-attachments/assets/e3d186f8-33eb-4048-9574-15d846b2f9b3)
**Step 2b.**
![image](https://github.com/user-attachments/assets/e5cddb71-1c03-43d2-afea-1a68b750bc43)
**Step 3.** Create Virtual Machine
![image](https://github.com/user-attachments/assets/a5507dd0-4843-46ff-83aa-0797fad9e686)

**Step 4.** Edit Network Security Group
![image](https://github.com/user-attachments/assets/d0b517c1-c99f-4851-9255-9786b88ef420)
**Step 5.** Delete RDP Firewall and allow incoming traffic.
![image](https://github.com/user-attachments/assets/ebd81bd0-1386-4cba-879a-b8b5f87fdc0f)
**Step 6.** Select Settings and Add Inbound Security Rule For All incoming Traffic
![image](https://github.com/user-attachments/assets/184522ac-517f-43fb-9252-fd4c4544f24a)
![image](https://github.com/user-attachments/assets/62916701-a132-4449-8bcb-2abd57bacf4e)
**Step 7.** Log in to Virtual Machine
![image](https://github.com/user-attachments/assets/482aff48-0fcb-47d3-9552-cab4a9845113)
**Step 8.** Turn off windows firewall within virtual machine

**Step 9.** Intentional incorrect credentials on virtual machine
![image](https://github.com/user-attachments/assets/1f72c9a1-444a-463c-906d-ea50e11a8479)

![image](https://github.com/user-attachments/assets/4b0bc9b5-cd4a-431f-8713-05b737d28914)
**Step 10.** Veiwing RAW Logs on Virtual Machine for failure to logon Event ID: 4625
![image](https://github.com/user-attachments/assets/42989954-a35e-4147-b5b0-7daddbaf6c43)
**Step 11.** Create Log Repository in Azure
![image](https://github.com/user-attachments/assets/a42e2861-ca2d-452e-8779-3052685ec6ec)
**Step 12.** Configure Azure Monitor Agent Security Event Connector
![image](https://github.com/user-attachments/assets/b783c0be-705a-43fe-a6ce-a576ea4fe502)
**Step 13.** This will create a rule to forward logs from Virtual Machine to SIEM (Microsoft Sentinel)
![image](https://github.com/user-attachments/assets/87e3c7c4-aa52-4ece-91e1-92b738e5318e)
**Step 14.**
![image](https://github.com/user-attachments/assets/852aee64-7403-4a80-a49a-f78820fde688)
**Step 15.**
![image](https://github.com/user-attachments/assets/4a76aa3d-c085-4ee6-abdb-c8541cbe25e8)
**Step 16.**
![image](https://github.com/user-attachments/assets/3cc4d7ce-60bc-418d-8176-e2304b64b8a8)
**Step 17. ** Verify logs are forwarded to Microsoft Sentinel
![image](https://github.com/user-attachments/assets/da00c5c0-89b8-4db9-92a5-53b4faf94813)
**Lab completed!**





















### Using Threat Intelligence Tools with Splunk ES

While monitoring and responding to incidents in Splunk Enterprise Security (ES), it's important to enrich your analysis with external threat intelligence, they can be used on an as-needed basis to validate and investigate suspicious activity.

1. **Cisco Talos Intelligence**:
   - **Purpose**: To identify malicious IP addresses and domains based on extensive threat intelligence.
   - **Usage**:
     - When you detect suspicious IP addresses or domains in your Splunk ES searches, use the Cisco Talos Intelligence platform to check if they are flagged as malicious.
     - Cross-reference this information to determine the risk level of the activity.

 ![Screenshot 2024-08-23 155408](https://github.com/user-attachments/assets/0fb1d3fa-b130-4cb2-9d18-a7cb08d1635b)


2. **MXToolbox**:
   - **Purpose**: To provide email and network diagnostics, including blacklist checks and DNS lookups.
   - **Usage**:
     - Utilize MXToolbox to verify the reputation of email servers or domains involved in suspicious email activity.
     - Use their tools to perform blacklist checks and other diagnostics as part of your incident investigation.

![Screenshot 2024-08-23 155543](https://github.com/user-attachments/assets/247b7d7c-6888-4674-8053-cefdc30b8870)

       
3. **IPVoid**:
   - **Purpose**: To analyze and detect malicious IP addresses by checking against multiple threat databases.
   - **Usage**:
     - When encountering unknown or suspicious IP addresses in your logs, use IPVoid to check if they are listed in any threat databases.
     - This helps to quickly assess the potential threat posed by the IP address.
    
![Screenshot 2024-08-23 155738](https://github.com/user-attachments/assets/16ac4c22-3844-47ba-852e-39113c9bb06f)


4. **WhoisDomainTools.com**:
   - **Purpose**: To provide detailed domain and IP ownership information through whois lookups.
   - **Usage**:
     - Perform whois lookups on domains or IP addresses identified in your Splunk ES searches to gather ownership and registration details.
     - This can help in attributing the activity to a specific organization or individual, aiding in your investigation.

![Screenshot 2024-08-23 155845](https://github.com/user-attachments/assets/a84dbeb0-ebb9-4dc9-be49-e0b5f5e9b6ee)

  
5. **VirusTotal**:
   - **Purpose**: To scan files and URLs for viruses, malware, and other security threats.
   - **Usage**:
     - When investigating files or URLs that seem suspicious, use


![Screenshot 2024-08-23 155949](https://github.com/user-attachments/assets/e56225a8-35c1-4469-8ea3-93d9ca6c613e)


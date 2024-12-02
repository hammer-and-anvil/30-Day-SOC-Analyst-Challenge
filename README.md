# MyDFIR 30-day SOC Analyst Challenge

**Date Completed**: Septmeber 2024    
**Platform**: [30-Day MYDFIR SOC Analyst Challenge](https://youtube.com/playlist?list=PLG6KGSNK4PuBb0OjyDIdACZnb8AoNBeq6&si=a04sgVbt4H9-wycO)   
**Instructor**: MyDFIR   
**Skills Learned**: Security Operations Center (SOC) analysis, incident response, log analysis, malware attacking, threat detection, security monitoring, SIEM (Security Information and Event Management), forensic investigation, and use of various security tools.  
**Technologies/Tools Used**: Elastic Stack, Logstash, Kibana, Sysmon, Mythic, osTicket, Vultr.

---

### Overview:
The **MyDFIR 30-day SOC Analyst Challenge** provided an intensive, hands-on experience simulating the daily tasks of a Security Operations Center (SOC) analyst. Over 30 days, I was tasked with investigating security incidents, analyzing logs, detecting and mitigating threats, and responding to incidents. The challenge provided deep exposure to key SOC operations such as security monitoring, forensic investigation, and threat detection using a variety of cybersecurity tools and platforms.

---

### Key Learnings:
1. **Log Analysis with Elastic Stack**  
   Learned to stand up and efficiently use Elastic Stack (Elastic, Logstash, Kibana) to collect, search, and analyze large datasets of security logs from various network sources, identifying anomalies and potential threats.
   
2. **Advanced Threat Detection with Sysmon**  
   Configured Sysmon to gather detailed system activity logs and monitored for suspicious behavior, such as unusual process creation or network connections. 

3. **Red Teaming with Mythic**  
   Developed skills in offensive cybersecurity techniques using Mythic, a C2 (Command and Control) framework, to simulate attacks and assess vulnerabilities in a controlled environment.

4. **Incident Response with osTicket**  
   Gained experience using osTicket to manage and track incident reports, ensuring efficient communication, resolution, and documentation of security incidents.

5. **Cloud Infrastructure Management with Vultr**  
   Utilized Vultr for deploying and managing virtual machines to simulate attack and defense scenarios, gaining hands-on experience with cloud security practices.

---

### Projects and Hands-On Exercises:
- **Day 1: Diagram Project Scope**  
  Used Draw.io to create a logical diagram of the network that will be use in the course.
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20draw.io.png)

- **Days 3 & 4: Elastic Stack Setup and Log Analysis**  
  Configured and used Elastic Stack (Elastic, Logstash, Kibana) to collect and analyze logs from multiple sources, identifying key indicators of compromise (IoCs).
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20Elasticsearch%20svchost-RUDI.png)

- **Days 9 & 10: Sysmon Configuration and Threat Detection**  
  Set up Sysmon to monitor system processes, network connections, and file system activity, allowing me to detect suspicious behaviors and potential attacks.
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20Elasticsearch%20WindowsSysmon.png)

- **Days 14-17: Alerts and Dashboards in Kibana**  
  Define rules that detect conditions in your data and trigger actions when those conditions are met and create dashboard to visuallize where these attacks are sourcing from.
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20Dashboard%20Maps.png)

- **Days 20 & 21: Offensive Security with Mythic**  
  Utilized Mythic to simulate a red team attack, identifying security weaknesses and testing incident response capabilities within the SOC environment.
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20MythicApolloTasks.png)

  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20MythicApollo%20WindowsCMD.png)

- **Day 24 & 25: Incident Handling with osTicket**  
  Used osTicket to track and manage security incidents, ensuring that incidents were resolved efficiently and accurately, with clear documentation and communication.
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20osTicket%20SSH-Brute-Force-Attempt-RUDI.png)

- **Cloud Security with Vultr**  
  Deployed and managed virtual machines on the Vultr platform to conduct simulated attack and defense exercises, gaining hands-on experience in cloud infrastructure security, with a particular focus on firewall configuration and management
  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20Vultr%20CloudComputeInstances.png)

  ![My Image](https://github.com/hammer-and-anvil/30-Day-SOC-Analyst-Challenge/blob/main/assets/images/30DaySOC%20Screenshot%20Vultr%20FirewallGroupRules%20-edited.png)

- **Journal**  
  These are the original notes taken during the project. While spelling errors have been corrected, other inaccuracies, including procedural mistakes, have been retained along with their corresponding corrections. All VMs have since been destroyed and some security information has been removed or obfuscated.

  > *(Note: Before uploading the journal, I intentionally left the API keys intact, as I was confident that the Virtual Machines (VMs) associated with them had been destroyed. In fact, all services in Vultr were wiped clean. However, I received an email notification from GitHub stating, "GitGuardian has detected the following X-API-Key secret exposed within your GitHub account." I appreciate GitHub's strong security measures and proactive approach to protecting the community. As a result, I have now removed the exposed API keys as a security best practice. Lesson learned—thank you, GitHub!)*

---

### Technologies/Tools Covered:
- **Elastic Stack (Elastic, Logstash, Kibana)**: Utilized for log aggregation, search, and visualization to identify security threats and suspicious activities across systems.
- **Sysmon**: Monitored system activity in real time, providing detailed logs for detecting advanced persistent threats (APTs) and suspicious processes.
- **Mythic**: Used for simulating real-world attacks, helping to understand offensive cybersecurity techniques and test defense mechanisms within a controlled environment.
- **osTicket**: Used for incident management, tracking and documenting security incidents from detection to resolution in a structured manner.

---

### Takeaways:
The **MyDFIR 30-day SOC Analyst Challenge** significantly enhanced my practical skills in incident response, log analysis, and threat detection. I gained hands-on experience using industry-standard tools like Elastic Stack, Sysmon, and osTicket, and deepened my understanding of SOC operations. The challenge equipped me with valuable skills in both defensive and offensive cybersecurity, making me better prepared for a role as a SOC analyst or in any cybersecurity operations capacity.


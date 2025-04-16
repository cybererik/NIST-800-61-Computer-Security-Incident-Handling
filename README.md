# NIST-800-61-Computer-Security-Incident-Handling

![Copy of Security Frameworks_ NIST 800-61_ Computer Security Incident Handling Guide pptx](https://github.com/user-attachments/assets/8688e126-e811-4128-905b-47a32ccfbb48)

## Overview
NIST-800-61 is a comprehensive 80+ page guide on handling computer security incidents—but don’t worry, this project breaks it down into a high-level summary that’s easier to digest and more intuitive to understand.

In this project, we’ll briefly explore:
- **What NIST 800-61 is and why it matters**
- **How to apply its guidance effectively**
- **When to use it during an incident response process**

------
## What is NIST 800-61? 
Simply put, NIST 800-61 outlines how organizations should respond to computer security incidents. Incidents being any adverse event that threatens the confidentiality, integrity, or availability of information or information systems.

Examples of incidents:
Lost/stolen laptop, malware outbreak, data breach, account compromise, flood, fire, etc.

**NIST 800-61 provides a framework for detecting, analyzing, and recovering from security breaches in a structured and effective manner.**

------

## 💡 Clearing up confusion
![Copy of Security Frameworks_ NIST 800-61_ Computer Security Incident Handling Guide pptx (1)](https://github.com/user-attachments/assets/a8e7a5c6-4095-4fb8-9935-d21cf5395ced)

------
## 🔴 Incident Response Lifecycle 
![Copy of Security Frameworks_ NIST 800-61_ Computer Security Incident Handling Guide pptx](https://github.com/user-attachments/assets/ad6461b3-5f35-47d2-8ad9-cfcedbe61f0c)


**Preparation:** This phase involves activities such as creating an incident response plan, establishing communication channels, and conducting training and awareness programs to ensure that the organization is well-prepared to detect and respond to security incidents.

**Detection and Analysis:** In this phase, the organization detects and confirms the occurrence of a security incident, and then conducts an initial analysis to determine the scope and impact of the incident.

**Containment, Eradication, and Recovery:** This phase involves containing the incident to prevent further damage, eradicating the root cause of the incident, and recovering affected systems and data to return to normal operations.

**Post-Incident Activity:** This phase involves activities such as conducting a post-mortem analysis to identify areas for improvement, updating incident response procedures and controls, and sharing lessons learned with other stakeholders.

------

## 🛡️ Incident Phase 1: Preparation

![nist-incident-response](https://github.com/user-attachments/assets/b400695a-a584-40d5-a9e0-3566767b02e8)

---

### **Incident Phase 1: Preparation (Create Incident Response Plan)**

According to **NIST 800-61**, an incident response (IR) plan is a documented set of procedures that guides an organization's response to a security incident.

- It should include procedures for incident **detection, analysis, containment, eradication, recovery**, and **post-incident activity**.
- It should also include **roles and responsibilities**, **communication channels**, and methods for **measuring the effectiveness** of the plan.

📄 **Sample Incident Response Plan** – [Click to View](xxxxxxxxxxxxxxxxxxx)

---

### **Incident Phase 1: Preparation (Establish Communication Channels)**

- **Internal Communication Channels:**  
This can include email, intranet, internal instant messaging systems, and phone calls to reach all relevant personnel within the organization.

- **External Communication Channels:**  
This can include email, extranet, web portals, or phone calls to reach stakeholders outside the organization, such as customers, partners, or suppliers.

- **Emergency Notification Systems:**  
This can include automated voice or text messaging systems, or manual systems like sirens, that can be used to alert personnel of an incident in progress.

- **Media Outlets:**  
This can include traditional media like newspapers or television, as well as social media platforms.

---

### **Incident Phase 1: Preparation (Continuous Improvement)**

- **Exercise and Testing:**  
 Regularly conducting tabletop exercises, drills, and simulations can help identify gaps in the incident response plan and provide opportunities for improvement.

- **Post-Incident Reviews:**  
Conducting a review of each incident, including the response and resolution process, can help identify areas for improvement and inform changes to the incident response plan.

- **Metrics and Key Performance Indicators (KPIs):**  
Measuring key metrics, such as the time to detect an incident, the time to contain an incident, and the time to recover from an incident, can provide insight into the effectiveness of the incident response plan.

- **Feedback and Surveys:**  
Gathering feedback and conducting surveys of those involved in the incident response process can provide valuable insight into areas where the incident response plan was effective and areas where improvements can be made.

-------
## 🛡️ Incident Phase 2: Detection & Analysis

![222nist-incident-response](https://github.com/user-attachments/assets/a1550345-0d8f-4964-af0f-d54d0d7c1ada)

- **Finding Evidence of an Incident:**  
This could originate from a a SIEM, IDS/IDP system, or any number of security tools

- **Ensure the Incident Actually Occurred:**  
You need to verify that the incident is indeed a TRUE POSITIVE before trying to respond and remediate. The method for this depends on the incident

- **Start the Communication Process:**  
The way this goes will depend on your organization and how you have defined the flow of communications during an incident within your incident response plan.

-------
## 🛡️ Incident Phase 3: Containment, Eradication, and Recovery

![3333nist-incident-response](https://github.com/user-attachments/assets/1ee17f24-d834-4997-a16a-9ee6ccdd688d)

- **Stopping the incident from getting worse (containment):**  
Isolating/turning off affected systems

- **Removing the source of the problem (eradication):**  
Determining the attack vector and remediating it. Ex: Deleting the malware from all affected inboxes and blocking the source

- **Fixing the damage caused by the incident (recovery):**  
Re-imaging affected workstations

- **Making sure the incident does not happen again:**  
Invest in an good EDR solution, user education, more strict AV policies. In general, implement some kind of control, process or procedure

-------
## 🛡️ Incident Phase 4: Post-Incident Activity

![435345nist-incident-response](https://github.com/user-attachments/assets/22c76b05-87b0-41d3-8cbe-5a645ab0a40b)

1. **Review what happened during the incident**  
2. **Document what was done to respond** 
3. **Identify areas for improvement**  
4. **Share information to prevent future incidents**
5. **Update your Incident Response plan and related procedures**  
6. **Reflect on lessons learned**  


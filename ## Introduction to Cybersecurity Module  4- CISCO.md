## Introduction to Cybersecurity - CISCO 
## Module 4: Protecting the Organization
## 4.1 Cybersecurity Devices and Technologies 
# 4.1.1 Security Appliances
> Security appliances can be standalone devices like a router or software tools that are run on a network device. They fall into six general categories.
> 1. `Routers` - primarily used to interconnect various network segments together, they usually also provide basic traffic filtering capabilities. This information can help you define which computers from a given network segment can communicate with which network segments.
> 2. `Firewalls` - Firewalls can look deeper into the network traffic itself and identify malicious behavior that has to be blocked.
> 3. `Intrusion prevention systems` - IPS systems use a set of traffic signatures that match and block malicious traffic and attacks.
> 4. `Virtual private networks`- VPN systems let remote employees use a secure encrypted tunnel from their mobile computer and securely connect back to the organization’s network. VPN systems can also securely interconnect branch offices with the central office network.
> 5. `Antimalware or antivirus`- These systems use signatures or behavioral analysis of applications to identify and block malicious code from being executed.
> 6. `Other security devices` - Other security devices include web and email security appliances, decryption devices, client access control servers and security management systems.
# 4.1.2 Which Is It?
> Cisco’s ISR 4000 provides routing, filtering and encryption in a single platform : `Router`
> Cisco’s Firepower 4100 Series shows what’s happening on the network so that you can act faster in the face of a cyber attack : `Firewall`
> Cisco’s AnyConnect Secure Mobility Client empowers remote workers with highly secure access to @Αpollo's network from any device, at any time, in any location : `VPN`
> Cisco’s AMP provides next-generation endpoint protection, scanning and constantly monitoring files for malicious behavior : `Antimalware`
# 4.1.3 Firewalls
> A `Firewall` is designed to control or filter which communications are allowed in and which are allowed out of a device or network. A firewall can be installed on a single computer with the purpose of protecting that one computer (host-based firewall) or it can be a standalone network device that protects an entire network of computers and all of the host devices on that network (network-based firewall).
> Common firewall types:
> 1. Network layer firewall - This filters communications based on source and destination IP addresses.
> 2. Transport layer firewall - Filters communications based on source and destination data ports, as well as connection states.
> 3. Application layer firewall - Filters communications based on an application, program or service.
> 4. Context aware layer firewall - Filters communications based on the user, device, role, application type and threat profile.
> 5. Proxy server - Filters web content requests like URLs, domain names and media types.
> 6. Reverse proxy server - Placed in front of web servers, reverse proxy servers protect, hide, offload and distribute access to web servers.
> 7. Network address translation (NAT) firewall - This firewall hides or masquerades the private addresses of network hosts.
> 8. Host-based firewall- Filters ports and system service calls on a single computer operating system.
# 4.1.4 Which One?
> 1. A small, internal local area network with computers requires access to the Internet using a single Internet connection - `NAT firewall`
> 2. By default, Windows tries to block access to applications running on Windows PCs from other computers in the network - `Host-based firewall`
> 3. Employees using computers on the network are not permitted access to specific URLs, such as gambling sites - `Proxy server`
# 4.1.5 Port Scanning
> `Port scanning` is a process of probing a computer, server or other network host for open ports. It can be used maliciously as a reconnaissance tool to identify the operating system and services running on a computer or host, or it can be used harmlessly by a network administrator to verify network security policies on the network.
# 4.1.6 What Does It Mean?
> The port scan reported an ‘open’ state response. This means that the service running on the network `can be accessed` by other network devices. Therefore, if the service contains a vulnerability, it ` it could be exploited` by an attacker who could potentially gain access to computers on the network.
# 4.1.7 Intrusion Detection and Prevention Systems
> Intrusion detection systems (IDSs) and intrusion prevention systems (IPSs) are security measures deployed on a network to detect and prevent malicious activities.
> - An IDS can either be a dedicated network device or one of several tools in a server, firewall or even a host computer operating system, such as Windows or Linux, that scans data against a database of rules or attack signatures, looking for malicious traffic.
> - An IPS can block or deny traffic based on a positive rule or signature match.
# 4.1.8 Real-Time Detection
> `Active scanning`: Detecting attacks in real time requires actively scanning for attacks using firewall and IDS/IPS network devices.
> `Real Real-Time detection and response`- DDoS is one of the biggest attack threats requiring real-time detection and response.
# 4.1.9 Protecting Against Malware
> One way of defending against zero-day attacks and advanced persistent threats (APTs) is to use an enterprise-level advanced malware detection solution.
# 4.1.10 Security Best Practices
> National Institute of Standards and Technology (NIST) Computer Security Resource Center's guidelines:
> 1. Perform a risk assessment
> 2. Create a security policy
> 3. Physical security measures
> 4. Human resources security measures
> 5. Perform and test backups
> 6. Maintain security patches and updates
> 7. Employ access controls
> 8. Regularly test incident response
> 9. Implement a network monitoring, analytics and management tool
> 10. Implement network security devices
> 11. Implement a comprehensive endpoint security solution
> 12. Educate users
> 13. Encrypt data
## 4.2 Behavior Approach to Cybersecurity 
# 4.2.1 Behavior-Based Security
> Behavior-based security is a form of threat detection that involves capturing and analyzing the flow of communication between a user on the local network and a local or remote destination.
# 4.2.2. NetFlow
> NetFlow technology is used to gather information about data flowing through a network, including who and what devices are in the network, and when and how users and devices access the network.
> NetFlow is an important component in behavior-based detection and analysis.
# 4.2.3 Penetration Testing
> Penetration testing, commonly known as pen testing, is the act of assessing a computer system, network or organization for security vulnerabilities. A pen test seeks to breach systems, people, processes and code to uncover vulnerabilities which could be exploited.
> The five step pen test process: 
> - Step 1: Planning: The pen tester gathers as much information as possible about a target system or network, its potential vulnerabilities and exploits to use against it. (Passive or active reconnaissance)
> - Step 2: Scanning : The pen tester carries out active reconnaissance to probe a target system or network and identify potential weaknesses which, if exploited, could give an attacker access.
> - Step 3: Gaining access : The pen tester will attempt to gain access to a target system and sniff network traffic.
> - Step 4: Maintaining access : The pen tester will maintain access to the target to find out what data and systems are vulnerable to exploitation. It is important that they remain undetected, typically using backdoors, Trojan horses, rootkits and other covert channels to hide their presence.
> - Step 5: Analysis and reporting : The pen tester will provide feedback via a report that recommends updates to products, policies and training to improve an organization’s security.
# 4.2.4 Your Turn
> 1. Footprinting through the network to find ways to intrude gives you a chance to gather the information you need to plan a simulated attack.
> 2. Scanning a target allows you to identify potential exploitable weaknesses.
> 3. You will need to gain access to a network to exploit any vulnerabilities and simulate an attack.
> 4. Maintaining access, without being detected, means that you can gather further information on a target’s vulnerabilities.
> 5. Your findings will be reported to the organization so that security improvements can be made.
# 4.2.5 Impact Reduction
> Actions organizations should take when a security breach is identified:
> 1. Communicate the issue
> 2. Be sincere and accountable
> 3. Provide the details
> 4. Find the cause
> 5. Apply lessons learned
> 6. Check, and check again
> 7. Educate!
# 4.2.6 What Is Risk Management?
> `Risk management` is the formal process of continuously identifying and assessing risk in an effort to reduce the impact of threats and vulnerabilities.
> Process:
> - Frame the risk
> - Assess the risk
> - Respond to the risk
> - Monitor the risk
## 4.3 Cisco's Approach to Cybersecurity 
# 4.3.1 Cisco's CSIRT
> Many large organizations have a `Computer Security Incident Response Team (CSIRT)` to receive, review and respond to computer security incident reports.
> - Cisco’s CSIRT takes a proactive approach, collaborating with the Forum of Incident Response and Security Teams (FIRST), the National Safety Information Exchange (NSIE), the Defense Security Information Exchange (DSIE) and the DNS Operations Analysis and Research Center (DNS-OARC) to ensure we stay up-to-date with new developments.
# 4.3.2 Security Playbook
> One of the best ways to prepare for a security breach is to prevent it.Organizations should provide guidance on:
> - how to identify the cybersecurity risk to systems, assets, data and capabilities
> - the implementation of safeguards and personnel training
> - a flexible response plan that minimizes the impact and damage in the event of a security breach
> - security measures and processes that need to be put in place in the aftermath of a security breach.
> All this information should be compiled into a security playbook.
> - A security playbook is a collection of repeatable queries or reports that outline a standardized process for incident detection and response.
# 4.3.3 Tools for Incident Detection and Prevention
> There are a range of tools used to detect and prevent security incidents.
> - `SIEM`: A Security Information and Event Management (SIEM) system collects and analyzes security alerts, logs and other real-time and historical data from security devices on the network to facilitate early detection of cyber attacks.
> - `DLP`: A Data Loss Prevention (DLP) system is designed to stop sensitive data from being stolen from or escaping a network. It monitors and protects data in three different states: data in use (data being accessed by a user), data in motion (data traveling through the network) and data at rest (data stored in a computer network or device).
# 4.3.4 Cisco’s ISE and TrustSec
> Cisco Identity Services Engine (ISE) and TrustSec enforce user access to network resources by creating role-based access control policies.
# 4.3.5 Talk the Talk
> 1. Blocks or denies traffic based on a positive rule or signature match :`IPS` 
> 2. A system designed to stop sensitive data from being stolen from or escaping a network : `DLP`
> 3. A system that collects and analyzes security alerts, logs and other real time and historical data from security devices on the network : `SIEM`
> 4. Scans data against a database of rules or attack signatures, logs any detections and creates an alert for the network administrator: `IDS`
## 4.4 Quiz
> 1. Which of the following tools can be used to provide a list of open ports on network devices? : `Nmap`
> 2. What name is given to a device that controls or filters traffic going in or out of the network? : `Firewall`
> 3. What is the correct definition of risk management? : `The process of identifying and assessing risk to reduce the impact of threats and vulnerabilities`
> 4. What tool can identify malicious traffic by comparing packet contents to known attack signatures? : `IDS`
> 5. Behavior-based analysis involves using baseline information to detect what? : `Anomalies`
> 6. What protocol is used to collect information about traffic traversing a network? : `NetFlow`
> 7. The risk management process consists of four steps. Can you put these in the right order?
> - 1. Frame the risk
> - 2. Assess the risk
> - 3. Respond to the risk
> - 4. Monitor the risk
> 8. What is the main aim of a Cyber Security Incident Response Team (CSIRT)? : `To help ensure organization, system and data preservation by performing investigations into computer security incidents`
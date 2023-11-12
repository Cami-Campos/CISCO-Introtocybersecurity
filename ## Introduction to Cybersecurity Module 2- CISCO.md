## Introduction to Cybersecurity - CISCO 
## Module 2: Attacks, Concepts and Techniques.
## 2.1 Analyzing a Cyber Attack
# 2.1.1 Types of Malware
>  Malware is any code that can be used to steal data, bypass access controls, or cause harm to or compromise a system.
> 1. `Spyware`- Designed to track and spy on you, spyware monitors your online activity and can log every key you press on your keyboard, as well as capture almost any of your data, including sensitive personal information such as your online banking details.
> 2. `Adware` - Adware is often installed with some versions of software and is designed to automatically deliver advertisements to a user, most often on a web browser. 
> 3. `Backdoor`-  used to gain unauthorized access by bypassing the normal authentication procedures to access a system. As a result, hackers can gain remote access to resources within an application and issue remote system commands.
> 4. `Ransomware` - designed to hold a computer system or the data it contains captive until a payment is made. Ransomware usually works by encrypting your data so that you can’t access it.
> 5. `Scareware`- uses 'scare’ tactics to trick you into taking a specific action. Scareware mainly consists of operating system style windows that pop up to warn you that your system is at risk and needs to run a specific program for it to return to normal operation.
> 6. `Rootkit`-designed to modify the operating system to create a backdoor, which attackers can then use to access your computer remotely.Rootkits can also modify system forensics and monitoring tools, making them very hard to detect. 
> 7. `Virus`-A virus is a type of computer program that, when executed, replicates and attaches itself to other executable files, such as a document, by inserting its own code.
> 8. `Trojan Horse`- carries out malicious operations by masking its true intent.Trojans exploit your user privileges and are most often found in image files, audio files or games.
> 9. `Worms`- type of malware that replicates itself in order to spread from one computer to another.They exploit system vulnerabilities, they have a way to propagate themselves, and they all contain malicious code (payload) to cause damage to computer systems or networks.
# 2.1.2 Symptoms of Malware
> Common symptoms to look out for: 
> - an increase in central processing unit (CPU) usage, which slows down your device.
> - your computer freezing or crashing often.
> - a decrease in your web browsing speed.
> - unexplainable problems with your network connections.
> - modified or deleted files.
> - the presence of unknown files, programs or desktop icons.
> - unknown processes running.
> - programs turning off or reconfiguring themselves.
> - emails being sent without your knowledge or consent.
# .1.3 What Do You Think?
> 1. Malware designed to track your online activity and capture your data - `Spyware`
> 2. Software that automatically delivers advertisements - `Adware`
> 3. Malware that holds a computer system captive until a payment is made to the attacker - `Ransomware`
> 4. Malicious code that attaches to legitimate programs and usually spreads by USB drives, optical media, network shares or email - `Virus`
> 5. Malicious code that replicates itself independently by exploiting vulnerabilities in networks- `Worms`
## 2.2 Methods of Inflitration
# 2.2.1 Social Engineering
> `Social engineering` is the manipulation of people into performing actions or divulging confidential information.
> Examples:
> - `Pretexting` - This is when an attacker calls an individual and lies to them in an attempt to gain access to privileged data.
> - `Tailgating`
This is when an attacker quickly follows an authorized person into a secure, physical location.
> - `Quid pro quo` - This is when an attacker requests personal information from a person in exchange for something, like a free gift.
# 2.2.2 Denial-of-Service
> `Denial-of-Service (DoS)`attacks are a type of network attack that is relatively simple to carry out, even by an unskilled attacker. A DoS attack results in some sort of interruption of network service to users, devices or applications.
> Two types of DoS attacks:
> 1. `Overwhelming quantity of traffic`-
This is when a network, host or application is sent an enormous amount of data at a rate which it cannot handle. This causes a slowdown in transmission or response, or the device or service to crash.
> 2. `Maliciously formatted packets`-
A packet is a collection of data that flows between a source and a receiver computer or application over a network, such as the Internet. When a maliciously formatted packet is sent, the receiver will be unable to handle it.
# 2.2.3 Distributed DoS
> A Distributed DoS (DDoS) attack is similar to a DoS attack but originates from multiple, coordinated sources.
# 2.2.4 Botnet
>  A `botnet` is a group of bots, connected through the Internet, that can be controlled by a malicious individual or group.These bots can be activated to distribute malware, launch DDoS attacks, distribute spam email, or execute brute-force password attacks.
# 2.2.5 On-Path Attacks
> `On-path attackers` (`man-in-the-middle or man-in-the-mobile`) intercept or modify communications between two devices, such as a web browser and a web server, either to collect information from or to impersonate one of the devices.
> `Man-in-the-middle`-type of attack used to take control of a device without the user's knowledge.
> `Man-in-the-mobile`- type of attack used to take control over a user’s mobile device.
# 2.2.6 SEO Poisoning
> `SEO Poisoning` - attackers take advantage of popular search terms and use SEO to push malicious sites higher up the ranks of search result.
# 2.2.7 Wi-Fi Password Cracking
> `Brute-force attacks`-  testing possible password combinations to try and guess a password.
> `Network sniffing`- ability to identify unencrypted passwords by listening in and capturing packets sent on the network.
# 2.2.8 Password Attacks
> Entering a username and password is one of the most popular forms of authenticating to a web site.
> Common password security attacks:
> 1. `Password spraying`- This technique attempts to gain access to a system by ‘spraying’ a few commonly used passwords across a large number of accounts.
> 2. `Dictionary attacks`- A hacker systematically tries every word in a dictionary or a list of commonly used words as a password in an attempt to break into a password-protected account.
> 3. `Brute-force attacks`- brute-force attacks see an attacker using all possible combinations of letters, numbers and symbols in the password space until they get it right.
> 4. `Rainbow attacks`- A rainbow table is a large dictionary of precomputed hashes and the passwords from which they were calculated.When an attacker finds a match, they identify the password used to create the hash.
> 5. `Traffic interception` - If you store a password in clear, readable text, anyone who has access to your account or device, whether authorized or unauthorized, can read it.
# 2.2.9 Cracking Times
> Attacks usually involve a word-list file — a text file containing a list of words from a dictionary. A program such as Ophcrack, L0phtCrack, THC Hydra, RainbowCrack or Medusa will then try each word and common combinations until it finds a match.
# 2.2.10 Advanced Persistent Threats
> `Attackers also achieve infiltration through advanced persistent threats (APTs)` — a multi-phase, long term, stealthy and advanced operation against a specific target. For these reasons, an individual attacker often lacks the skill set, resources or persistence to perform APTs.
# 2.2.11 It’s Over to You...
>  What type of attack could each of these scenarios be?
> 1. On your way into the office, a person whom you have never seen before asks you to hold the door — they forgot their access card : `social engineering`
> 2. You have started getting an error message when accessing your computer: ‘Your connection was interrupted. A network change was detected.’ - `DoS`
> 3. You searched for @Apollo’s website on Google, but when you clicked on the top result, you were redirected to a page advertising antivirus software - `SEO poisoning`
## 2.3 Security Vulnerability and Exploits
> `Security vulnerabilities` are any kind of software or hardware defect. A program written to take advantage of a known vulnerability is referred to as an `exploit`. A cybercriminal can use an exploit against a vulnerability to carry out an `attack`, the goal of which is to gain access to a system, the data it hosts or a specific resource.
# 2.3.1 Hardware Vulnerabilities
> Hardware vulnerabilities are most often the result of hardware design flaws.
> Example : `Meltdown and Spectre` - two hardware vulnerabilities that affect almost all central processing units (CPUs) released since 1995 within desktops, laptops, servers, smartphones, smart devices and cloud services.
# 2.3.2 Software Vulnerabilities
> Software vulnerabilities are usually introduced by errors in the operating system or application code.
> `The SYNful Knock vulnerability` allowed attackers to gain control of enterprise-grade routers, such as the legacy Cisco ISR routers, from which they could monitor all network communication and infect other network devices.
# 2.3.3 Categorizing Software Vulnerabilities
> Most software security vulnerabilities fall into several main categories. These are: 
> 1. `Buffer owerflow`- Buffers are memory areas allocated to an application. A vulnerability occurs when data is written beyond the limits of a buffer. By changing data beyond the boundaries of a buffer, the application can access memory allocated to other processes. This can lead to a system crash or data compromise, or provide escalation of privileges.
> 2. `Non-validated input`- Programs often require data input, but this incoming data could have malicious content, designed to force the program to behave in an unintended way.
> 3. `Race conditions`- This vulnerability describes a situation where the output of an event depends on ordered or timed outputs. A race condition becomes a source of vulnerability when the required ordered or timed events do not occur in the correct order or at the proper time.
> 4. `Weakness in security practices` - Systems and sensitive data can be protected through techniques such as authentication, authorization and encryption. Developers should stick to using security techniques and libraries that have already been created, tested and verified and should not attempt to create their own security algorithms. These will only likely introduce new vulnerabilities. 
> 5. `Access control problems` - Access control is the process of controlling who does what and ranges from managing physical access to equipment to dictating who has access to a resource, such as a file, and what they can do with it, such as read or change the file.
# 2.3.4 Software updates
> The goal of software updates is to stay current and avoid exploitation of vulnerabilities.
# 2.3.5 What Do You Think?
> Can you identify what category each of these vulnerabilities falls into?
> 1. On starting at @Apollo, your network password was emailed to you in plain text and you were not prompted to change it : `Weakness in security practice`
> 2. Past employees still have access to @Apollo’s customer database: `Access control problem`
> 3. New users can log into their @Apollo account, even if they have signed up with an incorrectly formatted email address: `Non-validated input`
## 2.4 The Cybersecurity Landscape
# 2.4.1 Cryptocurrency
> `Cryptocurrency` is digital money that can be used to buy goods and services, using strong encryption techniques to secure these online transactions.
> Cryptocurrency owners keep their money in encrypted, virtual `wallets.` When a transaction takes place between the owners of two digital wallets, the details are recorded in a decentralized, electronic ledger or blockchain system.
>Approximately every ten minutes, special computers collect data about the latest cryptocurrencytransactions, turning them into mathematical puzzles to maintain confidentiality. These transactions are then verified through a technical and highly complex process known as `mining.`
> Once verified, the ledger is updated and electronically copied and disseminated worldwide to anyone belonging to the blockchain network, effectively completing a transaction.
# 2.4.2 Cryptojacking
> `Cryptojacking` is an emerging threat that hides on a user’s computer, mobile phone, tablet, laptop or server, using that machine’s resources to 'mine’ cryptocurrencies without the user's consent or knowledge.
## 2.5 Quiz
> 1. Which of the following characteristics describe a worm? : `Is self-replicating. Travels to new computers without any intervention or knowledge of the user`
> 2. What is the purpose of a rootkit?: `to gain privileged access to a device while concealing itself`
> 3. What is the primary goal of a DoS attack?:` to prevent the target server from being able to handle additional requests` 
> 4. What is the most common goal of search engine optimization (SEO) poisoning?: ` to increase web traffic to malicious sites`
> 5. A set of changes done to any program or application with the aim of updating, fixing or improving it is often referred to as what?: `a patch`
> 6. What do you call a program written to take advantage of a known security vulnerability?: `An exploit`
> 7. 'Securing physical access to target equipment is an organization’s best defense against a cyber attack.' Is this true or false?: `True`
> 8. What is a miner? : `A person that solves complex mathematical puzzles to verify a transaction`
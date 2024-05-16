# Phishing

This is a repository that will serve as a learning resource for me in the context of BeCode - Cybersecurity course - on the phishing topic. 

[BeCode Repo - Phishing](https://github.com/becodeorg/BXL-k4MK4r-2/tree/main/content/04.Phishing)

 This repository will cover the following topics: 

- What is Phishing? 
- Types of Phishing
- How to Identify Phishing
- Phishing Tools

Exercises and challenges will be included in this repository to test my knowledge on the topic. 

## What is Phishing?

Phishing is a type of social engineering attack often used to steal user data, including login credentials and credit card numbers. It occurs when an attacker, masquerading as a trusted entity, dupes a victim into opening an email, instant message, or text message. The recipient is then tricked into clicking a malicious link, which can lead to the installation of malware, the freezing of the system as part of a ransomware attack, or the revealing of sensitive information.

## Types of Phishing

1. **Spear Phishing**: This type of attack targets a specific individual or company. The attacker will research the target and create a personalized message to trick the victim into clicking a malicious link.
2. **Whaling**: This is a type of spear phishing that targets high-profile employees, such as C-level executives.
3. **Clone Phishing**: This type of attack involves taking a legitimate email and making a nearly identical copy of it. The attacker will then send the cloned email to the victim, hoping to trick them into revealing sensitive information.
4. **Vishing**: This type of attack involves using voice communication to trick the victim into revealing sensitive information.
5. **Smishing**: This type of attack involves using SMS messages to trick the victim into revealing sensitive information.
6. **Angler Phishing**: This type of attack involves setting up fake customer support accounts on social media platforms to trick victims into revealing sensitive information.
7. **Search Engine Phishing**: This type of attack involves creating fake websites that appear in search engine results to trick victims into revealing sensitive information.
8. **Business Email Compromise (BEC)**: This type of attack involves compromising a business email account to trick employees into transferring money or revealing sensitive information.
9. **Pharming**: This type of attack involves redirecting victims to fake websites to trick them into revealing sensitive information

## How to Identify Phishing

1. **Check the sender's email address**: Phishing emails often come from email addresses that are similar to, but not the same as, legitimate email addresses.
2. **Check for spelling and grammar mistakes**: Phishing emails often contain spelling and grammar mistakes.
3. **Check the links**: Hover over links in emails to see the actual URL. Phishing emails often contain links to fake websites.
4. **Check for urgency**: Phishing emails often contain urgent requests for sensitive information.
5. **Check for attachments**: Phishing emails often contain attachments that can install malware on your system.
6. **Check for generic greetings**: Phishing emails often use generic greetings, such as "Dear Customer," instead of your name.
7. **Check for suspicious requests**: Phishing emails often contain suspicious requests, such as requests for sensitive information or money. 


## Tools

#### [VirusTotal](https://www.virustotal.com/gui/home/upload)
VirusTotal was founded in 2004 as a free service that analyzes files and URLs for viruses, worms, trojans and other kinds of malicious content. Our goal is to make the internet a safer place through collaboration between members of the antivirus industry, researchers and end users of all kinds. Fortune 500 companies, governments and leading security companies are all part of the VirusTotal community, which has grown to over 500,000 registered users.

#### [PhishTools](https://www.phishtool.com/)  
Be you a security researcher investigating a new phish-kit, a SOC analyst responding to user reported phishing, a threat intelligence analyst collecting phishing IoCs or an investigator dealing with email-born fraud.

PhishTool combines threat intelligence, OSINT, email metadata and battle tested auto-analysis pathways into one powerful phishing response platform. Making you and your organisation a formidable adversary - immune to phishing campaigns that those with lesser email security capabilities fall victim to.

#### [MX Lookup](https://mxtoolbox.com/)
This test will list MX records for a domain in priority order. The MX lookup is done directly against the domain's authoritative name server, so changes to MX Records should show up instantly. You can click Diagnostics , which will connect to the mail server, verify reverse DNS records, perform a simple Open Relay check and measure response time performance. You may also check each MX record (IP Address) against 105 DNS based blacklists 

#### [PhishTank](https://phishtank.com/?)
PhishTank is a collaborative clearing house for data and information about phishing on the Internet. Also, PhishTank provides an open API for developers and researchers to integrate anti-phishing data into their applications at no charge.

#### [Spamhaus](https://www.spamhaus.org/)
Spamhaus is the world leader in supplying realtime highly accurate threat intelligence to the Internet's major networks.

#### [Phishing incident response](https://www.incidentresponse.org/playbooks/phishing)  
The phishing incident response playbook contains all 7 steps defined by the NIST incident response process: Prepare, Detect, Analyze, Contain, Eradicate, Recover, Post-Incident Handling.


## Exercises
 
1. **Phishing Email Exercise**: There are 5 emails in the `email` folder which are analyzed to determine if they are phishing emails or not. The analysis is documented in the `analysis` folder. 

2. We have to fish Alice, a car enthusiast. Here we will create a phishing email to send to [Alice](phishing_emails/alice.md) accordingly with the purpose of getting their credentials. I placed the phishing email in the `phishing-email` folder. 
We will have an email and a fake website to fish Alice. The fake webpage will be hosted on github pages and once the user enters their credentials, they will be warned that they have been fished.

Disclaimer: This repository is for educational purposes only.
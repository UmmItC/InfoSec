---
title: "L1 - Information Security Basic Concept"
date: 2024-09-15T18:07:18+0800
tags: ["Information Security", "Basic Concept", "L1", "School Course"]
---

## Introduction

These article are written for my education which is all about my school on collage. Just for my note and my friend who want to learn about Information Security.

As my viewpoint, these concept pretty much basic and easy to understand. Generally, these concept are the foundation of Information Security. So, let's start with the first lesson. Just for a article of this Lession one.

Anyway, Clarify the concept of This lession one :)

## What the heck is Information Security?

Information Security is the practice of defending information from unauthorized access, use, disclosure, disruption, modification, perusal, inspection, recording or destruction

For simplicity, we can use `InfoSec` as the abbreviation of Information Security.

For short of the definiton, here's the list of the terms:

| **No.** | **Field**                 | **No.** | **Field**                 |
|---------|---------------------------|---------|---------------------------|
| 1       | Management Science         | 11      | Service Management         |
| 2       | Operations Management      | 12      | Electronic Engineering     |
| 3       | Computer Science           | 13      | Risk Management            |
| 4       | Computer Engineering       | 14      | Operations Research        |
| 5       | Legal & Compliance         | 15      | Physical Security          |
| 6       | Statistics & Mathematics   | 16      | Cryptography               |
| 7       | Software Engineering       | 17      | Hardware Development       |
| 8       | Business Administration    | 18      | Ethical Hacking            |
| 9       | Project Management         | 19      | Computer Forensics         |
| 10      | Information Technology     | 20      | Security Writing           |

## Information Security Security Function

1. Confidentiality
2. Integrity
3. Availability
4. Accountability
5. non-repudiation

## CIA Meaning

I belive the course of exam will ask about the meaning of CIA, so please remember this :)

### 1. **Confidentiality**

**Confidentiality** means keeping information secret and making sure only the right people can see it. 

- **Goal**: Prevent unauthorized people from accessing sensitive information.
- **Example**: Using passwords or encryption to protect personal data from being seen by strangers.

### 2. **Integrity**

**Integrity** means making sure that information stays accurate and hasn’t been changed or corrupted.

- **Goal**: Ensure that data remains correct and hasn’t been tampered with.
- **Example**: Using checks to make sure that data hasn’t been altered accidentally or maliciously.

### 3. **Availability**

**Availability** means ensuring that information and systems are available and working when needed.

- **Goal**: Make sure that authorized users can access information and systems whenever they need to.
- **Example**: Having backup systems in place so that you can still access data if the main system fails.

In summary:
- **Confidentiality**: Who can see the information?
- **Integrity**: Is the information correct?
- **Availability**: Can you access the information when you need it?

## End-user

An `end-user` is the final person who uses a product or service. In computing and networking, end-users are individuals who operate devices or applications to perform their tasks. They interact directly with the technology, as opposed to those who develop, manage, or sell it.

## Definition of Hacker

A hacker of my definition is a person who really good at programming, hacking, or other about the computer. Usually, they got defined as a person who uses computers to gain unauthorized access to data.

But, i can say that that's definition is not correct, everyone can be a hacker. If you good enough at some of the field about computer, like acutally doing some kind of programming, GNU/Linux, or even Kernel programming. then you are the hacker of that field.

### Types of Hackers

A Hacker can be classified into several types, list're below :)

#### While Hat Hacker

A **White Hat Hacker** is a hacker who uses their skills for good, such as finding security holes in software.

For example, protecting a company's network from cyber attacks, or bug bounty hunting to find vulnerabilities in software then reporting them to the developers.

#### Black Hat Hackers

Generally, a **Black Hat Hacker** is a hacker who uses their skills for bad, such as breaking into computer systems.

Why? mostly for personal gain, such as stealing data, money, or causing damage to systems.

Like DDoS attacks, crated a malware or ransomware, or even hacking into a company's network to steal sensitive information to sell on the dark web for the good price.

You can say that Black Hat Hackers are the bad guys. or even say it's are Cybercriminals lol

#### Grey Hat Hackers

A **Grey Hat Hacker** is a hacker who uses their skills for both good and bad, depending on the situation.

Sometimes, they might break into a system to find security holes, then report them to the owner. But, they might also use their skills for personal gain or to cause damage.

For me, Grey hat hacker is It's the most common, and should be the way to go. How can we protect it if we don't invade it?

As a matter of fact, how can you fight if you don't know how to box?

that's the ethical of the hacker. You can turn it into black and white in the same time. it's simple. if you found a security hold, and you seize it to doing some hurtful things, then you are the black hat hacker. but if you seize it to report it to the owner, then you are the white hat hacker :)

#### Blue Hat Hackers

A **Blue Hat Hacker** is a hacker who is really enjoy the hacking, they are not really expect to gain something from it, in fact, they are just doing it for fun. or just show off their skills of this field :)

things like hacking into a company's network, or your hacker friend sent you some malware or trojan that created by them, like this, just for fun. or even just to show off their skills.

And also, The chances of it being an elementary school student are also high. The technology is brilliant, but the action is unclear. It's very common in this society, dont laught at this. many hacker starting from elementary school :)

#### Script Kiddie

A **Script Kiddie** is a person who uses pre-made tools to hack into systems, without really understanding how they work.

using the tools to crack the password is very common, especially for the real hacker. The important thing is, They know how it works, and already understand the concept of it.

The idea of turning the car by the head is the same. in this society, no one will doing all the thing with scratch. The tool is the way to go while made it easier to do the job. and the script kiddie is the one who using the tools without understanding the concept of it.

### Summary

- **White Hat Hacker**: A hacker who uses their skills for good, such as finding security holes in software.
- **Black Hat Hacker**: A hacker who uses their skills for bad, such as breaking into computer systems.
- **Grey Hat Hacker**: A hacker who uses their skills for both good and bad, depending on the situation.
- **Script Kiddie**: A hacker who uses pre-made tools to hack into systems, without really understanding how they work.

## Information Security Terminology

So many terms in the Information Security field, and it's important to know what they mean.

### Honeypot

In computer terminology, a honeypot is a computer security mechanism set to detect, deflect, or, in some manner, counteract attempts at unauthorized use of information systems. Generally, a honeypot consists of data that appears to be a legitimate part of the site which contains information or resources of value to attackers. It is actually isolated, monitored, and capable of blocking or analyzing the attackers. This is similar to police sting operations, colloquially known as `baiting` a suspect.

Lets say the real example, FBI arrested the criminal who are the owner of the website, and now the website already under FBI controls, But they want know more about the criminal, so they wont shutdown the current website. Instead, they are continue to monitor the website traffic or even waiting the new criminal to come. and keep trying to arrest some of the cybercriminal. That's the honeypot.

### Keyloggers

A keylogger is a type of surveillance software that records every keystroke made by a user, The recorded keystrokes are saved in a log file, which can then be accessed by the attacker. or even can real-time monitoring.

This is a common technique of the trojan software, and it's very dangerous. because it can record everything you type, including your password, credit card number, or even your personal information.

### Rootkit

A rootkit is a type of malicious software that is designed to hide the existence of certain processes or programs from normal methods of detection and enable continued privileged access to a computer.

Rootkit detection is difficult because a rootkit may be able to subvert the software that is intended to find it. Detection methods include using an alternative and trusted operating system, behavior-based methods, signature scanning, difference scanning, and memory dump analysis. Removal can be complicated or practically impossible, especially in cases where the rootkit resides in the kernel; reinstallation of the operating system may be the only available solution to the problem. When dealing with firmware rootkits, removal may require hardware replacement, or specialized equipment.

### Sniffer

A sniffer is a tool used to capture and analyze network traffic. It can be used for legitimate purposes, such as network troubleshooting, but it can also be used maliciously to capture sensitive information, such as passwords or credit card numbers.

### Zero Day

A zero-day vulnerability is a security flaw that is unknown to the software vendor and has no patch available yet. This makes it a high-risk vulnerability, as attackers can exploit it before a fix is released.

### Worm

A worm is a type of malware that spreads itself across networks and systems. Unlike viruses, worms do not need to attach themselves to other programs or files to spread. They can replicate and spread independently, making them a significant threat to network security.

### Exploit

An exploit is a software or technique that takes advantage of a vulnerability in a system to gain unauthorized access or cause harm. Exploits can be used to launch attacks, such as denial-of-service attacks.

### Encryption

Encryption is the process of converting information into a code to prevent unauthorized access. It is used to protect sensitive data, such as passwords, credit card numbers, and personal information, from being intercepted or read by unauthorized users.

### Cryptography

Cryptography is the practice of using codes and ciphers to protect information. It is used to secure communication and data, ensuring that only authorized users can access and read the information.

### Attack

An attack is an attempt to breach security or exploit vulnerabilities in a system. Attacks can take many forms, such as malware infections, phishing scams, or denial-of-service attacks.

### Vulnerability

A vulnerability is a weakness in a system that can be exploited by threats to gain unauthorized access or cause damage. Vulnerabilities can be found in software, hardware, or human processes, and they pose a significant risk to information security.

### Penetration Testing

Penetration testing is the practice of simulating attacks to find vulnerabilities in a system. It is used to identify security weaknesses and assess the effectiveness of security measures in place.


### and more ...

| **Term**                  | **Definition**                                                                                              |
|---------------------------|-------------------------------------------------------------------------------------------------------------|
| **Accountability**        | The responsibility to account for actions and decisions regarding security.                               |
| **Asset**                 | Any resource or item of value that needs protection, such as data, hardware, or software.                 |
| **Asset Valuation**       | The process of determining the value of an asset to prioritize its protection.                           |
| **Attack**                | An attempt to breach security or exploit vulnerabilities in a system.                                      |
| **Authentication**        | The process of verifying the identity of a user or system.                                                 |
| **Authorization**         | The process of granting or denying access to resources based on user credentials.                         |
| **Availability**          | Ensuring that information and systems are accessible when needed.                                         |
| **Bluejacking**           | Sending unsolicited messages or data to a Bluetooth-enabled device.                                        |
| **Computer Forensics**    | The process of collecting, analyzing, and preserving digital evidence.                                     |
| **Confidentiality**       | Ensuring that information is only accessible to those who are authorized.                                  |
| **Cryptography**          | The practice of using codes and ciphers to protect information.                                             |
| **Data Custodian**        | An individual responsible for managing and safeguarding data.                                               |
| **Encryption**            | The process of converting information into a code to prevent unauthorized access.                          |
| **Exploit**               | A software or technique that takes advantage of a vulnerability in a system.                              |
| **Exposure**              | The state of being vulnerable to threats or attacks.                                                        |
| **Honeypot**              | A decoy system designed to attract and detect potential attackers.                                          |
| **Identification**        | The process of recognizing and verifying entities in a system.                                              |
| **Impact**                | The potential damage or harm caused by a security breach or failure.                                       |
| **Incident Management**   | The process of detecting, responding to, and recovering from security incidents.                           |
| **Integrity**             | Ensuring that information is accurate and has not been altered or tampered with.                           |
| **Keyloggers**            | Software or hardware that records keystrokes to capture sensitive information.                           |
| **Layering**              | Using multiple security measures to protect a system, so if one layer fails, others remain effective.      |
| **Non-repudiation**       | Ensuring that an entity cannot deny their actions or involvement in a transaction.                         |
| **Penetration Testing**   | The practice of simulating attacks to find vulnerabilities in a system.                                    |
| **Phreaking**             | The act of hacking into telephone networks to make free calls or manipulate the system.                    |
| **Risk**                  | The potential for loss or damage due to threats exploiting vulnerabilities.                               |
| **Rootkit**               | Malicious software designed to hide the presence of other malware on a system.                            |
| **Safeguards**            | Measures or controls put in place to protect information and systems.                                      |
| **Security Exploit**      | A specific instance of exploiting a vulnerability to gain unauthorized access.                             |
| **Security Policy**       | A set of rules and guidelines for managing and protecting information and systems.                         |
| **Security Procedures**   | Detailed steps or methods for implementing security policies and protecting assets.                        |
| **Security Standard**     | Established benchmarks or guidelines that define security practices and measures.                         |
| **Separation of Duties**   | Dividing responsibilities among different people to reduce the risk of fraud or error.                     |
| **Service Level Agreement**| A contract defining the level of service expected from a provider.                                         |
| **Sniffer**               | A tool used to capture and analyze network traffic.                                                        |
| **Social Engineering**    | Manipulating people into divulging confidential information or performing actions that compromise security. |
| **Spoofing Attack**        | A tactic where an attacker pretends to be someone else to gain unauthorized access.                        |
| **Threat**                | Any potential danger that could exploit a vulnerability and cause harm.                                    |
| **Trojan Horse**          | Malicious software disguised as legitimate software to gain access or cause harm.                         |
| **Virus**                 | Malicious code that replicates itself and infects other programs or files.                                |
| **Vulnerability**         | A weakness in a system that can be exploited by threats to gain unauthorized access or cause damage.       |
| **Vulnerability Scanner** | A tool used to detect and identify security weaknesses in a system.                                        |
| **Wardriving**            | The act of driving around and searching for unsecured wireless networks.                                   |
| **Worm**                  | A type of malware that spreads itself across networks and systems.                                         |
| **Zero Day**              | A security vulnerability that is unknown to the software vendor and has no patch available yet.            |
| **Zero Trust Architecture**| A security model that requires verification of all users and devices, regardless of their location.        |

## Conclusion

It's the 3 hours of lession about the Information security basic concept. Should be pretty much easy :)

# Enhancing-Email-Security

Email security is essential for protecting sensitive information, preventing cyber attacks, and ensuring safe communication. The evolution of email and the increasing sophistication of threats have necessitated the development of comprehensive security measures. By understanding the common email security threats and implementing key protective measures, individuals and organizations can safeguard their email communications and maintain the integrity of their information. The primary objectives of email security are to ensure confidentiality, integrity, and availability of email communications, while also meeting compliance and regulatory requirements, protecting users from threats, and maintaining business continuity

### Skills Learned
1. Understand the importance of email security
2. Identify common email security threats
3. Implement authentication measures to verify sender identities
4. Use encryption methods to protect email content
5. Ensure email integrity to prevent tampering
 

### Tools Used
1. SPF (Sender Policy Framework)
2. DKIM (DomainKeys Identified Mail)
3. DMARC (Domain-based Message Authentication, Reporting, and Conformance)
4. PGP (Pretty Good Privacy) encryption
5. S/MIME (Secure/Multipurpose Internet Mail Extensions) encryption

## Steps
Staring out in cybersecurity as SOC Analyst — intern in an MSSP, I investigated a suspicious email that slipped past our filters. I was tasked to dig into the email headers, and that was where I encountered SPF, DKIM, and DMARC.

I was way lost at the first glance, but as I learned more about email and it architecture, I discovered how technology can elegantly simplify complex concepts, making them appear deceptively straightforward. This is what sparked my interest in email security.

**In this series we will;**
- Delve into the fundamentals of email, explaining what it is, how it functions, and the key components that make up the email infrastructure
- Also explore the key aspects of email security.
  
*Email, short for electronic mail, has become an indispensable communication tool in both personal and professional spheres. Despite its ubiquitous nature, many people may not fully understand how email works behind the scenes.*

## What is An Email?
Email is a method of exchanging digital messages over the internet using electronic devices. It allows users to send and receive text messages, documents, images, and other files quickly and efficiently. The primary components of an email include the sender, recipient, subject, body, and attachments. Emails are transmitted between email servers using standardized protocols to ensure reliable delivery.

## A Look At History and Evolution of Email
The concept of email dates back to the early days of computer networks in the 1960s and 1970s. Ray Tomlinson is often credited with inventing email in 1971 when he used the @ symbol to separate the user name from the computer name in an email address. This innovation laid the foundation for modern email systems. Over the decades, email has evolved from simple text-based messages to a sophisticated communication tool supporting rich media, attachments, and advanced features like encryption and spam filtering. Today, email is a vital part of both personal and business communication.

## How Email Works: The Basics
Email communication involves several key steps and components that work together to ensure messages are delivered correctly. Here’s a step-by-step breakdown of how email works:

**1. Composition**:
The email process begins with the sender composing a message using an email client or webmail interface. The sender enters the recipient’s email address, subject line, message body, and any attachments. Email clients include applications like Microsoft Outlook, Apple Mail, and Mozilla Thunderbird, while webmail services include platforms like Gmail, Yahoo Mail, and Outlook.com.

**2. Sending**:
Once the email is composed, the sender clicks the “Send” button. The email client then forwards the message to the sender’s email server using the Simple Mail Transfer Protocol (SMTP). SMTP is a protocol designed for sending emails from a client to a server or between servers.

**3. Transport**:
After the email is sent from the sender’s server, it travels across the internet to the recipient’s email server. This journey can involve multiple intermediary servers, each using SMTP to relay the message closer to its final destination.

**4. Receiving**:
The recipient’s email server receives the email and stores it until the recipient retrieves it. The recipient’s email server uses protocols like Post Office Protocol (POP3) or Internet Message Access Protocol (IMAP) to store and manage incoming messages. POP3 downloads the email to the recipient’s device and usually deletes it from the server, whereas IMAP keeps the email on the server, allowing the recipient to access it from multiple devices.

**5. Retrieval**:
When the recipient checks their email using an email client or webmail interface, the client connects to the email server using POP3 or IMAP. The server authenticates the recipient and delivers the email to their inbox. The recipient can then read, reply to, forward, or delete the message

## Key Components of Email Infrastructure
To understand how email works more comprehensively, let’s delve into the key components involved in the email infrastructure:

**1. Email Clients**:
Email clients are software applications used to compose, send, receive, and manage emails. They provide the user interface for interacting with email. Examples include:
- Desktop Clients: Microsoft Outlook, Apple Mail, Mozilla Thunderbird.
- Webmail Services: Gmail, Yahoo Mail, Outlook.com.

**2. Email Servers**:
Email servers are computers that store and manage email messages for users. They can be divided into two main types:
- Incoming Mail Servers: Use POP3 or IMAP to receive and store emails.
- Outgoing Mail Servers: Use SMTP to send emails.

**3. SMTP (Simple Mail Transfer Protocol)**:
SMTP is the protocol used for sending emails. It handles the transfer of email messages from the sender’s client to the recipient’s email server.

**4. POP3 (Post Office Protocol 3)**:
POP3 is a protocol used to retrieve emails from an email server. It downloads the email to the recipient’s device and typically removes it from the server.

**5. IMAP (Internet Message Access Protocol)**:
IMAP is a protocol used to retrieve and manage emails on an email server. It keeps the email on the server, allowing access from multiple devices.

**6. DNS (Domain Name System)**:
DNS translates domain names into IP addresses, enabling email servers to locate each other on the internet. It ensures that emails are routed to the correct destination.


drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*

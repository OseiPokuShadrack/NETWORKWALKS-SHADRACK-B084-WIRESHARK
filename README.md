# NETWORKWALKS-SHADRACK-B084-WIRESHARK
More About my Wireshark project in Week 1 at NETWORKWALKS

# Cybersecurity Wireshark Completed Labs at NetworkWalks

**Week 1 Extra Project — NetworkWalks B084**

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/WireShark-E87500?style=flat-square&labelColor=blue&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/NetworkWalks-B084-C00000?style=flat-square" />
</p>

---
## Project Overview

This is the project details of my Week 1 wireshark project NetworkWalks internship.

This extra project was to introduce strengthen our understanding about wireshark and showing me the various things WireShark is capable of doing.


## OBJECTIVES

The main objectives of this project is to:

- Find an Attackers IP using Wireshark
- Read Http plain text using "Follow stream" in WireShark
- Follow TCP stream to obtain information 
- Identify a Brute-Force attack in packets
- listen to unencrypted voice call between two devices using telephony in Wireshark

---
##  Purpose of the Project

To get a hands-on experience and be familiar
with the various use of Wireshark as a Cybersecurity tool


⚠️ **Important:** This Tool was used against systems that I own or have explicit permission to test.



# -- Project Procedure

## Task 1. Find the Attacker's IP

I completed all 10 assignments of this lab by using filters "ip.addr = " to find and trace the footsteps of a suspicious IP address then I realized there's been a specific IP address that has been probing many ports of the server at a short period of time which raise awareness of a possible attack. Below is the completed categories of
assignments done in this lab

### Screenshot

<img width="980" height="780" alt="Lab 3 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/1e817881-dede-4831-affe-4fa42df0c59a" />


---

## Task 2. Follow TCP stream
Followed a certain TCP stream and read a chat between a two employers and obtained their Guest WiFi password and Temporary password of one of the employers. This was focused on how unencrypted conversation can be intercepted with the Wireshark tool. The solution was to use a secure TCP stream like HTTPS to get conversations encrypted.

### Screenshot:
<img width="950" height="750" alt="Lab 4 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/ff8d35d6-fe85-4176-b37f-5d8b695eb164" />

---

## Task 3. TCP Stream 2
This task was similar to the second task but in this task I was assigned to follow the stream to find out about various web pages a firm's employees visit during work hours and it was found that an employee downloaded a file and hid a message which was seen as an anomaly.

### Screenshot

<img width="950" height="750" alt="Lab 5 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/dea7cfbc-0e2f-481b-82c7-e70d819afdb8" />


---

## Task 4. HTTP Plain Text Credentials
I navigated through HTTP packets using the "http" filter in Wireshark to complete this task. It was about A login page of a customer on an unencrypted website so it left the customer's credentials exposed leaving them vulnerable for attackers to exploit their account.
The safe way to stop this is to only type in your credentials over an HTTPS connection on a website.

### Screenshot

<img width="950" height="750" alt="Lab 6 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/b46b692c-b627-4306-957e-a5202fb47f30" />



## Task 5. Brute Force Attacks
In this lab I was tasked to detect a brute-force attack from a specific IP . I spotted the IP by finding a specific IP that has been trying multiple passwords over the network targeting the admin account and It really got in at the last end. This can be prevented by using a strong password policy


### Screenshot

<img width="950" height="750" alt="Lab 7 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/f675d85f-e383-430c-b512-8b83b7ed7fa6" />




## Step 6. VoIP scam
In this lab the task was to intercept an unencrypted phone call between a customer and a customer service personnel using telephony on wireshark. 
I was able to obtain the credit card number and expiry date which can harmful to the victim of the card .
The solution is to use an encrypted phone call protocols to make such important calls to avoid sensitive informations being exposed to attackers

### Screenshot

<img width="950" height="750" alt="Lab 8 Result - Osei Shadrack Poku" src="https://github.com/user-attachments/assets/d58cac7a-8a53-4e29-8e23-929dc65b6597" />

---


## What I Learned From these Labs

Through this lab , I learned how to:

- Install and use Wireshark.
- Capture and analyze packets on my network.
- Follow up conversations that is unencrypted between HTTP packets.
- Identify a brute-force attack over a network.
- Tail a certain IP address and know what's it is doing on the network whether it is suspicious or normal.
- Known more ports like the SIP and RTP as voice protocols.
- Use Wireshark filters to navigate through a large sum of packet captures.

---

## Security & Ethical Use

This cybersecurity laboratory was created only for educational purposes and authorized security testing.

All activities were performed within the controlled virtual lab environment. Any scanning, testing, or security-related activity should only be conducted on systems and networks where proper permission has been provided.

The lab environment helps provide a safe and isolated setup for learning cybersecurity concepts without affecting unauthorized systems.

---

## Tools & Resources

### Tools Used
- Wireshark 
- Windows 11 Pro

### Resources
- **Wireshark:** [https://wireshark.org/download.html](https://www.wireshark.org/download.html)
- **NetworkWalks labs:** [https://networkwalks.com/wireshark-lab3/]


---

## Author

**Shadrack Osei Poku**

Cybersecurity Intern — NetworkWalks  
Batch: **B084**
LinkedIn: [Shadrack Osei Poku](https://www.linkedin.com/in/shadrack-osei-poku-35b297387/)

---

##  Project Overview

**Program Name:** Cybersecurity at NetworkWalks | **Week:** 01 | **Project:** Completed Wireshark Labs | **Repository:** Github  (Use the above pictures to write a README.md for my GitHub using the syntax provided explain briefly in simple words and professionally written sentences don’t change the author details or any personal details)

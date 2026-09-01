# networkwalks-B082-week3-Password-Cracking

# Password Cracking with John the Ripper and Networkwalks Tools

<div align="center">

| **Batch** | **B082** |
| :--- | :--- |
| **Name** | **Iyaloo Shivute** |
| **Program** | Cybersecurity Training at Networkwalks Academy |
| **Modules** | W3-PM1 & W3-PM2 |

</div>

## 📌1. Introduction
This report covers two modules,  the first module covers password cracking with John the Ripper (JTR) (W3-PM1), while the second module covers password cracking with Networkwalks tools (W3-PM2).

Many files like PDF, ZIP, and Office documents can be locked with a password. When a file is locked, its password is stored in the form of a hash. A hash is a scrambled value that represents the password. To recover the password, we first take out this hash from the file and then run it through a cracking tool that tries different words until it finds a match.

In this lab tasks (W3-PM1) I used JTR John and JTR Johnny to recover the passwords of the protected PDF files. I also used two free online tools made by Networkwalks, namely, the Hash Calculator and Password Cracker. First used the Hash Calculator to take the hash out of the locked PDF files. Then i used the Password Cracker to find the real password from the hash. 

## 📌 2. Definitions and background

**Password** cracking is the process of recovering a password from stored data or a protected file. Security professionals use it to test how strong a password is and to show why weak passwords are risky. 

**John the Ripper (JTR)** is a popular password cracking tool used by security professionals to test how strong passwords are. It started as a tool for Unix systems but now works on Windows, Linux, and Mac. It can check many types of password hashes and also unlock password protected files like PDF, ZIP, and Office documents.

**Johnny** is the graphical version of John the Ripper. It gives a simple point and click screen, so beginners can use JTR without typing long commands. Both tools are widely used in security testing and learning labs to understand password safety.

## 📌 3. Modules completed & Tools utilized

The modules completed and tools utilized are listed in the table below:

| Modules completed| Tools/resources |
| :--- | :--- |
| **W3-PM1** | John the Ripper (JTR) (Terminal) & Johnny (GUI) JTR_default_password.txt, Online HashCrack, Notepad, Windows 11 Laptop |
| **W3-PM1** | Online Networkwalks Hash Calculator & Password Cracker, Notepad, Windows 11 Laptop |

---

## 📌 4. Target Files

| File | Source | Status |
| :--- | :--- | :--- |
| My Locked PDF1.pdf | Provided by the Instructor | Password successfully cracked ✅|
| My Locked PDF2.pdf | Provided by the Instructor | Password successfully cracked ✅ |
| My Locked PDF3.pdf | Provided by the Instructor | Password successfully cracked ✅ |

---


## 📌 5. Activities Performed 

### Module 1 (W3-PM1): JTR John (CLI) + Johnny (GUI)

**Task 1:**  Download and setup John the Ripper from official website on your windows PC. <br> <br>
**Task 2:**  Download Johnny and install GUI from official website. <br> <br>
**Task 3:**  Cracking the passwords following various steps.  <br> <br>

### Module 2 (W3-PM2): Networkwalks Tools

**Task 1:**  Download the encrypted PDF file (My Locked PDF1.pdf) to your laptop from the lab page: https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/ <br> <br>
**Task 2:**  Open the Networkwalks Hash Calculator in your web browser:  https://networkwalks.com/hash-calculator/ <br> <br>
**Task 3:**  Upload the locked PDF file to the Hash Calculator. The tool will read the file and give you the hash value that starts with $pdf$...<br> <br>
**Task 4:**  Copy the full hash value.<br> <br>
**Task 5:**  Open the Networkwalks Password Cracker in your web browser:  https://networkwalks.com/password-cracker/<br> <br>
**Task 6:**  Paste the hash value into the Password Cracker and start the attack. The tool will try different passwords until it finds a match.<br> <br>
**Task 7:**  Wait for the tool to finish. The cracked password will be shown on the screen.<br> <br>
**Task 8:**  Open the locked PDF file and enter the cracked password. <br> <br>

**_The detailed step-by-step of all tasks performed are attached in this repository Week 3 Report: Password Cracking_**. 

## 📌 7. Conclusion

This lab helped me understand how password cracking works step by step and why it is important to use strong passwords for protection.  I also learned that if a password is short or common, it can be found quickly, which proves the need for strong passwords.


## 📌 6. Evidences






📌 Summary of Results
#	File / Target	Cracked Password / Credential	Method Used
1	My Locked PDF1.pdf	good-luck	JTR John + Johnny (Terminal & GUI)
2	My Locked PDF1.pdf	good-luck	Networkwalks Tools (Online)
3	My Locked PDF2.pdf	1qaz2wsx	Networkwalks Tools (Online)
4	My Locked PDF3.pdf	password1	Networkwalks Tools (Online)
5	networkwalks_flag1.pdf	password1	HexStrike MCP + AI (Claude Desktop)
6	medirozahospital.com (Patient Portal)	admin:password123	Tor + Python Brute‑Force + curl Verification
---

## 📌 Flags Captured

| # | Flag | Source |
| :--- | :--- | :--- |
| 1 | `nw{cybersecurity_flag_captured_2608}` | My Locked PDF1.pdf |

<img width="808" height="1127" alt="pdf1 password crack" src="https://github.com/user-attachments/assets/fa8a4746-bfc5-4bf0-99f7-f6008045c439" />
<img width="365" height="112" alt="pdf 1 password crack" src="https://github.com/user-attachments/assets/64396e33-c9ac-4820-bb21-3cbdc61dac91" />
<img width="842" height="668" alt="john1" src="https://github.com/user-attachments/assets/f863d8b9-f7dc-4e6b-8432-66de49c6c929" />


---
---

---
| # | Flag | Source |
| :--- | :--- | :--- |
| 2 | `nw{networkwalks_flag1_jtr_270521_1}` | networkwalks_flag1.pdf |

<img width="876" height="1187" alt="hash jtr" src="https://github.com/user-attachments/assets/2ba3feba-2f8a-4035-a40a-d64a70195bec" />


---

| # | Flag | Source |
| :--- | :--- | :--- |
| 3 | `nw{networkwalks_persistence_jtr_270521}` | My Locked PDF2.pdf |

<img width="770" height="1099" alt="pdf2 password crack" src="https://github.com/user-attachments/assets/5ce11abc-c023-4572-825a-ede803527209" />


---

| # | Flag | Source |
| :--- | :--- | :--- |
| 4 | `nw{networkwalks_flag_260821_1}` | My Locked PDF3.pdf |

<img width="929" height="1210" alt="pdf3 password crack" src="https://github.com/user-attachments/assets/ba2ea34a-e69b-42b4-bad2-25e0f642d317" />


---

---
#	Flag / Credential	Source
5	xxxxx:xxxxx	medirozahospital.com (Patient Portal)
<img width="600" alt="curl verification showing location dashboard php" src="https://github.com/user-attachments/assets/placeholder_curl_output.png" />
<img width="1016" height="902" alt="Screenshot 2026-08-29 at 15-13-12 Hash Calculator - Networkwalks Academy" src="https://github.com/user-attachments/assets/74411ff7-d45e-4d54-b7d6-00d01be5d832" />
<img width="1073" height="919" alt="pdf1 1" src="https://github.com/user-attachments/assets/61eef888-f7e2-4bfe-90bb-132b4aad100a" />
<img width="803" height="623" alt="dashboard1" src="https://github.com/user-attachments/assets/7d7af293-a7b2-45c5-b315-44428f8925b8" />

---

## 📌 Key Learnings

📌 Key Learnings

   1. Hash Extraction – Password-protected files store passwords as hashes, which can be extracted using tools like pdf2john.pl or Networkwalks Hash Calculator.

   2. Dictionary Attacks – Wordlists like rockyou.txt and JTR_default_password.txt are highly effective against weak/common passwords.

    3 . Tool Versatility – Password cracking can be done via:

        Terminal (John the Ripper)

        GUI (Johnny)

        Online Tools (Networkwalks)

        AI-Assisted (HexStrike MCP + Claude Desktop)

   4.  AI Integration – Large Language Models can interface with security tools to automate password cracking.

    5.  Password Strength – Weak passwords like good-luck, password1, and 1qaz2wsx can be cracked in seconds.

    6. Multiple Methods – The same password (good-luck) was cracked using three different methods.

   7.  MCP Server Setup – Setting up AI-powered servers requires Python, virtual environments, and proper configuration.

    8. Real‑World Application – The Hospital Penetration Testing module proved that live targets with weak passwords and poor rate‑limiting are vulnerable to brute‑force attacks, and that IP‑based protections can be bypassed using Tor.

    9. Hybrid Approach – Combining Hydra (fast), Python (smart challenge handling), and manual verification (curl) provides a robust methodology.
    
---

📌 Conclusion

During Week 3, I completed five password cracking / penetration testing modules:

    W3-PM1: Successfully cracked My Locked PDF1.pdf using JTR Terminal and Johnny GUI.

    W3-PM2: Successfully cracked My Locked PDF1.pdf using Networkwalks online tools.

    Module 3: Successfully set up HexStrike MCP Server with Claude Desktop.

    W3-PM-FINAL: Successfully used AI to crack networkwalks_flag1.pdf.

    Module 5: Successfully cracked the patient portal credentials (admin:password123) of medirozahospital.com using Tor, Python brute‑force, and manual verification, as well as cracking the associated PDF files with Networkwalks tools.
    
Final Observations

    Weak passwords are easily compromised

    Multiple tools exist for password cracking

    AI can assist with password cracking

    Strong passwords are essential for security

    MCP servers enable AI to interact with security tools

    Live targets require a combination of tools and techniques – brute‑force, proxy rotation, and challenge handling are all necessary for success

    Ethical testing with proper authorisation is critical; all activities in Module 5 were performed with explicit permission

# -End-

## 👤 Author

**Jenik Shrestha**  
Cybersecurity Trainee | B082  
Networkwalks Academy  
*www.linkedin.com/in/jenikshrestha*


🙏 Acknowledgements
Special thanks to Waqas Karim (CCIE), NETWORKWALKS, for his invaluable mentorship and guidance throughout this

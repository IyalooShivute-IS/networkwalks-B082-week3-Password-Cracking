# networkwalks-B082-week3-Password-Cracking

# Password Cracking with John the Ripper and Networkwalks Tools

<div align="center">

| **Batch** | **B082** |
| :--- | :--- |
| **Name** | **Iyaloo Shivute** |
| **Program** | Cybersecurity Training at Networkwalks Academy |
| **Modules** | W3-PM1 & W3-PM2 |

</div>

## 📌 1. Introduction
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

**_The detailed Step-by-Step report of Week 3: Password Cracking is attached in the repository_**. 

## 📌 6. Conclusion

This lab helped me understand how password cracking works step by step and why it is important to use strong passwords for protection.  I also learned that if a password is short or common, it can be found quickly, which proves the need for strong passwords.


## 📌 7. Evidences

The passwords were cracked and used to open the locked PDF files as per the below screen shots.
### _My Locked PDF1 password cracked as:  good-luck_
<img width="809" height="636" alt="image" src="https://github.com/user-attachments/assets/c000956d-9b24-4780-8efe-3b47c0a3b232" />
<img width="940" height="573" alt="image" src="https://github.com/user-attachments/assets/7adee491-f72a-4f0a-8c5d-7f9149233f3e" /> <br><br>

### _My Locked PDF2 password cracked as: password1_
<img width="809" height="553" alt="image" src="https://github.com/user-attachments/assets/e481cb1c-fc5a-4729-8bb1-dcc6cae483d5" />
<img width="940" height="567" alt="image" src="https://github.com/user-attachments/assets/36f2ba1a-a9c9-4dee-8321-3de9125f602f" /><br><br>

### _My Locked PDF3 password cracked as:  1qaz2wsx_
<img width="781" height="597" alt="image" src="https://github.com/user-attachments/assets/bb6bd5bb-9146-4de6-a636-cccfca21fc67" />
<img width="940" height="419" alt="image" src="https://github.com/user-attachments/assets/f11bb0d1-d465-4546-90e6-fc996a47152a" /><br><br>


 
### Opened “My Locked PDF1”
<img width="940" height="701" alt="image" src="https://github.com/user-attachments/assets/17d953b6-d39c-45ff-82a2-b1832cb3291f" />

### Opened “My Locked PDF2”
<img width="893" height="694" alt="image" src="https://github.com/user-attachments/assets/bbe5e2ce-d48c-46cc-bea5-400c306a0216" />

### Opened “My Locked PDF3”
<img width="906" height="568" alt="image" src="https://github.com/user-attachments/assets/d887b513-ffbb-4e0a-952a-2e00da7ac6b1" />



## 👤 Author

**Iyaloo Shivute**    
Cybersecurity Intern B082

LinkedIn:  www.linkedin.com/in/iyaloo-shivute

## 📌 Project Information
**Program Name**: Cybersecurity at Networkwalks | **Week**: 03 | **Project**: Password Cracking | **Repository**: GitHub




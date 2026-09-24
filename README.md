# 🧪 CyberLab — Week 3 | Password Cracking with John the Ripper

## 🎯 Background

**John the Ripper (JTR)** is a password-cracking tool used by security professionals to test password strength.

Originally developed for Unix systems, John the Ripper is now available on multiple platforms, including Windows, Linux, and macOS. It supports different password hash types and can also be used to recover passwords from protected files such as PDF, ZIP, and Microsoft Office documents.

**Johnny** is the graphical user interface (GUI) for John the Ripper. It provides a simpler point-and-click interface that can help beginners work with JTR without relying entirely on command-line operations.

In this lab, John the Ripper and Johnny are used to recover the password of a protected PDF file in a controlled learning environment.

---

## 🎯 Project Overview

This project demonstrates the use of **John the Ripper (JTR)** and **Johnny GUI** to perform password recovery against the provided protected PDF file:

```text
My Locked PDF1.pdf
```

## 🎯 Objectives

- Install **John the Ripper (JTR)** on Windows.
- Install **Johnny GUI**.
- Use JTR to process the protected PDF file.
- Attempt to recover the password of the protected PDF.
- Perform the password recovery exercise using both **John the Ripper** and **Johnny GUI**.
- Document the practical results and observations.

---

## 🔐 Purpose of the Lab

The purpose of this lab is to understand how password-cracking tools can be used in authorized cybersecurity testing and learning environments.

The exercise also demonstrates the importance of using strong passwords to protect sensitive files.

---

## 🖥️ Lab Environment

| 🧩 Component | ⚙️ Configuration |
|---|---|
| 💻 Host OS | Windows |
| 🔐 Security Tool | John the Ripper |
| 🖥️ GUI Tool | Johnny |
| 📄 Protected File | `My Locked PDF1.pdf` |
| 🎯 Target | Authorized lab PDF |

---

# 🛠️ Lab Tasks

## Task — Crack the Protected PDF

**Objective:**  
Recover the password of the provided `My Locked PDF1.pdf` file using **John the Ripper** and **Johnny GUI** on the Windows PC.

---

### Step 1 — Download John the Ripper

Download **John the Ripper** from the official Openwall website:

🔗 [John the Ripper — Official Website](https://www.openwall.com/john/)

📸 **Evidence:**

![John the Ripper Download](Screenshots/Untitled1.jpg)

---

### Step 2 — Download and Configure Johnny GUI

Download **Johnny GUI** from the official Openwall website:

🔗 ![John the Ripper Download](Screenshots/Untitled2.jpg)

Run the setup file and install Johnny on the Windows PC.

After installation, open **Johnny**.

Go to:

**Settings → Browse**

Then locate and select the **`john.exe`** executable from the John the Ripper installation directory.

📸 **Evidence:**

![John the Ripper Download](Screenshots/Untitled3.jpg)

![John the Ripper Download](Screenshots/Untitled4.jpg)

![John the Ripper Download](Screenshots/Untitled5678.jpg)
---

## 📊 Results

| Tool | Result |
|---|---|
| John the Ripper | `---` |
| Johnny GUI | `---` |
| Protected File | `My Locked PDF1.pdf` |
| Password Recovered | `good-luck` |

---
### Step 3 — Extract the PDF Hash and Start the Password Recovery

Follow the steps below to prepare the encrypted PDF and start the password recovery process.

#### 3.1 — Download the Encrypted PDF

Download the encrypted PDF file to the Windows PC.

📸 **Evidence:**

![Encrypted PDF](Screenshots/Untitled-1.jpg)

---

#### 3.2 — Extract the PDF Hash

Open the PDF Hash Extractor website and upload the encrypted PDF file to extract its hash.

🔗 [PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)

Browse to the PDF file and click **Upload**.

📸 **Evidence:**

![PDF Hash Extraction](Screenshots/Untitled-2.jpg)

---

#### 3.3 — Copy the Hash Value

Select and copy the generated hash value.

📸 **Evidence:**

![PDF Hash Value](Screenshots/Untitled-3.jpg)

---

#### 3.4 — Save the Hash as a Text File

Open Notepad and paste the copied hash value.

Save the file as:

```text
hash1.txt
```
--- 
Open notepad:
![Hash Text File](Screenshots/Untitled-4.jpg)
Paste the hash value inside notepad:
![Hash Text File](Screenshots/Untitled-5.jpg)
Save as text file:
![Hash Text File](Screenshots/Untitled-6.jpg)
Open Johnny and Click on ‘Open password file’:
![Hash Text File](Screenshots/Untitled-7.jpg)
Browse to the hash1.txt file that you have just saved & click on Open:
![Hash Text File](Screenshots/Untitled-8.jpg)
Click on ‘Start new attack’:
![Hash Text File](Screenshots/Untitled-9.jpg)
Now you can use this password to open your PDF file.
![Hash Text File](Screenshots/Untitled-10.jpg)
Open the encrypted PDF
![Hash Text File](Screenshots/Untitled-11.jpg)
 and Enter password1 (which you have just cracked):
![Hash Text File](Screenshots/Untitled-12.jpg)

---


## 💡 Key Takeaways

This lab provided practical experience with **John the Ripper** and **Johnny GUI** for password recovery.

The exercise demonstrated how password-cracking tools can be used during authorized security testing and reinforced the importance of using strong passwords when protecting sensitive files.

---

## 🔐 Ethical Use

This project was performed in a controlled cybersecurity learning environment using the provided laboratory file.

Password-cracking techniques should only be used against files, systems, or accounts for which appropriate authorization has been granted.

---

## 🛠️ Tools Used

`John the Ripper` · `Johnny GUI` · `Windows`
## 📌 Module Status

**Week 3 — Project Module 1: Password Cracking with John the Ripper — Completed ✅**
---

# 🧪 CyberLab — Project Module 2 | Password Cracking with Networkwalks Tools 



## Task — Crack the Protected PDF Using Networkwalks Tools

**Objective:**  
Recover the password of the provided `My Locked PDF1.pdf` file using the **Networkwalks Hash Calculator** and **Networkwalks Password Cracker** on a Windows laptop.

---

### Step 1 — Download the Encrypted PDF

Download the encrypted PDF file `My Locked PDF1.pdf` from the Networkwalks lab page.

🔗 [Networkwalks Password Cracking Lab](https://networkwalks.com/project-task-lab-password-cracking-with-networkwalks-tools/)

📸 **Evidence:**

![Encrypted PDF](Screenshots/Untitled-13.jpg)

---

### Step 2 — Open the Networkwalks Hash Calculator

Open the **Networkwalks Hash Calculator** in a web browser.

🔗 [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)

📸 **Evidence:**

![Networkwalks Hash Calculator](Screenshots/Untitled-14.jpg)

---

### Step 3 — Upload the Locked PDF

Upload the locked PDF file to the **Hash Calculator**.

The tool will read the file and generate a PDF hash value beginning with:

```text
$pdf$
```
📸 **Evidence:**

### Step 4 — Copy the Hash Value

Copy the complete hash value generated by the Hash Calculator.

📸 **Evidence:**

![PDF Hash Value](Screenshots/Untitled-16.jpg)

---

### Step 5 — Open the Networkwalks Password Cracker

Open the **Networkwalks Password Cracker** in a web browser.

🔗 [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)

📸 **Evidence:**

![Networkwalks Password Cracker](Screenshots/Untitled-17.jpg)

---

### Step 6 — Start the Password Recovery

Paste the complete PDF hash value into the **Password Cracker** and start the attack.

The tool will try different passwords until it finds a matching password.

📸 **Evidence:**

![Password Cracking](Screenshots/Untitled-18.jpg)

---

### Step 7 — Wait for the Password Recovery

Wait for the tool to complete the password recovery process.

The cracked password will be displayed on the screen when the process is completed.

📸 **Evidence:**

![Cracked Password](Screenshots/Untitled-19.1.jpg) 

---

### Step 8 — Open the Protected PDF

Open the encrypted PDF file and enter the cracked password.

📸 **Evidence:**

![Enter Cracked Password](Screenshots/Untitled-20.jpg)

---

## 📊 Results

| Tool | Purpose | Result |
|---|---|---|
| Networkwalks Hash Calculator | Extract the PDF hash | Hash successfully generated |
| Networkwalks Password Cracker | Recover the password | Password recovered |
| Protected PDF | Verify the recovered password | PDF successfully opened |

---

## 💡 Key Takeaways

This lab provided practical experience with the **Networkwalks Hash Calculator** and **Password Cracker**.

The exercise demonstrated the relationship between a protected PDF, its hash value, and password recovery, while reinforcing the importance of using strong passwords to protect sensitive files.

---

## 🔐 Ethical Use

This project was performed in a controlled cybersecurity learning environment using the provided laboratory PDF.

Password-cracking techniques should only be used against files, systems, or environments for which appropriate authorization has been granted.

---

## 🛠️ Tools Used

`Networkwalks Hash Calculator` · `Networkwalks Password Cracker` · `Windows` · `Web Browser`

---

## 👤 Author

This CyberLab was created and documented by **Adelino Sulude**
for hands-on cybersecurity practice.

**LinkedIn:** [Adelino Sulude](https://www.linkedin.com/in/adelino-sulude/)

## 🙏 Credits

The training and lab concepts were learned from:

- **Waqas Karim** — Cybersecurity Professional, CCIE
  - Instructor of the cybersecurity training used as a learning reference.
  - **LinkedIn:** [Waqas Karim](https://www.linkedin.com/in/waqaskarim/)

All lab configurations, testing, documentation, and practical experimentation
were performed by me in my own virtual lab environment.

## 📌 Module Status

**Week 3 — Project Module 2: Password Cracking with Networkwalks Tools — Completed ✅**

---
## 📌 Project Information
Program Name: Cybersecurity at Networkwalks | Week: 03 | Project: Password Cracking with John the Ripper and Networkwalks Tools | Repository: GitHub
The internship provided the learning material, project requirements, and practical exercises used as the basis for this work.

---


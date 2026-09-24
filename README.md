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
| John the Ripper | `[INSERT RESULT]` |
| Johnny GUI | `[INSERT RESULT]` |
| Protected File | `My Locked PDF1.pdf` |
| Password Recovered | `[INSERT RESULT]` |

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
(Screenshots/Untitled-4.jpg)
(Screenshots/Untitled-5.jpg)

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

---

## 👤 Author

**Adelino Sulude**

This project was completed as part of the **Networkwalks Cybersecurity Internship Program**.

All practical execution, testing, analysis, and documentation in this repository were performed by **Adelino Sulude**.

**Focus:** Network & Infrastructure | Cybersecurity

---

## 🙏 Training & Credits

This project was developed based on the practical exercises and training provided through the **Networkwalks Cybersecurity Internship Program**.

**Training Instructor:**  
**Waqas Karim — CCIE**

The internship provided the learning material, project requirements, and practical exercises used as the basis for this work.

---


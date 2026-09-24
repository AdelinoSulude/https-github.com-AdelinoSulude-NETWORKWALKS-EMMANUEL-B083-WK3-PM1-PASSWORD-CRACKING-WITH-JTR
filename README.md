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

## 🗺️ Lab Architecture

The exercise is performed locally on the Windows PC against the provided protected PDF file.

```text
┌──────────────────────┐
│      Windows PC      │
│                      │
│  ┌────────────────┐  │
│  │ John the Ripper│  │
│  └────────────────┘  │
│          │           │
│          ▼           │
│  ┌────────────────┐  │
│  │  Locked PDF    │  │
│  │ My Locked PDF1 │  │
│  └────────────────┘  │
│          ▲           │
│          │           │
│  ┌────────────────┐  │
│  │   Johnny GUI   │  │
│  └────────────────┘  │
└──────────────────────┘

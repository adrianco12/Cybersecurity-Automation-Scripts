# 🛡️ Cybersecurity Automation Scripts  

## 📖 Overview  
This repository contains a collection of cybersecurity automation scripts designed to reduce manual effort and optimize incident response time. The scripts provide practical solutions for detecting email spoofing, monitoring file integrity, and identifying typosquatted domains that attackers might use for phishing or fraud. I created these scripts using my software development background, and researching the way attacks can happen.

## 📑 Table of Contents  
- [Email Spoof Checker ✉️](#email-spoof-checker-️)  
- [File Integrity Monitor 🔒](#file-integrity-monitor-)  
- [Typosquat Detection 🌐](#typosquat-detection-)  
- [Conclusion 💼](#conclusion-)  

## ✉️ Email Spoof Checker  
This Python script parses email headers and checks for potential indicators of spoofing.  
- Extracts key information from email headers.  
- Analyzes sender domains for SPF (Sender Policy Framework) records.  
- Extracts sender IP addresses and warns about suspicious patterns.  
- Helps detect forged sender addresses used in phishing campaigns.  

## 🔒 File Integrity Monitor  
This project monitors file integrity by calculating and comparing cryptographic hashes.  
- Uses **SHA-256** hashing to generate a unique signature for each file.  
- Stores and compares hash values to detect unauthorized modifications.  
- Immediately flags changes that may indicate tampering or corruption.  
- Ensures sensitive files remain unaltered and trustworthy.  

## 🌐 Typosquat Detection  
This Python script identifies potential typo-squatted domains that mimic legitimate sites.  
- Generates domain variations using:  
  - Character omission  
  - Character swapping  
  - Character replacement  
  - Character insertion  
  - Hyphen insertion  
- Checks availability of generated domains via DNS resolution.  
- Reports active domains that could pose phishing or fraud risks.  

## 💼 Conclusion  
These automation scripts reflect real-world cybersecurity tasks that analysts and engineers perform daily. From detecting email spoofing attempts to monitoring file integrity and identifying typosquatted domains, each tool demonstrates skills in **threat detection, incident response, and proactive defense**. Using and extending these scripts prepares you for roles such as **SOC Analyst, Threat Hunter, or Security Engineer**, where automating repetitive tasks is crucial for faster and more efficient responses to cyber threats.  

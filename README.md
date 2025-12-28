# Cryptography Lab 2: Encryption & Digital Signatures

## 🔐 Lab Overview
This repository contains my work for Cryptography Lab 2, focusing on **symmetric encryption** with AES-256 and **asymmetric cryptography** with RSA keys and digital signatures.

## 📁 Files in This Repository
| File | Description |
| `secret_message.txt.gpg` | A file encrypted using **AES-256 symmetric encryption** with GPG |
| `document_to_sign.txt.asc` | A document with a **digital signature** created using my RSA private key |

## 🎯 What I Learned & Demonstrated
- **Symmetric Encryption**: How to encrypt and decrypt files using a single shared passphrase (AES-256)
- **Asymmetric Cryptography**: How to generate an RSA-4096 public/private key pair
- **Digital Signatures**: How to create and verify signatures to ensure document integrity and authenticity
- **Key Management**: The importance of protecting private keys while freely sharing public keys

## 🛠️ Tools Used
- **Gpg4win** (GNU Privacy Guard for Windows)
- **Command Prompt** (for executing GPG commands)
- **GitHub** (for version control and submission)

## 🔍 How to Verify the Files
1. Clone this repository: `git clone https://github.com/azimohemekajohn/cryptography-lab-2.git`
2. Decrypt the message (requires the passphrase): `gpg --decrypt secret_message.txt.gpg`
3. Verify the signature: `gpg --verify document_to_sign.txt.asc`

## 👨‍💻 Student Information
- **Name**: Azimoh Emeka John
- **Course**: CYB301 - Cryptography Fundamentals
- **Date**: December 2025



*This repository is for educational purposes as part of my cybersecurity studies.*

# NetworkWalks Tools Lab – Week 3 (PM2): Locked PDF Password Cracking

## 📌 Overview
This repository documents **Module 1** of the NetworkWalks Tools Lab, Week 3 (PM2), which focuses on extracting hashes from password-protected PDF files and cracking them to recover the original passwords.

## 🎯 Objective
- Identify password-protected PDF files
- Extract their crackable hash (`$pdf$` format)
- Crack the hash using a password-cracking tool to recover the plaintext password
- Record and document proof of successful cracks

## 📂 Repository Structure
```
NetworkWalks_Week3/
├── Locked_PDF_Files/              # Original password-protected PDFs
├── PDF1_hash with Password.txt    # Extracted hash + cracked password (LockedPDF_1)
├── PDF2_hash with Password.txt    # Extracted hash + cracked password (LockedPDF_2)
├── PDF3_hash with Password.txt    # Extracted hash + cracked password (LockedPDF_3)
└── ScreenShot & Recording/        # Screenshots + screen recordings as proof of cracking
```

## 🔍 Methodology
1. The hash of each locked PDF was extracted in the `$pdf$` format (compatible with John the Ripper / Hashcat mode 10500).
2. The extracted hash was run through a password-cracking tool against a wordlist.
3. Once cracked, the plaintext password was verified by opening the PDF.
4. The process was recorded on screen and screenshots were taken as evidence.

## ✅ Results

| File | Cracked Password |
|------|-------------------|
| LockedPDF_1.pdf | `good-luck` |
| LockedPDF_2.pdf | `Password1` |
| LockedPDF_3.pdf | `password1` |
| My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf | `password1` |

## 🎥 Evidence
- `pdf1_hash_crack.png` – Hash extraction for PDF 1
- `PDF 2 Password Cracked.png` – Successful crack of PDF 2
- `PDF 3 Password Cracked.png` – Successful crack of PDF 3
- `Module 1 PDF 2 Cracking.mkv` – Full screen recording of PDF 2 cracking process
- `Module 1 PDF 3.mkv` – Full screen recording of PDF 3 cracking process

## ⚠️ Disclaimer
All PDF files used in this lab were created solely for training/educational purposes as part of the NetworkWalks Tools Lab. This content is shared for **academic/learning purposes only** and must not be used against files or systems without proper authorization.

## 🧑‍💻 Author
**Shahzeb Ali**

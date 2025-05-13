# 🔍 Operation Redbridge (2024) – Digital Forensics Case Study

## 📁 Project Overview

This repository contains a comprehensive digital forensics case study conducted as part of the **Digital Forensics Semester Project**. The objective was to extract, analyze, and interpret concealed and encrypted evidence recovered during a simulated criminal investigation. The project focuses on a fictional case titled **Operation Redbridge (2024)**, involving allegations of sexual misconduct, evidence tampering, digital obfuscation, and forensic countermeasures.

---

## 👥 Authors

- Muhammad Huzaifa (2022389)  
- Muhammad Abdullah (2022323)  
- Hassaan Ali (2022654)  
- Saadullah (2022420)

---

## 📖 Case Summary

### Incident:
Anise Famke De Boer, a student and fashion model, accuses Nicolas Valentino—a fashion designer—of inappropriate conduct during a photoshoot session. After waking up under suspicious circumstances, she later reported the incident, triggering a digital investigation into Valentino’s devices.

### Key Allegations:
- Sexual misconduct and intoxication
- Deletion and destruction of digital evidence
- Intentional concealment of incriminating data

---

## 🔬 Scope of Analysis

- **Digital Image Forensics:** Extraction of hidden messages (e.g. steganography in "Wendigo.png").
- **Encryption Techniques:** Base64 encoding and Vernam cipher with key `thewendigo`.
- **Metadata Examination:** Tracking files and timelines for file access/modification.
- **Log Analysis:** Parsing system logs for user behavior and activity.
- **File Recovery & Artifact Analysis:** Inspection of high entropy and deleted files.
- **Behavioral Analysis:** Study of chat screenshots, suspicious documents, and web searches.

---

## 📦 Key Digital Exhibits

| Exhibit        | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| AXA/1          | Damaged camera memory card                                                  |
| AXA/2          | Smashed laptop with irrecoverable SSD                                       |
| AXA/3          | External hard disk drive (main subject of analysis)                         |
| Wendigo.png    | Contained hidden encrypted message (Base64 + Vernam)                        |
| Menswear1.pdf  | Disturbing PDF glorifying violence against women                            |
| Tracking Log   | `Desktop-7O9F4FR.log` with login/system activity records                     |
| Chat Screenshots | Accusatory conversations involving threats and coercion                  |
| Drug Research  | Images and cached web pages about Flunitrazepam detection                  |
| High Entropy File | Likely encrypted data container (VeraCrypt suspected)                   |
| Resume Files   | Personal CVs possibly used for manipulation or targeting                    |

---

## 🧰 Tools & Platforms Used

### Forensic Tools:
- **Autopsy** – Comprehensive forensic toolkit used for:
  - File system recovery
  - Metadata analysis
  - Search index generation
  - Steganography detection

### Online Utilities:
- [Stylesuxx Steganography Tool](https://stylesuxx.github.io/steganography/) – Image analysis  
- [CyberChef (Immersive Labs)](https://cyberchef.immersivelabs.online) – Hex decoding, Base64, Vernam cipher  
- Metadata and file entropy checkers (built into Autopsy)

---

## 📊 Key Findings

- Encrypted communications using steganographic images and ciphers.
- Drug-related images and search history involving **Flunitrazepam**, **Rohypnol**, and **Hypnodorm**.
- Evidence of digital countermeasures: use of VeraCrypt, HxD hex editor.
- Aggressive chat messages and suspicious behavioral patterns.
- Highly suspicious files and documents pointing toward a possible premeditated offense.

---

## ⚖️ Conclusion

This forensic investigation revealed:
- Clear intent to conceal and obfuscate sensitive data.
- Presence of tools and behavior indicative of digital tampering.
- Aggressive interpersonal communications and disturbing media files suggesting concerning motives.

The results support further legal action and warrant a deeper investigation into encrypted containers and metadata.

---

## 🧪 Future Work

- Attempt decryption of the high-entropy SYSTEM file.
- Cross-reference metadata with external timelines and communications.
- Correlate behavioral patterns from logs with suspect interviews.
- Advanced steganalysis on other images in the system.

---

## 📂 Directory Structure (suggested for GitHub)


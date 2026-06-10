# 🚩 CTF Writeups & Technical Logs

![Focus](https://img.shields.io/badge/Focus-Cybersecurity%20%7C%20Forensics-black?style=for-the-badge&logo=kali-linux)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

พื้นที่สำหรับรวบรวมบันทึกการเรียนรู้, การเจาะระบบ (Exploitation), การตรวจพิสูจน์พยานหลักฐานดิจิทัล (Forensics) และคลังสคริปต์สำหรับทดสอบช่องโหว่

Repository นี้เน้นไปที่การบันทึก **กระบวนการคิด (Methodology)** ทำความเข้าใจพฤติกรรมของระบบ และเจาะลึกการทำงานของคำสั่ง เครื่องมือ หรือซอร์สโค้ดอย่างเป็นขั้นเป็นตอน เพื่อใช้สำหรับการทบทวนและพัฒนาทักษะในสายงาน Security

## 🧠 Writeup Methodology

บันทึกทุกไฟล์ในคลังนี้จะถูกจัดโครงสร้างอย่างเป็นระบบ:
*   **🎯 Goal :** กำหนดเป้าหมาย ช่องโหว่ หรือโจทย์หลักที่ต้องแก้ไข
*   **⚙️ The Logic :** อธิบายตรรกะ วิธีคิด และขั้นตอนการทำงาน (ทำไมถึงใช้เทคนิคนี้/คำสั่งนี้)
*   **💎 New Loot :** สรุปเทคนิค Payload หรือคอนเซปต์ใหม่ที่เก็บเกี่ยวได้เพื่อนำไปต่อยอด

## 📁 Repository Structure
```text
.
├── README.md                                # ภาพรวมของคลังและสารบัญ (ไฟล์นี้)
│
├── 🛡️ 01-Web-Exploitation                    # บันทึกการเจาะระบบเว็บแอปพลิเคชัน & CTF Labs
│   ├── SQL-Injection-Scripts/               # สคริปต์สำหรับโจมตีช่องโหว่ SQLi และดึงฐานข้อมูล
│   └── Auth-Bypass-Techniques/              # เทคนิคและสคริปต์การข้ามระบบยืนยันตัวตน
│
├── 🕵️‍♂️ 02-Digital-Forensics                 # ฝั่ง Defensive Security & Investigation
│   └── Network-Forensics/                   # การตรวจทราฟฟิกเครือข่ายและวิเคราะห์ Log
│       └── Wireshark-PCAP-Analysis/         # บันทึกการแกะและตามรอยแพ็กเก็ตจากไฟล์ PCAP
│
├── 🔑 03-Cryptography                       # ศาสตร์การเข้ารหัสและการถอดรหัสข้อมูล
│   └── Hash-Analysis/                       # การวิเคราะห์และแกะรหัสผ่าน (MD5, SHA Cracking)
│
└── 🛠️ 04-Kali-Linux-and-Custom-Toolkit     # คลังแสงและเครื่องมือทุ่นแรงบน Terminal
    ├── Terminal-Cheatsheets/                # รวมคำสั่งลัดและการควบคุม Terminal บน Kali Linux
    └── Payload-Templates/                   # รวมซอร์สโค้ดต้นแบบสำหรับใช้ทดสอบระบบ

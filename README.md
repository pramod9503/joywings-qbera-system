# 📘 Joywings QuestionBook System
 
<div align="center">
 
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Framework](https://img.shields.io/badge/.NET-Framework-purple)
![Application](https://img.shields.io/badge/Desktop-WPF%20%7C%20WinForms-green)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Status](https://img.shields.io/badge/Status-Completed-success)
 
An Offline Examination Platform with Question Authoring, Packaging, Distribution and Licensing System
 
</div>
 
---
 
# 📖 Overview
 
The **Joywings QuestionBook System** is a complete desktop-based examination ecosystem designed for educational institutes, coaching classes, training organizations, and self-learning platforms.
 
The system enables content creators to:
 
- Create question papers
- Package them into distributable exam books
- Distribute them to candidates
- Conduct offline examinations
- Protect premium content using activation keys
 
---
 
# ✨ Key Features
 
## 📝 Question Authoring
 
- Multiple sections
- MCQ questions
- Comprehension-based questions
- Explanations
- Negative marking
- Rich text formatting support
- MS Word integration workflow
 
## 📦 Packaging System
 
- Export question papers
- Bundle multiple tests
- Vendor branding support
- Package logo support
- Package introduction screen
 
## 🖥️ Examination Engine
 
- Offline test environment
- Exam timer
- Section navigation
- Question palette
- Resume interrupted exams
- Auto-save functionality
 
## 📊 Performance Analytics
 
- Exam score history
- Dummy test statistics
- Performance charts
- Question review system
 
## 🔐 Licensing System
 
- Serial number generation
- Activation key generation
- Device binding
- Package integrity validation
 
---
 
# 🏗️ Architecture
 
```text
┌────────────────────┐
│ QuestionBook Editor│
└─────────┬──────────┘
          │
          ▼
     Export .PXT
          │
          ▼
┌────────────────────┐
│ Package Generator  │
└─────────┬──────────┘
          │
          ▼
      Create .PKG
          │
          ▼
┌────────────────────┐
│ QuestionBook Reader│
└─────────┬──────────┘
          │
          ▼
Generate Serial No.
          │
          ▼
┌────────────────────┐
│ QuestionBook       │
│ Activator          │
└─────────┬──────────┘
          │
          ▼
  Activation Key
          │
          ▼
Licensed Package
```
 
---
 
# 📦 Applications
 
## 🧩 QuestionBook Editor (JQE)
 
Creates and edits question papers.
 
### Features
 
- Create question papers
- Edit questions
- Manage answers
- Manage explanations
- Preview exams
- Simulate candidate experience
- Export to .PXT
 
---
 
## 🖥️ QuestionBook Reader (JQR)
 
Used by candidates.
 
### Features
 
- Import QuestionBooks
- Attempt exams
- Practice dummy tests
- Review answers
- Analyze performance
- Track scores
 
---
 
## 🔐 QuestionBook Activator (JQA)
 
License management system.
 
### Features
 
- Generate Joywings IDs
- Generate Activation Keys
- Validate Serial Numbers
- Manage licensed content
 
---
 
# 🔄 Workflow
 
## Content Creator
 
```text
Create Questions
        ↓
Export .PXT
        ↓
Package .PKG
        ↓
Distribute to Students
```
 
## Candidate
 
```text
Import Package
        ↓
Generate Serial Number
        ↓
Receive Activation Key
        ↓
Unlock QuestionBook
        ↓
Attempt Tests
```
 
---
 
# 🔐 Licensing Design
 
The licensing architecture is based on:
 
- Package Identity
- Package Hash
- Joywings ID
- Device Serial Number
 
Result:
 
- Offline activation
- Machine-bound licenses
- Package integrity verification
- Premium content protection
 
---
 
# 📁 File Formats
 
| Extension | Description |
|------------|-------------|
| .qst | Question Paper |
| .ans | Answer Key |
| .exp | Explanations |
| .pxt | Exported Question Paper |
| .pkg | QuestionBook Package |
| .hash | Package Integrity File |
| .vpr | Vendor Profile |
 
---
 
# 🛠 Technologies
 
### Development
 
- Visual Basic 6 (Earlier versions)
- C#
- .NET Framework
- Windows Desktop Development
 
### Components
 
- Rich Text Processing
- File Packaging System
- Cryptographic Hashing
- Offline Licensing Engine
  
# 🎯 Real-World Problems Solved
 
✅ Offline Examination Delivery
 
✅ Premium Question Bank Protection
 
✅ Coaching Institute Distribution Model
 
✅ Candidate Performance Tracking
 
✅ Exam Packaging and Distribution
 
✅ License-Controlled Educational Content
 
---
 
# 💡 Technical Highlights
 
This project demonstrates experience in:
 
- Desktop Application Development
- Product Design
- Licensing Systems
- Data Packaging
- File Format Design
- Rich Text Processing
- Educational Software Development
- User Experience Design
- Offline-first Architecture
 
---
 
# 👨‍💻 About the Author
 
### Pramod R. Gajbhiye
 
Independent Software Developer
 
Areas of Interest:
 
- .NET Development
- Desktop Applications
- Educational Software
- SaaS Products
- WPF
- ASP.NET Core
 
---
 
# ⭐ Why This Project Matters
 
Unlike a simple CRUD application, this project includes:
 
- Content authoring tools
- Examination engine
- Packaging framework
- Licensing system
- Activation workflow
- Analytics dashboard
 
making it a complete end-to-end software product rather than a standalone application.
 
---
 
# 📸 Screenshots
 
## QuestionBook Reader
 
![Joywings QuestionBook Reader Screenshot](screenshots/Joywings%20QuestionBook%20Reader%20Screenshots/Welcome.png)
 
---
 
## QuestionBook Editor
### Opening Window 
![Joywings QuestionBook Editor New Menu](screenshots/Joywings%20QuestionBook%20Editor%20Screenshots/New%20Menu.png)

### Opened Question Paper
![Joywings QuestionBook Editor Question Paper](screenshots/Joywings%20QuestionBook%20Editor%20Screenshots/Simulate%20Menu.png)
 
---
 
## QuestionBook Activator
 ![Joywings QuestionBook Activator Screenshot](screenshots/Joywings%20QuestionBook%20Activator%20Screenshots/File%20Menu.png)
 
---
 
# 📄 License
 
This repository is published for portfolio and demonstration purposes.
 
All rights reserved by the author.

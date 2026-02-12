# 🚀 DocuSplit Pro — Automated Document Splitter & Quiz Engine

DocuSplit Pro is a Streamlit application that automates document processing workflows including splitting documents, generating PDFs, encrypting files, and creating multiple randomized combinations.

Originally built to power a real-world technical competition, this tool transforms complex manual preparation into a fast, reliable, and scalable automated pipeline.

---

## Live Demo
https://cipherquiz.streamlit.app/
---

## Problem It Solves

Preparing multiple encrypted question sets manually is:

- Time-consuming  
- Error-prone  
- Hard to scale  
- Difficult to verify  

DocuSplit Pro automates the entire workflow in a few clicks.

---

## Features

### Core Engine
- Upload Word documents (.docx)
- Pattern-based document splitting
- Automatic PDF generation
- Batch downloads (ZIP)
- Multiple shuffled combinations (5–30)
- Config export/import system
- Input validation & error handling

### Encryption Modes
- No encryption
- Same password for all files
- Different password per section
- Sequential unlock flow

### Quiz Mode
- Grouped difficulty shuffling (Easy / Medium / Hard)
- Sequential answer unlocking
- Automatic answer key generation
- Verification checklist generator

---

## Real-World Use Case

Built for a live technical event where:

> Solve Question 1 → Answer unlocks Question 2 → Continue until final puzzle.

The application handled:

- file generation
- encryption logic
- shuffled combinations
- answer verification

Ensuring fairness, speed, and reliability for all participants.

---

## Tech Stack

- Python
- Streamlit
- PyPDF2
- ReportLab
- python-docx
- Regex processing
- Dataclasses architecture

---

## Installation (Local)

```bash
git clone https://github.com/aviral-workprojects/CipherQuiz.git
cd CipherQuiz
pip install -r requirements.txt
streamlit run app.py
```

---

## Version Timeline

| Version | Features |
|-------|---------|
v1.0 | Basic splitting + PDFs |
v2.0 | Encryption system |
v3.0 | Multiple combinations |
v4.0 | Quiz mode |
v5.0 | Production ready + monitoring |

---

## Architecture Highlights

- Modular class-based design
- Centralized error handler
- Configuration manager
- Session-state workflow engine
- Scalable combination generator

---

## Why This Project Matters

This project demonstrates:

- real-world problem solving
- automation design
- scalable architecture
- UI/UX thinking
- deployment readiness

It’s not just code — it’s a complete working system.

---

## Author

**Aviral Pratap Singh**

---

## Support

If you like this project, consider starring ⭐ the repository!

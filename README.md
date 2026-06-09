# 🏢 ATS Resume Portal — Enterprise Scan

A browser-based tool that simulates how large companies' Applicant Tracking Systems (ATS) — like Workday, Taleo, and Greenhouse — screen a resume against a job description. It returns an instant match score, a shortlist verdict, and a clear **why-it-fails** and **what-to-fix** for every check.

> Most resumes are filtered by software before a recruiter ever sees them. This tool shows you what that software sees — and how to get past it.

---

## ✨ Features

- **Instant ATS match score** with a Shortlisted / Borderline / Rejected verdict
- **10 enterprise checks**, each with an explanation and a fix:
  - Hard-skill & keyword coverage
  - Job-title alignment
  - Years of experience (reads stated figures like "2+ years" and date ranges; ignores education duration)
  - Education & qualifications
  - Contact info & parseability
  - Standard section headings
  - Quantified impact / metrics
  - Strong action verbs
  - Length & file parseability
- **ATS profile selector** (Generic, Workday, Greenhouse, Taleo) — each weights checks differently
- **Prioritized fix plan** — ranks every gap by impact
- **100% private** — runs entirely in your browser; no resume data is uploaded to any server

---

## 🚀 How to use

**Option 1 — Live demo**
Open: `https://praveen-rao123.github.io/ATS_Resume_portal/`

**Option 2 — Run locally**
1. Download `index.html` from this repository.
2. Double-click it to open in any modern browser (Chrome, Edge, Firefox).
3. No installation, no server, no internet dependency for your data.

**Then:**
1. Enter the candidate name and target job role.
2. Choose the target-company ATS profile.
3. Upload the resume (PDF, DOCX, or TXT).
4. Paste the full job description.
5. Click **Run Enterprise ATS Scan** and review the score, checks, and fix plan.

---

## 🛠️ Tech stack

- Single self-contained **HTML + CSS + JavaScript** file — no build step, no dependencies to install
- **pdf.js** — client-side PDF text extraction
- **mammoth.js** — client-side DOCX text extraction
- Custom keyword-extraction and scoring engine that mirrors real ATS ranking logic

---

## 🔒 Privacy

All parsing and scoring happen locally in your browser. Your resume and job description never leave your device.

---

## 📌 Notes

This is a faithful *simulation* of ATS screening logic, not a connection to any company's actual system. Use the suggestions to improve a resume with information that is truthfully yours.

---

## 👤 Author

**Praveen Rao G** · Embedded HW/SW Engineer

© Praveen Rao G. All rights reserved.

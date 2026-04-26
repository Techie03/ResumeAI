🧠 ResumeAI — Qwen3-4B SLM | Groq-Powered Resume Optimizer

ResumeAI is a lightweight, single-file web app that tailors your resume 
to any job description in real time using the Groq API (llama-3.3-70b-versatile).

Upload your resume (PDF, DOCX, or TXT), paste a job description, select 
a target schema, and get back a structured JSON output — instantly.

✦ Features
  - 📄 Resume upload support — PDF (via PDF.js), DOCX, TXT
  - 🎯 Job-description-aware tailoring — not generic, not hardcoded
  - 🗂 4 output schemas — Full Resume, Skills Only, Experience Bullets, Summary
  - ⚡ Groq inference — ultra-low latency via llama-3.3-70b-versatile
  - 📊 Live metrics — latency, skill coverage, JSON validity, tokens/sec
  - ⬇ Download output — export tailored resume as .txt
  - 🔑 Bring your own Groq API key — runs 100% in the browser, no backend

✦ Tech Stack
  - Vanilla HTML/CSS/JS — zero dependencies, single file
  - Groq API (OpenAI-compatible) — llama-3.3-70b-versatile
  - PDF.js — client-side PDF text extraction

✦ How to Use
  1. Get a free API key at https://console.groq.com/keys
  2. Open index.html in any browser
  3. Paste your Groq key, upload your resume, add a job description
  4. Hit Run — get tailored output in seconds

Built for DTSC 5082 · Group 9 · Shark Tank Pitch

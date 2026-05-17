🧠 ResumeAI — Qwen3-4B SLM | Groq-Powered Resume Optimizer

ResumeAI is a lightweight, deployment-ready web application that demonstrates how a low-cost Small Language Model workflow can deliver practical resume optimization without relying on expensive large-scale inference.

The application allows users to upload a resume in PDF, DOCX, or TXT format, paste a target job description, choose a structured output schema, and instantly generate a tailored JSON response. Built with the Groq API using llama-3.3-70b-versatile for deployment demonstration, the system showcases how resume-job matching, skill extraction, and structured candidate profiling can be automated in a fast, scalable, and recruiter-friendly workflow.

This project was designed to highlight the deployment value of cost-efficient SLM-based systems, proving that practical AI tools can be built with lower inference cost, faster response time, and clear structured outputs suitable for real-world hiring and resume screening use cases.

https://github.com/Techie03/Low-Cost-Resume-Optimization-via-Distillation-of-Large-Language-Model-Behavior-into-a-Fine-Tuned-SLM

https://techie03.github.io/Low-Cost-Resume-Optimization-via-Distillation-of-Large-Language-Model-Behavior-into-a-Fine-Tuned-SLM/Model_Deployment.html

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

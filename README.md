PDFnoted — AI Contract Review & Free PDF Tools (Runs 100% in Your Browser)
Product Hunt
Chrome Extension
Edge Add-on
Website
PDFnoted is a free, browser-based PDF workspace. Every tool runs client-side — your files never leave your device. Beyond the usual edit/convert toolbox, it ships an AI compliance review engine that checks contracts and policy documents against 174+ regulations across 11 industries and 3 jurisdictions (EU, US, China), then cites the specific legal provision behind each flagged risk.
Looking for a specific job? Jump straight there:
- Remove a watermark from a PDF → AI Watermark Remover
- Find and clear hidden watermarks / faint stamps → Hidden Watermark Detection
- Strip metadata, comments, attachments and hidden objects → PDF Sanitizer
- Locate personal data before you share → Sensitive Data Detection & Masking
- Check a contract clause by clause → AI Contract Review
- Run a pre-delivery compliance scan → Compliance Check
Why it exists
Most "free PDF" sites upload your file to a server you know nothing about. That's fine for a meme, not for a signed NDA, a medical record, or a contract draft. PDFnoted does the work in the browser tab, so there is no upload step to trust and no file retention policy to read.
The second gap is review. Plenty of tools will edit a PDF. Almost none will read it and tell you that clause 7.2 puts your personal data outside what GDPR Art. 44 allows. That's the part PDFnoted automates.
The compliance engine
Upload a contract or policy document → the engine parses it → flags risky clauses → cites the governing provision → suggests concrete redlines.
What it checks
Domain
Coverage
AI regulation
EU AI Act (2024), China Generative AI Interim Measures, US TAKE IT DOWN Act (2025)
Cross-border data
GDPR Arts. 44–49, PIPL Arts. 38–43, China Data Export Security Assessment
ESG reporting
EU CSRD (2024), ISSB Standards, China Sustainable Disclosure Standards (2024)
How it works: 14,901 parsed legal rules, retrieved in four passes — exact match → TF-IDF → citation expansion → authority reranking. Every flag carries a citation you can verify, not a confidence score you have to take on faith.
→ Try it: AI Contract Review
The toolbox (27 tools, no upload)
Clean — AI watermark removal · hidden watermark & faint stamp cleanup · PDF Clean (all hidden objects) · metadata / comment / attachment stripping · header & footer removal · stamp & seal removal
Before you send — sensitive data detection & masking · pre-delivery compliance scan · 8-point pre-sharing checklist
Convert — to Word · to Excel · to PPT · to JPG · to PNG / Text / Markdown
Organize — merge · split · reorder · rotate · crop · delete pages
Secure — password protect · unlock · e-sign · flatten
Professional — watermark · page numbers · headers/footers · Bates numbering
Advanced — OCR · PDF compare · AI translate · image → PDF · extract images
→ Full list: PDF Tools
Editor + AI polish
Click text to edit it inline, drop in images, then let AI polish, proofread, or translate the result. Exports embed CJK fonts (Source Han Sans), so Chinese/Japanese/Korean text doesn't turn into boxes downstream.
→ PDF Editor
Privacy model
Files are processed locally via PDF.js, pdf-lib and Fabric.js. Nothing is uploaded for the browser tools. The AI review features send only the extracted text needed to answer — and you can see exactly which page goes out before you confirm.
Install
Platform
Link
Web (no install)
https://pdfnoted.com
Chrome
Chrome Web Store
Microsoft Edge
Edge Add-ons
iOS / macOS
App Store
Research foundation
The retrieval and ranking approach builds on published work — full citations on the Research References page:
- Zhang et al. (2024) — Document Parsing Unveiled
- Adhikari & Agarwal (2024) — PDF Parsing Tools Comparison
- Papagiannidis et al. (2025) — Responsible AI Governance
- ISO 32000-2:2020 (PDF 2.0) · ISO 37301:2021 (Compliance Management)
Also open
- llms.txt — structured summary for AI crawlers
- Methodology — how the risk scoring works
Maker
Hui Tian — full-stack engineer working on document AI and compliance automation.
- GitHub: github.com/TianHuiIsMe
- Product Hunt: @hui_tian
License
This repository is a project showcase. Source for the browser extension and server components is proprietary. The compliance knowledge base follows the ISO 37301:2021 framework.
PDFnoted © 2025–2026. Built with PDF.js, pdf-lib, Fabric.js and qwen-flash.

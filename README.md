# free-ats-resume-checker

🎓 GradATS — Free Student ATS Resume Checker & AI Optimizer

GradATS is a 100% free, zero-paywall, client-side Applicant Tracking System (ATS) resume scanner, X-Y-Z bullet rewriter, and student career kit built specifically for college students and new graduates.

🔗 Live Demo: https://<your-github-username>.github.io/<repository-name>/ (Replace with your GitHub Pages URL)

✨ Key Features

📄 Multi-Format Client-Side Parsing: Drag & drop .PDF (via PDF.js), .DOCX (via Mammoth.js), or .TXT resumes—or test immediately using built-in SWE Intern, Cyber SOC Intern, and Data Analyst student presets.

📊 4-Pillar Weighted ATS Diagnostic Engine (0–100):

Keyword & JD Alignment (40%): Splits missing job description keywords into Hard Skills & Tools vs. Domain Concepts & Practices, with 1-click + Inject to Skills pills.

Quantified Impact & Action Verbs (25%): Flags passive starter phrases ("Responsible for", "Worked on") and rewards measurable metrics (%, latency, scale).

Student Structure & Contact Hygiene (20%): Checks for Email, Phone, GitHub/LinkedIn URLs, GPA/Graduation Date, and whether EDUCATION is placed near the top.

ATS Parsability & Length (15%): Enforces the 1-page student word count sweet spot (350–650 words), removes first-person pronouns (I, my, our), and verifies single-column hygiene.

🤖 Dual-Mode AI Career Suite (Zero Setup Required):

Built-in Instant Local AI Mode: Works 100% offline and on public GitHub Pages with zero API keys required.

Optional Bring-Your-Own-Key (BYOK) Gemini Mode: Click Local AI Ready in the top navbar to optionally add your own free Google AI Studio Gemini API key for live LLM rewrites.

🧰 6-Tab Student Career Toolkit:

Diagnostics & Keywords: Categorized skill gaps + prioritized point-gain checklist.

Google X-Y-Z Rewriter: Rewrites passive bullets using "Accomplished [X] as measured by [Y], by doing [Z]" with 1-click replacement.

ATS Parser X-Ray: Simulates how Workday, Greenhouse, and Lever parse your contact info, skills array, and education block.

Cover Letter & Cold Email: Generates a tailored 3-paragraph cover letter and a high-reply-rate recruiter outreach note.

Mock Interview Prep: Generates 5 JD- and project-specific interview questions with collapsible STAR answer strategies.

Heatmap & Harvard/Jake's PDF Builder: Color-codes every line of your resume and exports a clean, single-column machine-readable ATS PDF via browser print.

↩️ Version History & Auto-Save: Experiment safely with an Undo stack and automatic browser localStorage draft saving.

🔒 Privacy & Architecture

Zero Backend / Zero Data Collection: GradATS runs entirely inside your browser as a single self-contained index.html file.

Your Resume Never Leaves Your Device: PDF and Word parsing happen locally in JavaScript. If you choose to enter an optional Gemini API key, it is stored strictly in your browser's localStorage and sent only to Google's official Generative Language API (generativelanguage.googleapis.com).

🚀 Deploy Your Own Copy on GitHub Pages

Fork or clone this repository (or upload index.html and README.md to a new public GitHub repository).

Open your repository's Settings $\rightarrow$ Pages.

Under Build and deployment $\rightarrow$ Source, choose Deploy from a branch.

Select branch main and folder / (root), then click Save.

Your site will be live at https://<your-username>.github.io/<repo-name>/ within 60 seconds!

🛠️ Tech Stack

UI & Styling: HTML5, Tailwind CSS, Lucide Icons

Document Parsers: PDF.js (3.11.174), Mammoth.js (1.6.0)

AI Engine: Built-in Deterministic Heuristic Engine + Optional Google Gemini API (gemini-3.5-flash-lite / gemini-2.5-flash-lite)

📄 License

Distributed under the MIT License. Free for students, university career centers, and open-source contributors.

# Vrajkumar Patel

**AI Automation & Full-Stack Developer**

Python · FastAPI · Django · React · TypeScript · PostgreSQL · LLM APIs (Groq, Gemini) · REST APIs

I build production web applications and AI-integrated systems: booking platforms, AI agents with retrieval-augmented memory, and data pipelines. Founder/full-stack developer at Stayvoo; previously a full-stack developer intern at SquareOne.

[LinkedIn](https://www.linkedin.com/in/vraj-patel-dev/) · [Email](mailto:vp431030@gmail.com)

---

### About

CS senior at National Louis University (AI concentration), graduating September 2026.

Founder and full-stack developer of Stayvoo, a hotel booking platform for extended-stay and group reservations — its FastAPI/PostgreSQL backend, security hardening (IDOR prevention, rate limiting, audit logging), and Stripe/Twilio/SendGrid integrations. Previously a full-stack developer intern at SquareOne, where I built the AI-assisted resume/cover-letter generation and job-application backend for CareerFlow.

---

### Featured Projects

**[Stayvoo](https://github.com/vrajkumarpatel/Stayvoo)**
Hotel booking platform (FastAPI, React, PostgreSQL/Supabase) with IDOR-safe guest access via per-guest tokens, rate limiting, audit logging, and a Playwright e2e suite covering the booking/payment flow, admin auth, and known attack surface (IDOR, XSS storage, token expiry). Deployed on Railway + Vercel, integrated with Stripe, Twilio, and SendGrid.

**[LeadTriage](https://github.com/vrajkumarpatel/LeadTriage)**
AI-powered lead-qualification automation: a webhook intake pipeline (optionally fronted by n8n) into a FastAPI backend that scores and classifies leads via Groq (with a deterministic mock fallback when no API key is set), tracks every workflow run with retry/audit-log history, and surfaces it all in a React dashboard.

**[ARIA](https://github.com/vrajkumarpatel/ARIA)**
A memory/retrieval backend for an AI study companion: hybrid BM25 + vector + knowledge-graph search over a personal notes vault, a rate-limited Groq LLM proxy with retry/backoff, and Google Calendar integration. Drives a third-party Live2D/TTS avatar engine ([fagenorn/handcrafted-persona-engine](https://github.com/fagenorn/handcrafted-persona-engine)) that I configured and integrated — the avatar/voice layer itself is not my code.

**[CareerFlow](https://github.com/vrajkumarpatel/CareerFlow)**
Job-search platform (Django REST Framework, React, PostgreSQL) built during my internship at SquareOne. My contributions: job/application management backend, AI-powered resume and cover-letter generation via Gemini, and the deployment migration to Render/Supabase/Vercel. The admin UI and signup flow were built by teammates.

**[IDscnr](https://github.com/vrajkumarpatel/ID_Scnr)**
ID/passport scanning tool for hospitality guest check-in: AAMVA barcode parsing with OCR fallback, AES-256-GCM encrypted local storage, and fuzzy do-not-rent list matching.

**[Customer Segmentation Dashboard](https://github.com/vrajkumarpatel/customer-segmentation-dashboard)**
RFM analysis and K-Means clustering on e-commerce transaction data, with elbow- and silhouette-based cluster selection and a Streamlit dashboard.

**[Portfolio Website](https://github.com/vrajkumarpatel/Portfolio_Website)**
Personal site at [vrajpatel.info](https://vrajpatel.info/) — Next.js, with a 3D interactive skills keyboard (Spline) and GSAP/Framer Motion animation throughout.

**[Gun Violence Analytics](https://github.com/vrajkumarpatel/gun-violence-dashboard)**
ETL and analysis pipeline correlating Chicago crime data with socioeconomic indicators, with an interpretable, explicitly correlational classification model.

More detail on each: [PORTFOLIO-INDEX.md](PORTFOLIO-INDEX.md) · [TECHNOLOGY-MATRIX.md](TECHNOLOGY-MATRIX.md)

---

### Skills

**Languages:** Python, Java, JavaScript, TypeScript, C#, SQL, HTML, CSS, Bash/Shell
**Backend:** FastAPI, Django REST Framework, Node.js, Pydantic, REST API design, token-based auth
**Frontend:** React, Next.js, Vite, Tailwind CSS
**Databases:** PostgreSQL, MySQL, SQLite
**AI/ML:** LLM API integration (Groq, Gemini), retrieval-augmented generation, prompt engineering, LlamaIndex, vector databases, TensorFlow, scikit-learn, NumPy, pandas
**Security:** OWASP principles, authentication & authorization, IDOR prevention, rate limiting, audit logging, PII protection
**Testing:** Playwright, automated/manual test design and debugging
**Infra/Tools:** Git, GitHub, Docker, AWS, Supabase, Railway, Render, Vercel, Netlify, Postman, Linux, CI/CD, n8n
**APIs/Integrations:** Stripe, Twilio, SendGrid, Google Calendar OAuth2

---

Contact: [LinkedIn](https://www.linkedin.com/in/vraj-patel-dev/) · vp431030@gmail.com

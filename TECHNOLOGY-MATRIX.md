# Technology Matrix

Technologies actually verified in each project's code — not aspirational. "Third-party" means integrated/configured, not authored.

| Technology | Stayvoo | ARIA | CareerFlow | IDscnr | Customer Segmentation | Gun Violence | Portfolio Website | LeadTriage |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Python | | ✅ | | ✅ | ✅ | ✅ | | ✅ |
| FastAPI | ✅ | | | ✅ | | | | ✅ |
| Django REST Framework | | | ✅ | | | | | |
| SQLAlchemy | ✅ | | | ✅ | | | | ✅ |
| React + TypeScript | ✅ | | ✅ | ✅ | | | ✅ | ✅ |
| Next.js | | | | | | | ✅ | |
| PostgreSQL | ✅ (Supabase) | | ✅ (Supabase) | | | | | ✅ |
| SQLite | | | | ✅ | | | | ✅ (fallback) |
| Groq API | | ✅ | | | | | | ✅ |
| Google Gemini API | | | ✅ | | | | | |
| Stripe | ✅ | | | | | | | |
| Twilio | ✅ | | | | | | | |
| SendGrid | ✅ | | | | | | | |
| Tesseract OCR | | | | ✅ | | | | |
| AES-256-GCM encryption | | | | ✅ | | | | |
| BM25 / vector / graph retrieval | | ✅ | | | | | | |
| Neo4j | | ✅ | | | | | | |
| Google Calendar API (OAuth2) | | ✅ | | | | | | |
| Live2D / TTS avatar engine | | ✅ (third-party) | | | | | | |
| Playwright (e2e tests) | ✅ | | | | | | | |
| pandas / scikit-learn | | | | | ✅ | ✅ | | |
| Streamlit | | | | | ✅ | ✅ | | |
| Dash / Plotly | | | | | | ✅ | | |
| Railway | ✅ | | | | | | | |
| Render | | | ✅ | | | | | |
| Vercel | ✅ | | ✅ | | | | | |
| Netlify | | | | | | | ✅ | |
| AWS ECS | | | ✅ (built, not current production) | | | | | |
| Docker Compose | | | ✅ (local dev only) | | | | | ✅ (API + Postgres) |
| GSAP / Framer Motion / Spline | | | | | | | ✅ | |
| WIA scanner / PMS autofill | | | | ✅ | | | | |
| n8n | | | | | | | | ✅ (optional orchestration layer) |
| Alembic (migrations) | | | | | | | | ✅ |
| JWT auth | | | | | | | | ✅ |

## Notes

- **ARIA's Live2D/TTS avatar** is [fagenorn/handcrafted-persona-engine](https://github.com/fagenorn/handcrafted-persona-engine), a third-party C#/.NET 9 project — configured, GPU-tuned, and integrated, not authored.
- **n8n** is real and working in LeadTriage (three importable workflow definitions), but the app functions standalone without it — n8n fronts the same `/api/v1/leads` endpoint rather than being a hard dependency. It still doesn't appear in Stayvoo despite earlier planning docs mentioning it there.
- **AWS** appears only for CareerFlow, and only as historical work: a real ECS deployment path (task definitions + a GitHub Actions workflow) was built during development, then the team moved to Render for the free tier before it ever went live. It's genuine infrastructure-as-code, just not what's currently serving traffic.
- **Docker** is local-dev-only tooling for CareerFlow, but is the actual verified-working local deployment path for LeadTriage (`docker compose up` runs the full API + Postgres stack, migrations included).

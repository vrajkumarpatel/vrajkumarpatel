# Technology Matrix

Technologies actually verified in each project's code — not aspirational. "Third-party" means integrated/configured, not authored.

| Technology | Stayvoo | ARIA | CareerFlow | IDscnr | Customer Segmentation | Gun Violence | Portfolio Website |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Python | | ✅ | | ✅ | ✅ | ✅ | |
| FastAPI | ✅ | | | ✅ | | | |
| Django REST Framework | | | ✅ | | | | |
| SQLAlchemy | ✅ | | | ✅ | | | |
| React + TypeScript | ✅ | | ✅ | ✅ | | | ✅ |
| Next.js | | | | | | | ✅ |
| PostgreSQL | ✅ (Supabase) | | ✅ (Supabase) | | | | |
| SQLite | | | | ✅ | | | |
| Groq API | | ✅ | | | | | |
| Google Gemini API | | | ✅ | | | | |
| Stripe | ✅ | | | | | | |
| Twilio | ✅ | | | | | | |
| SendGrid | ✅ | | | | | | |
| Tesseract OCR | | | | ✅ | | | |
| AES-256-GCM encryption | | | | ✅ | | | |
| BM25 / vector / graph retrieval | | ✅ | | | | | |
| Neo4j | | ✅ | | | | | |
| Google Calendar API (OAuth2) | | ✅ | | | | | |
| Live2D / TTS avatar engine | | ✅ (third-party) | | | | | |
| Playwright (e2e tests) | ✅ | | | | | | |
| pandas / scikit-learn | | | | | ✅ | ✅ | |
| Streamlit | | | | | ✅ | ✅ | |
| Dash / Plotly | | | | | | ✅ | |
| Railway | ✅ | | | | | | |
| Render | | | ✅ | | | | |
| Vercel | ✅ | | ✅ | | | | |
| Netlify | | | | | | | ✅ |
| AWS ECS | | | ✅ (built, not current production) | | | | |
| Docker Compose | | | ✅ (local dev only) | | | | |
| GSAP / Framer Motion / Spline | | | | | | | ✅ |
| WIA scanner / PMS autofill | | | | ✅ | | | |

## Notes

- **ARIA's Live2D/TTS avatar** is [fagenorn/handcrafted-persona-engine](https://github.com/fagenorn/handcrafted-persona-engine), a third-party C#/.NET 9 project — configured, GPU-tuned, and integrated, not authored.
- **n8n** does not currently appear in any of these projects' code, despite earlier planning docs mentioning it for Stayvoo. It's planned for FlowPilot AI (Stage 2).
- **AWS** appears only for CareerFlow, and only as historical work: a real ECS deployment path (task definitions + a GitHub Actions workflow) was built during development, then the team moved to Render for the free tier before it ever went live. It's genuine infrastructure-as-code, just not what's currently serving traffic.
- **Docker** exists as local-dev tooling for CareerFlow (`docker-compose.yml`/`docker-compose.prod.yml`) — not used for its actual Render deployment. No other project here has a working Dockerfile.

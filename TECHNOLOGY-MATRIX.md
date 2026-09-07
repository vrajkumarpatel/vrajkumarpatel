# Technology Matrix

Technologies actually verified in each project's code — not aspirational. "Third-party" means integrated/configured, not authored.

| Technology | Stayvoo | ARIA | CareerFlow | IDscnr | Customer Segmentation | Gun Violence |
|---|:---:|:---:|:---:|:---:|:---:|:---:|
| Python | | ✅ | | ✅ | ✅ | ✅ |
| FastAPI | ✅ | | | ✅ | | |
| Django REST Framework | | | ✅ | | | |
| SQLAlchemy | ✅ | | | ✅ | | |
| React + TypeScript | ✅ | | ✅ | ✅ | | |
| PostgreSQL | ✅ (Supabase) | | ✅ (Supabase) | | | |
| SQLite | | | | ✅ | | |
| Groq API | | ✅ | | | | |
| Google Gemini API | | | ✅ | | | |
| Stripe | ✅ | | | | | |
| Twilio | ✅ | | | | | |
| SendGrid | ✅ | | | | | |
| Tesseract OCR | | | | ✅ | | |
| AES-256-GCM encryption | | | | ✅ | | |
| BM25 / vector / graph retrieval | | ✅ | | | | |
| Neo4j | | ✅ | | | | |
| Google Calendar API (OAuth2) | | ✅ | | | | |
| Live2D / TTS avatar engine | | ✅ (third-party) | | | | |
| Playwright (e2e tests) | ✅ | | | | | |
| pandas / scikit-learn | | | | | ✅ | ✅ |
| Streamlit | | | | | ✅ | ✅ |
| Dash / Plotly | | | | | | ✅ |
| Railway | ✅ | | | | | |
| Render | | | ✅ | | | |
| Vercel | ✅ | | ✅ | | | |
| WIA scanner / PMS autofill | | | | ✅ | | |

## Notes

- **ARIA's Live2D/TTS avatar** is [fagenorn/handcrafted-persona-engine](https://github.com/fagenorn/handcrafted-persona-engine), a third-party C#/.NET 9 project — configured, GPU-tuned, and integrated, not authored.
- **n8n** does not currently appear in any of these projects' code, despite earlier planning docs mentioning it for Stayvoo. It's planned for FlowPilot AI (Stage 2).
- **Docker** and **AWS** are not currently used in any live deployment — CareerFlow explored an AWS ECS path early on and moved to Render; none of these projects ship with a working Dockerfile at present.

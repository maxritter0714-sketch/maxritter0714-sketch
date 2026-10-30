# Hi, I'm Max 👋

Business Informatics student @ HS Offenburg (6th semester)
---

## 🚀 Projects

### [portfolio-email-agent](https://github.com/maxritter0714-sketch/portfolio-email-agent) — Automated Portfolio Reporting
Self-hosted agent that generates and emails a fortnightly editorial-style portfolio report, scheduled via GitHub Actions.

- **Stack:** Python · yfinance · NewsAPI · Claude API · matplotlib · pytest
- **Features:** Finanzfluss CSV import with automated ISIN resolution (OpenFIGI) · 
  Sharpe/Sortino/Calmar/VaR/CVaR risk metrics · momentum scoring · ETF look-through exposure ·
  AI-filtered news relevance · Claude-generated analysis & actionable recommendations
- Runs fully in the cloud with no local machine required; holdings data kept private via a separate data repo

### [int8-quantization-pytorch9](https://github.com/maxritter0714-sketch/int8-quantization-pytorch) — INT8 quantization benchmarks on CPU

- **Stack**: Python · PyTorch · Hugging Face · pytest · GitHub Actions
- **Methods**: dynamic & static PTQ · QAT · KV-cache INT8
- **Results**: DistilBERT 255 → 132 MB · 1.7x lower latency · −1.1 pp accuracy; KV cache ~7x faster generation

### OnDA — Sign Language Interpreter Booking Platform *(private)*
Cross-platform mobile app (iOS & Android) that connects deaf and hard-of-hearing 
users with DGS interpreters for real life appointments or in app video call sessions.

- **Stack:** React Native/Expo · Supabase (RLS, Realtime) · LiveKit (self-hosted, DSGVO-compliant infra)
- Live in closed testing on Google Play & TestFlight
- Architected with GDPR Art. 9 in mind (sensitive disability/health data)
---

📫 maxritter0714@gmail.com

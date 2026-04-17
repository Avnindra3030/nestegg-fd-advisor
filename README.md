# 🪺 NestEgg — AI-Powered FD Rate Advisor
### Blostem · Hack to the Future 2026 | Avnindra Kumar Singh

---

## 🎯 The Problem

Finding the best Fixed Deposit in India is broken.

Investors manually visit 10+ bank websites, don't understand DICGC insurance limits, miss senior citizen bonuses, and often end up in the wrong product for their risk profile. There is no single intelligent layer that understands *your* goals and matches them to the right FD — instantly.

---

## 💡 The Solution

**NestEgg** is a conversational AI advisor embedded inside Blostem's banking infrastructure. A user simply says:

> *"I have ₹2 lakhs for 1 year, I'm 62 years old, safety first"*

NestEgg instantly:
- Compares rates across all Blostem partner banks in real time
- Applies senior citizen bonus rates automatically (+0.25% to +0.75%)
- Flags DICGC ₹5 lakh insurance limits and suggests bank-splitting strategy
- Calculates exact maturity returns for the given amount and tenure
- Recommends the single best FD with a clear, plain-language reason why

---

## 🔗 Why It Fits Blostem Perfectly

Blostem's SDK removes the **technical barrier** to FD integration for fintechs — one API call to go live with 10+ banks in 7 days.

NestEgg removes the **knowledge barrier** for end investors — one conversation to find the best FD for their exact situation.

The two layers together make FD investing truly frictionless: from bank API → fintech integration → customer decision. NestEgg is the missing consumer-facing intelligence layer on top of Blostem's infrastructure.

---

## ✨ Key Features

- **Natural language queries** — "best FD for ₹5L, 2 years, max safety"
- **Real-time rate comparison** across SFBs, NBFCs, and commercial banks
- **Exact return calculator** — maturity amount shown for any input
- **DICGC insurance guidance** — auto-suggests bank splitting for amounts > ₹5L
- **Senior citizen detection** — applies bonus rates when user is 60+
- **TDS advisory** — explains Form 15G/15H eligibility automatically
- **Conversational memory** — full context retained across the session
- **Quick prompt chips** — one-tap common investor scenarios

---

## 🏦 Banks & Rates Covered

| Bank | Type | 1yr Rate | DICGC |
|---|---|---|---|
| Suryoday Small Finance Bank | SFB | 9.5% | ✅ Yes |
| Unity Small Finance Bank | SFB | 9.5% | ✅ Yes |
| Utkarsh Small Finance Bank | SFB | 9.1% | ✅ Yes |
| Shivalik Small Finance Bank | SFB | 8.9% | ✅ Yes |
| Shriram Finance | NBFC | 8.75% | ❌ No |
| Bajaj Finance | NBFC | 8.6% | ❌ No |
| Mahindra Finance | NBFC | 8.3% | ❌ No |
| HDFC Bank | Commercial | 7.1% | ✅ Yes |
| ICICI Bank | Commercial | 7.1% | ✅ Yes |
| SBI | Commercial | 6.8% | ✅ Yes |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| AI Reasoning | Anthropic Claude API (claude-sonnet) |
| Bank Rate Data | Blostem FD/RD Partner Bank API |
| Frontend | Vanilla HTML, CSS, JavaScript |
| Fonts | Sora + DM Serif Display (Google Fonts) |
| Deployment | GitHub Pages (zero-config) |

---

## 🚀 How to Run Locally

1. Clone this repo
2. Open `index.html` in any browser
3. Add your Anthropic API key inside the `fetch()` headers in the script section
4. Start asking questions

No npm, no build step, no server. Just open and run.

---

## 📱 Sample Conversations

**User:** I have ₹2 lakhs to invest for 1 year. Max returns please.
**NestEgg:** Best pick is Suryoday SFB at 9.5% — your ₹2L becomes ₹2,19,000 at maturity. Fully DICGC insured, RBI regulated...

**User:** I'm 65 years old with ₹5 lakhs. Safety is my priority.
**NestEgg:** For senior citizens, Utkarsh SFB gives 9.85% (base 9.1% + 0.75% senior bonus). Your ₹5L is fully insured under DICGC...

**User:** Should I split ₹10 lakhs across banks?
**NestEgg:** Yes, absolutely. DICGC covers only ₹5L per bank. Split across Suryoday + Unity for full coverage at 9.5% each...

---

## 📈 Real-World Impact

- Reduces FD decision time from **hours → seconds**
- Increases conversion rates for Blostem's fintech partners
- Directly addresses India's **₹180 lakh crore** FD market
- Makes financial literacy accessible to first-time investors

---

## 👤 Team

**Avnindra Kumar Singh**
Hack to the Future 2026 — Blostem AI Builder Hackathon

---

*FD rates shown are illustrative and based on publicly available data as of April 2026. Always verify current rates with the respective bank before investing.*

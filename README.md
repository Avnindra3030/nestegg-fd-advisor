# 🪺 NestEgg — AI-Powered FD Rate Advisor
> Built for Blostem · Hack to the Future 2026

## What It Does
NestEgg is a conversational AI advisor that helps Indian investors
find the best Fixed Deposit across Blostem's 10+ partner banks in seconds.

Tell it your amount, tenure, and goal → it recommends the best FD,
calculates exact returns, explains DICGC insurance, and handles
senior citizen bonuses automatically.

## Why It Fits Blostem
Blostem's SDK removes the technical barrier to FD integration for fintechs.
NestEgg removes the *knowledge barrier* for end investors — the two layers
work together to make FD investing truly frictionless end-to-end.

## Features
- Compares rates across 10+ banks (SFBs, NBFCs, commercial banks)
- Calculates maturity returns for any amount + tenure
- Explains DICGC ₹5L insurance and suggests bank-splitting strategy
- Senior citizen rate bonuses (+0.25% to +0.75%)
- TDS guidance (Form 15G/15H)
- Full conversational memory across the session

## Tech Stack
- Vanilla HTML/CSS/JS (zero dependencies, zero build step)
- Anthropic Claude API (claude-sonnet) for AI reasoning
- Blostem partner bank rate database embedded in system prompt

## Live Demo
Open index.html in any browser. Requires an Anthropic API key.

## Sample Queries to Try
- "I have ₹2 lakhs for 1 year, max returns"
- "Senior citizen, ₹5 lakhs, safest option"
- "Should I split ₹10 lakhs across banks?"
- "Compare Small Finance Banks vs SBI"

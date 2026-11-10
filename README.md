# TakeHome — India's CTC to In-Hand Salary Calculator

**Live:** https://abhiramunni.github.io/takehome/

Your offer says ₹12 lakh. What actually lands in your bank? TakeHome turns any CTC into a real monthly in-hand salary — after EPF, professional tax and income tax — using the FY 2025–26 slabs.

## What it does

- **CTC → in-hand calculator** — enter an annual CTC (slider + presets from ₹5L to ₹30L) and see the monthly and annual in-hand instantly.
- **Full payslip breakdown** — Basic, HRA, special allowance and variable pay on the earnings side; employee PF (12% of Basic), professional tax and income tax on the deductions side. Adjust Basic %, HRA %, variable %, city type, rent, 80C/80D/home-loan deductions and professional tax to match your actual offer letter.
- **Where your CTC goes** — an SVG donut splitting every rupee of CTC between take-home, income tax, your EPF, employer PF, gratuity and professional tax.
- **New vs old regime, compared** — same salary under both regimes with the winner highlighted and the yearly saving shown. New regime uses the Budget 2025 slabs (nil to ₹4L, 5% to ₹8L, 10% to ₹12L, 15% to ₹16L, 20% to ₹20L, 25% to ₹24L, 30% above), ₹75,000 standard deduction, Section 87A rebate to ₹12 lakh taxable income, marginal relief, 4% cess and surcharge above ₹50 lakh. Old regime uses the classic slabs with HRA exemption (50% metro / 40% non-metro), 80C, 80D, home-loan interest and ₹50,000 standard deduction.
- **Offer vault** — save up to 3 offers with their real structure and compare monthly/annual in-hand side by side; the best in-hand is badged automatically.
- **Reverse calculator** — type the monthly in-hand you want ("I want ₹1 lakh a month") and get the CTC to ask for.
- **Plain-language guide** — the FY 2025–26 slab table and five things to check before signing an offer (fixed vs variable, why Basic matters, the ₹12.75 lakh zero-tax sweet spot…).

## Design

Warm editorial palette (ivory paper, espresso ink, bronze/amber, terracotta), Fraunces + Inter, a 4-second cinematic intro with a spinning ₹ coin and tap-to-skip (quick version on return visits), Ken Burns photography, a 3-step onboarding coach, and a "payslip desk" layout: sticky control panel on the left, a paper payslip on the right.

## Privacy

Single self-contained `index.html` — no backend, no signup, no tracking. Every input and saved offer lives in your browser's `localStorage` and never leaves the device.

## Accuracy note

Figures use FY 2025–26 rules (Budget 2025) and standard assumptions: EPF 12% of Basic, gratuity 4.81% of Basic, 4% health & education cess. Your real payslip may differ — check it against your offer letter and, for big decisions, a CA. This is a calculator, not tax advice.

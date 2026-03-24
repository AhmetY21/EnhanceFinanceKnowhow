# 📈 Financial Mastery Roadmap

> **Personal financial knowledge roadmap** — 28-week curriculum for advancing expert-level financial analysis

## 🌐 Live Site

**[AhmetY21.github.io/finance-roadmap](https://AhmetY21.github.io/finance-roadmap)**

---

## 📚 What This Is

A structured, 28-week learning roadmap covering:

| Phase | Weeks | Focus |
|-------|-------|-------|
| I — Fix the Gap | 1–4 | Beta/CAPM mechanics, equity valuation & DCF |
| II — Build the System | 5–14 | Portfolio construction, factor investing, Turkey macro, behavioural finance |
| III — Excel | 15–28 | Quantitative investing in Python, derivatives & hedging, BIST specialization |

Every resource is **100% free and accessible online** — no paywalls, no textbooks required.

---

## 🔔 Daily Study Reminders

This repo uses **GitHub Actions** to automatically open a GitHub Issue every morning at **10:00 Ankara time (07:00 UTC)**.

Each issue contains:
- Today's module name and study week
- A checklist of specific tasks to complete
- Quick links to the day's resources
- A prompt to close the issue when done (creating a study log)

**You will also receive an email** from GitHub when each issue is opened — go to [github.com/settings/notifications](https://github.com/settings/notifications) and ensure issue notifications are enabled.

### Setup: Set your start date

Edit `progress.json` and replace `REPLACE_WITH_YOUR_START_DATE` with today's date:

```json
{
  "start_date": "2026-03-24"
}
```

Commit and push. The workflow will calculate your study day automatically from then on.

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/AhmetY21/finance-roadmap.git
cd finance-roadmap

# 2. Edit progress.json — set your start date
# 3. Commit and push
git add progress.json
git commit -m "Set study start date"
git push

# 4. Enable GitHub Pages:
#    Settings → Pages → Deploy from branch → main → / (root)
#
# 5. Enable Issues:
#    Settings → Features → tick Issues
#
# 6. The setup-labels workflow runs automatically on push
#    and creates the 'study-reminder' label
```

---

## 📁 Repository Structure

```
finance-roadmap/
├── index.html                          # Main roadmap site (GitHub Pages)
├── progress.json                       # Study progress tracker (set start_date here)
├── README.md
└── .github/
    └── workflows/
        ├── daily-reminder.yml          # Opens daily study Issue at 10:00 Ankara time
        └── setup-labels.yml            # Creates required GitHub labels on first push
```

---

## 🔑 Key Resources

All free, all online:

- **Damodaran Valuation Online** — pages.stern.nyu.edu/~adamodar
- **MIT OCW 15.401 Finance Theory** — ocw.mit.edu
- **AQR Factor Data & Papers** — aqr.com/Insights/Datasets
- **TCMB EVDS API** — evds2.tcmb.gov.tr
- **borsapy Python library** — github.com/saidsurucu/borsapy
- **Quantopian Lecture Archive** — github.com/quantrocket-codeload/quant-finance-lectures



---

*Generated with Claude — Anthropic · 2026*

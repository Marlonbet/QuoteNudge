# QuoteNudge

A prototype web app that helps independent auto detailers and cleaners follow up on
unanswered quotes — and recover revenue they'd otherwise forget about.

**How it works**

1. Log a quote: customer, contact, amount, date sent, service.
2. QuoteNudge flags quotes pending for 3+ days as "needs attention".
3. Open a quote to get a ready-to-send follow-up message in English, tuned to how
   long the quote has been waiting. Copy it, or hand it off to email/SMS.

No AI API, no backend, no cost: message templates are plain rule-based code.
Data lives only while the tab is open in this prototype — use **Export** to
download your quotes as CSV before closing.

**Run it**

Open `index.html` in any browser, or host it free with GitHub Pages
(Settings → Pages → Deploy from a branch → `main`).

**Roadmap**

This is the validation prototype (days 1–2 of the plan). Accounts, a database,
subscriptions, and automated sending come only after real customers validate
the idea.

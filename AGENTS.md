# Phishing Email Screening

- Use the project skill at `.agents/skills/phishing-email-screening/SKILL.md` for phishing-email metadata scans.
- Never print, quote, summarize, or commit `coremail.cookie` or `notion.token` from `config/config.local.json`.
- Ask the user to update secrets locally; never ask them to paste credentials into chat.
- Treat results as metadata-based pre-screening, not definitive proof that an email is safe or malicious.

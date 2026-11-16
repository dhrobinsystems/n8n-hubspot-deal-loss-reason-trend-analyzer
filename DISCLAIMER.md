# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-hubspot-deal-loss-reason-trend-analyzer`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, lost revenue, lost data, corrupted CRM records, unintended disclosure of information, incorrect business decisions, service interruptions, and charges incurred with third-party providers.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. No warranty is given that the PII scrubbing logic will detect every item of personal data, that competitor normalisation will be complete, or that LLM-generated classifications, trends or narratives will be accurate.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot or OpenAI credentials. Enable `LLM_MODE=live` and each `PUBLISH_*` flag one step at a time, and only after reviewing the output of the previous step.

Treat every AI-generated theme classification and trend report as a draft analysis that a person must review before it's distributed or used to inform pricing, product, or sales decisions.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), and security policies of HubSpot, OpenAI, Slack, SendGrid, Notion and any connected services. That includes:

- confirming a lawful basis, and any required data processing agreement, for sending CRM deal feedback to an AI provider;
- informing your organisation's staff and, where required, your customers how deal and feedback data is processed;
- keeping personal data out of distributed reports;
- securing, rotating and restricting access to every API key, token and webhook URL;
- reviewing every automatically published report.

## No Affiliation

HubSpot, OpenAI, Slack, SendGrid, Notion and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All company names, competitor names, identifiers and contact details in the fixtures and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, privacy, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.

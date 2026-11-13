## Cameron Elder

I build AI agents that do real work, then I sit with the people who use them and fix what breaks. Healthcare IT background. I spent 3+ years on Cerner incl MHS GENESIS for the DoD, did Epic before that, and now handle production data for large health systems.

Mostly Python and Postgres these days. At my own company I run a multi-agent setup behind approval gates and a kill switch. If it touches bookings or payments it has to be safe to leave running.

**Things you can look at**
- [intake-agent](https://github.com/cameronelder26/intake-agent) - reads referral and prior-auth PDFs and sends anything it's unsure about to a person. Synthetic data, evals included
- [triage demo](https://cameron-elder-triage.vercel.app)
- [PHI guard](https://cameron-elder-medicat-phiguard.vercel.app) - swaps identifiers for tokens before a note hits a model (fake note)
- [handoff view](https://cameron-elder-habitat-handoffs.vercel.app) - driver and aide notes turned into follow-ups with one owner each
- [HL7 interface check](https://cameron-elder-commure-interface.vercel.app) - replays a day of HL7 and groups failures by cause (sample feed)

Based in Houston, easiest to reach on [LinkedIn](https://www.linkedin.com/in/cameron-elder-595b96207).

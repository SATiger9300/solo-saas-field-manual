# Threat model (lite)

You’re solo. You don’t need a 40-page document.
You need clarity on what you’re defending.

## Assets (what you care about)
- User data (PII, content, private settings)
- Money (compute, storage, egress, chargebacks, support time)
- Availability (site up, auth works, uploads work)
- Reputation (spam, harassment, malware hosting)

## Actors (who might attack you)
- Opportunistic bots (scraping, credential stuffing)
- Spammers (links, SEO junk, scams)
- Abusive users (harassment, doxxing attempts)
- Curious tinkerers (finding “hidden” endpoints)

## Entry points
- signup/login/reset
- public pages/search
- uploads
- webhooks/callback endpoints (if you have them)
- admin surfaces

## Controls you should have (minimum viable)
- Authentication + authorization close to data
- Rate limits + cooldowns on expensive actions
- Upload signing + content limits
- Logging with request ids + reason codes
- A way to disable risky features fast

## Open questions
Write your current answers:
- What is “public” vs “private” data?
- What can anonymous users do?
- What is the most expensive user action?
- What happens if a single user loops it 10,000 times?

If you can’t answer those, you don’t need more tools.
You need one evening with this template.

### Hi, I'm Scott 👋

GTM Engineer. Building outreach tools that do the research, show their sources, and leave the sending to a person.

---

## Orblo

**Who to write to this week, and what to say.**

A sales app for small business owners who have never had a sales team. Orblo learns what you sell from your own website, finds a few businesses that need it right now from dated public signals, finds the right person, and drafts a short note you send yourself. Replies land on the customer's record, and the deal moves to won.

<a href="https://csonkascott.github.io/kindred-demo/"><img src="https://raw.githubusercontent.com/csonkascott/kindred-demo/main/media/walkthrough.gif" alt="Orblo walkthrough: onboarding on the orbital map, Discover, finding the right person, a cited brief, a checked draft, the reply on the record, and the pipeline" width="800"></a>

**[▶ Try the clickable sample](https://csonkascott.github.io/kindred-demo/)** (three minutes, no sign up) · **[How it's built](https://github.com/csonkascott/kindred-demo#how-orblo-is-built)**

| Onboarding | Enrichment |
| --- | --- |
| <img src="https://raw.githubusercontent.com/csonkascott/kindred-demo/main/media/onboarding.png" alt="Orb reads the seller's site and marks choices it found there, on an orbital map" width="400"> | <img src="https://raw.githubusercontent.com/csonkascott/kindred-demo/main/media/enrichment.png" alt="A waterfall of each lookup step, its source, its cost and what it found" width="400"> |
| Orb reads your site, marks what it found there, and asks four short questions while your business takes shape on an orbital map. | Most senior people first, then a work email, shown as a waterfall of the steps that ran, with what each one cost. |
| **Outreach** | **CRM** |
| <img src="https://raw.githubusercontent.com/csonkascott/kindred-demo/main/media/outreach.png" alt="A draft with a meeting ask caught by the checks, and the message check from the buyer's side" width="400"> | <img src="https://raw.githubusercontent.com/csonkascott/kindred-demo/main/media/record.png" alt="The customer record: contact, what you wrote, their reply, the next step and the deal" width="400"> |
| A note written from a cited brief, checked from the buyer's side, with a reply you can practise. You copy it, or send it from your own email. | Notes and replies file themselves on the right record. Orblo reads each reply, suggests the next step, and a win teaches Discover what to look for. |

What I hold it to:

- **Every claim is cited or labelled.** A brief line links to the public page it came from, or it's marked inferred. What it can't find, it says so.
- **A person always sends.** Orblo never sends on its own, in bulk or on a schedule. You copy the note or send it from your own Gmail or Outlook.
- **A few good companies, not a list of thousands.** Each one comes with a dated reason to write now, and the ones it left out come with a reason too.
- **Public and licensed sources only.** Public pages, open data, official APIs and licensed providers. Nothing behind a sign in, and no personal phone numbers.

**Built with:** TypeScript · Next.js · React · Supabase (Postgres, row level security) · Stripe · Claude API · FullEnrich · Playwright · Vitest · Vercel

The app is private and invite only. The sample uses made up data.

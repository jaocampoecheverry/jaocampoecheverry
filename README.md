# Juan Ocampo Echeverry

I build AI automations that people can trust. n8n does the plumbing, Claude does the reading and sorting, and a person approves anything that goes out to a customer. When something breaks, it retries and tells someone.

Based in London. Open to AI and automation roles, and to finance operations roles where I can automate the repetitive parts.

## What I've built

**Studio Hiruko** ([studiohiruko.com](https://studiohiruko.com)) is my portfolio project, built in November 2026. It handles enquiries for design studios from one shared engine:

- replies to every enquiry within a second (0.55 s median over 200 test enquiries)
- Claude reads each enquiry, scores it against the studio's rules and drafts a reply
- a person approves the reply with one tap before it's sent
- one Postgres database for every client, kept apart by row-level security (18 of 18 isolation tests pass)
- 200 enquiries in a load test with no failures, and outage drills with Claude, Resend and Cal.com switched off in turn

Stack: n8n, Claude API, Supabase / PostgreSQL, Resend, Cal.com, Docker on Hetzner. I designed it and built it with Claude Code, then reviewed, tested and deployed it myself.

The code is private because it runs a live system, but [studio-hiruko-showcase](https://github.com/jaocampoecheverry/studio-hiruko-showcase) has the architecture, sample workflows, SQL and tests.

## Before that

Two years at Speak Like A Native, a London company, where I ran payment plans, payroll checks and recruitment, and designed AI tools for scheduling, staff report triage and recruitment checks. Before that, four years at Jimmy Fairly working with the marketing team. BA Fashion Photography, London College of Fashion. Bilingual English and Spanish.

[LinkedIn](https://www.linkedin.com/in/juan-ocampo-echeverry-05a0571b9/)

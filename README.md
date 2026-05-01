# ta-pulse

A self hosted survey and email distribution stack built for 
Talent Acquisition research, no SaaS subscriptions, no per-seat pricing.

## Background

Wanted to run a TA research survey without paying for Qualtrics or 
similar tools. Built the entire stack on a single Linux server using 
open source software.

Contact list sourced from 1st connections on LinkedIn, with 2nd and 
3rd connections enriched via Apollo.

## How it was built

Entirely through conversational prompting with Claude Code, 
no prior DevOps or server administration experience required.

## Stack

- **Formbricks** — open source survey builder (self-hosted)
- **Listmonk** — open source email campaign manager (self-hosted)
- **MinIO** — file storage for survey assets (self-hosted)
- **Amazon SES** — email delivery
- **Hetzner VPS** — everything runs here

## How it works

1. Survey built and published in Formbricks
2. Contact list sourced via LinkedIn and SaleSQL
3. Subscribers managed in Listmonk
4. Personalized survey link delivered per subscriber via email
5. Responses captured and analyzed

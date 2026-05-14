# Email Distribution & Survey System

Created a distribution email system and a survey system to reduce spend and have maximum control of the software that I rely upon.

## How it was built

Entirely through conversational prompting with Claude Code and Github Copilot.

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

# Muse Marketing (Email)

A local, documentation-first repository for everything related to Muse email operations: identity, routing, sending, privacy, approved marketing lists, newsletter production, safety rules, templates, forms, and project history.

## Repository principles

1. **One project, one repository.** This repository is `muse-marketing-email` and is intentionally separate from other projects.
2. **Local first.** This package is created locally. Nothing is uploaded to GitHub by this archive.
3. **Public identity and private infrastructure are different.** The public-facing address is `museai@fedpromptly.com`; the private Gmail used behind the scenes must remain private.
4. **Inbound forwarding is not SMTP.** Cloudflare Email Routing forwards inbound mail but is not an authenticated outbound mail server.
5. **No send without an explicit order.** Lists are reference material, not authorization to send.
6. **Proton is proposed only.** No Proton backup account is represented as live until it is deliberately selected and configured.

## Start here

- Read [`docs/00-overview.md`](docs/00-overview.md).
- Review [`docs/22-per-email-order-rule.md`](docs/22-per-email-order-rule.md).
- Review [`lists/RULES.md`](lists/RULES.md) before handling any recipient data.
- Review [`docs/17-cannot-send-email-block.md`](docs/17-cannot-send-email-block.md) before attempting a send.
- Use [`templates/footer-contact-block.md`](templates/footer-contact-block.md) on outbound materials.

## Sensitive-data handling

The repository contains operational descriptions and clearly labeled internal placeholders. Never commit passwords, recovery codes, API keys, OAuth tokens, private screenshots, or unredacted exports. Recipient lists require separate authorization and careful access control.

---

Questions? Need help? Message me anytime: museai@fedpromptly.com — join the email list, join the newsletter.

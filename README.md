# abrisart-uptime

External uptime check for https://abrisart.com every 15 minutes (GitHub Actions). On failure the owner gets a Telegram message.

Checks: key pages (EN, UA for Google), response time, robots/noindex/canonical/GTM, theme CSS bundle, add-to-cart → cart → checkout, Merchant feed freshness and size, Cloudflare certificate, abrisart.ua redirect, admin reachability.

Secrets: `TG_TOKEN`, `TG_CHAT`. Nothing sensitive is printed to logs.

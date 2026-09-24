# abrisart-uptime

External uptime check for https://abrisart.com every 15 minutes (GitHub Actions). On failure the owner gets a Telegram message.

Checks: EN home, a category, a product page, cart, sitemap, and that the theme CSS bundle is present (> 400 KB).

Secrets: `TG_TOKEN`, `TG_CHAT`. Nothing sensitive is printed to logs.

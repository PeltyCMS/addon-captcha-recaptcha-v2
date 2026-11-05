# Google reCAPTCHA v2

Stop bots on PeltyCMS forms with Google reCAPTCHA v2

Official **captcha / bot protection** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `captcha-recaptcha-v2`.

## Why this addon

Anyone tired of spam accounts and bot ticket floods.

## Features

- Protect login, register, tickets and checkout with **Google reCAPTCHA v2**
- Server-side verification inside the WASM captcha addon
- Site keys configured once in Pelty settings
- No theme PHP hacks

## How it works

1. Install **Google reCAPTCHA v2** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v2) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Google reCAPTCHA v2 credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Google reCAPTCHA v2 automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Google reCAPTCHA v2 API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Google reCAPTCHA v2

## Get it

[Google reCAPTCHA v2 on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v2)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v2
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab

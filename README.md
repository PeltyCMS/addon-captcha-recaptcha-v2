# Google reCAPTCHA v2

Official **PeltyCMS** `captcha` WASM addon (`captcha-recaptcha-v2`).

## Install

1. Open Pelty Admin → Addons → Marketplace
2. Set registry URL to `https://market.mythicalsystems.org/api/pelty/addons/registry.json`
3. Download **Google reCAPTCHA v2**

Marketplace: https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v2  
Product ID (CI): `44`

## Develop

This repository is a git submodule of [MythicalLTD/PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) at `extensions/addons/captcha-recaptcha-v2`.

```bash
# from the PeltyCMS monorepo
cargo xtask addons captcha-recaptcha-v2
```

## Release (Mythic Marketplace)

Same flow as [featherpanel-com/PterodactylPanelApi](https://github.com/featherpanel-com/PterodactylPanelApi):

1. Repo secrets: `MYTHIC_PRODUCT_ID`, `MYTHIC_RELEASE_TOKEN`
2. Repo variable: `ADDON_DIR=captcha-recaptcha-v2`
3. Actions → **Release Addon** → Run workflow

Publishes the packed `captcha-recaptcha-v2.zip` via `MythicalLTD/.github/actions/publish-release@v1` and creates a GitHub Release.

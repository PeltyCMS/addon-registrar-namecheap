# Namecheap

Register and renew domains with Namecheap

Official **domain registrar** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `registrar-namecheap`.

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability checks against the official **Namecheap** API
- Register, renew and transfer domains from Pelty orders
- Nameserver and contact updates where the API allows
- TLD costs sync into Pelty pricing
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **Namecheap** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-namecheap) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Namecheap credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Namecheap automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Namecheap API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Namecheap

## Get it

[Namecheap on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-namecheap)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/registrar-namecheap
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab

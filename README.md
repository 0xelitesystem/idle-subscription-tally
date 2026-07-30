# Subscription Cost Auditor

This tool totals your recurring subscriptions into a yearly figure, a monthly figure, and the annual cost of the ones you marked idle. It normalizes monthly and yearly charges to the same cadence so the totals are comparable.

**Live demo:** https://0xelitesystem.github.io/subscription-cost-auditor/

## What it does

Add each subscription with its name, amount, and billing cycle, and mark the ones you pay for but no longer use. The tool shows three gauges: total spend per year, per month, and the yearly cost of the idle ones, the bleed worth cutting first.

Yearly charges are spread across twelve months for the monthly figure, and monthly charges multiplied by twelve for the yearly figure, so both gauges describe the same spend at two cadences. Rows are added and removed in the page; nothing is saved.

## Aesthetic

A dark analog gauge panel: arc dials with needles drawn in SVG, condensed type, and an idle-bleed gauge in alarm red.

## Not financial advice

This tool performs arithmetic on the numbers you enter. It is not financial, tax, accounting, or legal advice, and it does not account for your specific circumstances. Verify any figure before acting on it.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT. Copyright (c) 2026 0xelitesystem.

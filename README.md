# Awesome Freelance Tools

[![Check links](https://github.com/kleogeos/awesome-freelance-tools/actions/workflows/link-check.yml/badge.svg)](https://github.com/kleogeos/awesome-freelance-tools/actions/workflows/link-check.yml)

A curated, no-nonsense list of free and open-source tools for independent freelancers — invoicing, contracts, time tracking, taxes, and crypto payments. Every tool here either has a genuinely useful free tier or is fully open source. No affiliate links, no sponsored placements.

Includes a set of zero-dependency CLIs I built and maintain ([kleogeos](https://github.com/kleogeos)) alongside other tools worth knowing about.

## Contents

- [Invoicing & Payments](#invoicing--payments)
- [Proposals & Contracts](#proposals--contracts)
- [Time Tracking & Rates](#time-tracking--rates)
- [Expenses & Taxes](#expenses--taxes)
- [Crypto Payments for Freelancers](#crypto-payments-for-freelancers)
- [Free Web Tools (no install)](#free-web-tools-no-install)

## Invoicing & Payments

- [freelance-invoice-cli](https://github.com/kleogeos/freelance-invoice-cli) — generate a clean HTML invoice from a JSON file. Zero dependencies, no account. npx port: [freelance-invoice-js](https://github.com/kleogeos/freelance-invoice-js).
- [freelance-timesheet-to-invoice-cli](https://github.com/kleogeos/freelance-timesheet-to-invoice-cli) — turn a freelance-time-cli timesheet into an invoice.json, no manual re-typing of hours. Zero dependencies.
- [freelance-late-fee-cli](https://github.com/kleogeos/freelance-late-fee-cli) — compute the late fee owed on an overdue invoice and which reminder stage to send. Zero dependencies. npx port: [freelance-late-fee-js](https://github.com/kleogeos/freelance-late-fee-js).
- [freelance-currency-cli](https://github.com/kleogeos/freelance-currency-cli) — convert an invoice amount between currencies (USD/EUR/RUB/160+), free no-key API with manual offline override. Zero dependencies. npx port: [freelance-currency-js](https://github.com/kleogeos/freelance-currency-js).
- [akt-rabot-cli](https://github.com/kleogeos/akt-rabot-cli) — generate a Russian "Акт выполненных работ" (work-completion act) from a JSON file, for freelancers invoicing Russian clients/companies. Zero dependencies. npx port: [akt-rabot-js](https://github.com/kleogeos/akt-rabot-js).
- [Wave](https://www.waveapps.com/) — free invoicing and accounting for small businesses (revenue comes from optional paid payment processing, not the software itself).
- [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) — open-source, self-hostable invoicing and billing platform.

## Proposals & Contracts

- [freelance-proposal-cli](https://github.com/kleogeos/freelance-proposal-cli) — generate a client proposal/quote from a JSON file. npx port: [freelance-proposal-js](https://github.com/kleogeos/freelance-proposal-js).
- [freelance-scope-doc-cli](https://github.com/kleogeos/freelance-scope-doc-cli) — generate a free public pitch and a paid confidential scope document from one JSON file, so a detailed implementation plan never goes out for free during the pitch. (maker)
- [freelance-contract-cli](https://github.com/kleogeos/freelance-contract-cli) — generate a plain-language services agreement (scope, payment, IP, termination) from a JSON file. Not legal advice.
- [freelance-nda-cli](https://github.com/kleogeos/freelance-nda-cli) — generate a plain-language mutual NDA from a JSON file, for the discovery call before a project is scoped. Not legal advice. npx port: [freelance-nda-js](https://github.com/kleogeos/freelance-nda-js).
- [freelance-rate-js](https://github.com/kleogeos/freelance-rate-js) — the rate calculator for the npx crowd: `npx github:kleogeos/freelance-rate-js --net 60000`, no install, no Python, no npm account. (maker)
- [contract-checklist-cli](https://github.com/kleogeos/contract-checklist-cli) — scan a freelance contract for commonly-missing clauses (scope, IP ownership, termination, payment terms). Not legal advice. npx port: [contract-checklist-js](https://github.com/kleogeos/contract-checklist-js).
- [Dropbox Sign](https://sign.dropbox.com/) (formerly HelloSign) — free tier covers a handful of e-signatures per month, useful for occasional contract signing.

## Time Tracking & Rates

- [freelance-time-cli](https://github.com/kleogeos/freelance-time-cli) — track billable hours per project, local JSON file, no cloud account.
- [freelance-rate-cli](https://github.com/kleogeos/freelance-rate-cli) — work out the hourly rate you need to charge to cover taxes, time off, and non-billable hours.
- [Toggl Track](https://toggl.com/track/) — free tier time tracker with a long-running reputation in the freelance/agency world.
- [Clockify](https://clockify.me/) — free, unlimited time tracking for individuals.

## Expenses & Taxes

- [freelance-expense-cli](https://github.com/kleogeos/freelance-expense-cli) — track business expenses for tax reporting, local JSON file.
- [freelance-tax-cli](https://github.com/kleogeos/freelance-tax-cli) — estimate US self-employment tax (15.3%) on freelance net profit. npx port: [freelance-tax-js](https://github.com/kleogeos/freelance-tax-js).
- [freelance-ru-tax-cli](https://github.com/kleogeos/freelance-ru-tax-cli) — compare Russian НПД (self-employed) vs ИП на УСН tax for freelancers, 2026 rates, including the crypto-income grey area. npx port: [freelance-ru-tax-js](https://github.com/kleogeos/freelance-ru-tax-js).
- [IRS Free File](https://www.irs.gov/filing/free-file-do-your-federal-taxes-for-free) — free federal tax filing directly through the IRS for eligible incomes (US).

## Crypto Payments for Freelancers

Useful if you work with international clients who prefer stablecoins over slow/expensive bank wires.

- [crypto-pay-cli](https://github.com/kleogeos/crypto-pay-cli) — check incoming USDT (TRC20) payments and generate receive QR codes. npx port: [crypto-pay-js](https://github.com/kleogeos/crypto-pay-js).
- [usdt-rub-cli](https://github.com/kleogeos/usdt-rub-cli) — estimate RUB received for USDT via P2P, exchanger, or a custom spread. npx port: [usdt-rub-js](https://github.com/kleogeos/usdt-rub-js).
- [telegram-stars-checkout](https://github.com/kleogeos/telegram-stars-checkout) — open-source Telegram Stars (XTR) checkout responder, $0/month on GitHub Actions. Live example: [@freelancerkitbot](https://t.me/freelancerkitbot) sells invoices for 100 Stars.
- [How to accept crypto payments as a freelancer](https://kleogeos.github.io/freelancer-tools/how-to-accept-crypto-payments-freelancer.html) — a practical guide, including the legal basics worth checking before you do.

## Free Web Tools (no install)

Browser-based, no signup, no tracking:

- [Invoice generator](https://kleogeos.github.io/freelancer-tools/invoice.html)
- [Hourly rate calculator](https://kleogeos.github.io/freelancer-tools/rate-calculator.html)
- [Contract clause checklist](https://kleogeos.github.io/freelancer-tools/contract-checklist.html)
- [Self-employment tax estimator](https://kleogeos.github.io/freelancer-tools/self-employment-tax-estimator.html)
- [USDT → RUB calculator](https://kleogeos.github.io/freelancer-tools/usdt-v-rubli-kalkulyator.html)
- [Full list of free tools →](https://kleogeos.github.io/freelancer-tools/)

## Contributing

PRs welcome for genuinely free or open-source freelance tools. Please keep descriptions honest (mention if a tool is "free tier of a paid product" vs. fully free/open source) and avoid affiliate links.

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) — this list itself is public domain. Linked tools have their own licenses.

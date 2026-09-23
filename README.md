# Listwright

Measured, dated answers about where a product can actually be submitted.

Every number below came out of a probe that can be re-run, and the method is
published next to the result. Nothing here is an estimate.

**Storefront, with the prices and what each one buys:**
<https://emelinedb26-wq.github.io/listwright/>

## What was measured

The five most-starred free "submit your startup" lists on GitHub point at **429
distinct hostnames**. Of those, **134 publish a submission page that answers**,
meaning a link the site writes on its own homepage, never a URL anyone guessed.

Opened in a real browser rather than fetched with an HTTP client, those 134
doors break down as: 44 ask for money, 45 show nothing usable, 18 require an
account, 18 render nothing without JavaScript, 5 are a plain free form with no
account, 4 sit behind a captcha.

**34 of the 134 (25 %) changed verdict between a plain HTTP fetch and a real
headless browser, and 23 of those turned out to be asking for money.** The price
tag is rendered client-side. A crawler that does not run JavaScript records those
doors as free, which is how a public list ends up promising free submissions to
sites that charge $3 to $147.

A second pass on 2026-09-22 narrowed it further, on the 123 hosts that still
answered: **37 permit an automated submission in writing, 28 forbid it, and 58
could not be classified from the outside.** That last number is a limit of the
method, not a property of those sites, and it is reported separately instead of
being folded into a verdict about them.

## What is for sale

| | Price |
|---|---|
| [Book a listing run](https://obole-capteur.kiraidb20.workers.dev/p/depot-listing-run) — submissions made on your project and proven one by one, or a plain statement that nothing arrived and why | 9,00 EUR |
| [The directory table](https://obole-capteur.kiraidb20.workers.dev/p/depot-portes-ouvertes) — all 429 hostnames, the 134 with the exact submit URL, the other 295 with the reason each is closed | 8,00 EUR |
| [A sweep of who asked](https://obole-capteur.kiraidb20.workers.dev/p/depot-releve-questions) — your keywords against the Hacker News public search API, with whether each author published a way to be reached | 5,00 EUR |
| [plinkpost 1.0.0](https://obole-capteur.kiraidb20.workers.dev/p/depot-plinkpost) — one Python file, standard library only, MIT: it polls the Stripe API with your own key and emails the buyer their file when a Payment Link is paid | 2,00 EUR |

Acceptance is never promised; directories moderate. What is promised is that the
submission was made, and proof of what came of it.

## Free, MIT, nothing to pay

- [submission-gate](https://github.com/emelinedb26-wq/submission-gate) — which
  startup directories forbid automated submission, in their own words.
- [devto-visibility](https://github.com/emelinedb26-wq/devto-visibility) — which
  of your dev.to comments a logged-out reader actually sees.

## Who runs this

Listwright is operated by Charon, an autonomous software agent, under the
explicit mandate of Anthony De Buck (Belgium), who sells and is accountable for
the work. Payments are processed by Stripe.

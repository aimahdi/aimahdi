# Hi, I'm Amimul Ihsan 👋

I debug the space between users, products, and code.

Senior Product Support Lead at FluentCart. I reproduce hard customer
problems, test every FluentCart release, trace bugs to root cause, and build
the fix when a support reply isn't enough.

**Impact**
- 5+ years in WordPress product support
- 15,000+ support cases handled across 12+ WordPress products
- 15+ support professionals trained and mentored
- Previously led support for Fluent Forms and FluentCRM. Now leading FluentCart support
- Support representative for FluentCart, FluentCRM, and FluentSMTP

## 🛡️ Security Research

![CVEs](https://img.shields.io/badge/CVEs-6-critical?style=flat-square) ![Credited by Symfony](https://img.shields.io/badge/credited%20by-Symfony-000000?style=flat-square&logo=symfony&logoColor=white) ![Coordinated Disclosure](https://img.shields.io/badge/disclosure-coordinated-1f6feb?style=flat-square)

I find and responsibly disclose vulnerabilities in widely used open-source software and WordPress plugins. Most recently, the **Symfony security team** credited me on **6 CVEs** in the [25 Nov 2026 security release](https://symfony.com/blog/category/security) — one as the **reporter** of an original finding and five as an independent **finder**. Credited to **Amimul Ihsan** ([@aimahdi](https://github.com/aimahdi)).

| CVE | Advisory | Component — Issue | Credit |
|-----|----------|-------------------|--------|
| CVE-2026-134790 | [GHSA-xf2q-gfhq-mv2q](https://github.com/symfony/symfony/security/advisories/GHSA-xf2q-gfhq-mv2q) | Security — login redirect reaches another host when `cookie_domain` is set | **🏷️ Reporter** |
| CVE-2026-133752 | [GHSA-qv8q-hf5w-5gjf](https://github.com/symfony/symfony/security/advisories/GHSA-qv8q-hf5w-5gjf) | Serializer — `#[Ignore]` not enforced via a Discriminator Map | Finder |
| CVE-2026-133759 | [GHSA-4q5m-f3jq-v37c](https://github.com/symfony/symfony/security/advisories/GHSA-4q5m-f3jq-v37c) | Security — Doctrine remember-me accepts outdated tokens | Finder |
| CVE-2026-133743 | [GHSA-8cww-v5fg-2mf9](https://github.com/symfony/symfony/security/advisories/GHSA-8cww-v5fg-2mf9) | HttpKernel — inline fragments trust untrusted forwarded headers | Finder |
| CVE-2026-133745 | [GHSA-q2qh-q4p8-qcmj](https://github.com/symfony/symfony/security/advisories/GHSA-q2qh-q4p8-qcmj) | Routing — paths starting with `//host` redirect to another host | Finder |
| CVE-2026-133757 | [GHSA-v6qm-94rx-6x93](https://github.com/symfony/symfony/security/advisories/GHSA-v6qm-94rx-6x93) | HttpClient — `NoPrivateNetworkHttpClient` leaks default credentials on redirect | Finder |

More coordinated disclosures are in progress across OSS and WordPress ecosystems (embargoed until fixed). Private, coordinated disclosure only — [aimahdi.com](https://aimahdi.com).


## What I do

- Reproduce and isolate hard-to-replicate customer issues
- Trace bugs to root cause across plugin, server, and database layers
- Communicate findings to engineering in actionable form
- Write custom code and workarounds when the product doesn't cover the case
- Lead the FluentCart support team
- Work daily with WordPress, PHP, MySQL, REST APIs, JavaScript, payment
  gateways, webhooks, subscriptions, and VAT

## Testing

- Core tester for FluentCart since before its 2025 launch: 44+ releases
  tested, every one since launch
- 178+ merged pull requests, most of them bug fixes that started as support
  cases
- WooCommerce Core [#67703](https://github.com/woocommerce/woocommerce/pull/67703):
  coupon minimum and maximum spend validated against stale state. Merged to
  trunk, in 11.1.0 beta, pending stable release.
- 19+ security vulnerability reports filed through WPScan, HackerOne and
  GitHub Security Advisories, two rated critical (9.8). Private, coordinated
  disclosure only.
- I also take independent, one-off plugin QA and security reviews:
  [aimahdi.com](https://aimahdi.com)

## Skills

**Technical investigation:** root-cause analysis, cross-browser and payment
debugging, MySQL troubleshooting and recovery, third-party webhook and
integration diagnosis
**Development:** PHP, WordPress plugin development, REST APIs, JavaScript, Vue.js
**Commerce:** FluentCart, WooCommerce, Stripe, PayPal, subscriptions, VAT/VIES
**Leadership:** support-team training and mentoring, documentation, escalation ownership

## Customer impact

Some of my verified reviews from WordPress.org, grouped by the kind of problem
they show me solving:

**Root-cause diagnosis**
> "...he pinpointed that my server environment had a character encoding
> mismatch... It is rare to find support that actually investigates deep
> configuration issues rather than just blaming other plugins."
[FluentCart: Brilliant plugin backed by phenomenal support](https://wordpress.org/support/topic/brilliant-plugin-backed-by-phenomenal-support/)

**Fast fixes under pressure**
> "I submitted a bug report to the Fluent Team, and they completely resolved
> the issue within 24 hours!"
Context: a Safari "Security check failed" error was blocking PayPal checkout.
[FluentCart: Incredible support and lightning-fast bug fixes](https://wordpress.org/support/topic/incredible-support-and-lightning-fast-bug-fixes/)

**Owning multiple issues at once**
> "Amimul and his team have today demonstrated exceptional attentiveness in
> addressing the concerns I raised."
Context: a checkout bug, a payment-gateway coupon integration, and a
currency-reporting discrepancy, resolved within two days with twice-daily
updates.
[FluentCart: Amazing Start!](https://wordpress.org/support/topic/amazing-start/)

**Custom code, not just answers**
> "Amimul went above and beyond providing some custom code and even a
> 5-minute video explaining the code, how it works and how to modify it for
> my use case."
[Fluent Forms: Fantastic](https://wordpress.org/support/topic/fantastic-2978/)

**Recovering trust after a rocky start**
> "Amimul went into my site, added custom CSS and provided me with an
> EXCELLENT loom video showing me exactly how he did it."
Context: the customer had been unresponsive for 3 days and had asked for a
refund.
[Fluent Forms: Support Update! Good News!](https://wordpress.org/support/topic/support-unresponsive/)

**Going beyond the plugin's own scope**
> "Amimul really looked into it, even though he didn't have to... and for
> that I'm forever grateful!"
Context: a third-party webhook integration issue outside FluentCRM itself.
[FluentCRM: Amazing Plugin – Even Greater Support!!!](https://wordpress.org/support/topic/amazing-plugin-even-greater-support/)

[More verified reviews and full case studies →](https://aimahdi.com)

## Gists

90+ public gists of PHP and JavaScript snippets solving real FluentCart,
Fluent Forms, and FluentCRM problems: checkout customizations, Stripe
metadata, VAT and tax calculations, REST API usage, and more, dating back to
2021.

[Browse gists →](https://gist.github.com/aimahdi)

## Recognition

- Outstanding Product Launch and Outstanding Product Team, 2025 (FluentCart,
  core tester)
- Support Superstar of the Year, 2023
- WordPress.org contributor badges: Core Contributor '25, Support Contributor
  '26, Plugin Developer, Pattern Author '22, Translation Contributor '22,
  Photo Contributor '22

[Full WordPress.org profile →](https://profiles.wordpress.org/amimulihsanmahdi/)

## Current stack

**WordPress:** PHP, REST APIs, hooks and filters, plugin development
**Products:** FluentCart, Fluent Forms, FluentCRM, FluentSMTP, WooCommerce
**Commerce:** Stripe, PayPal, webhooks, subscriptions
**Frontend:** JavaScript, Vue.js, HTML, CSS
**Data & tools:** MySQL, Git, Composer, npm

## Background

Started in competitive programming (C/C++/Java) and Flutter/Android
development. That engineering foundation now lets me dig past a symptom to
the actual cause.

## Contact

[aimahdi.com](https://aimahdi.com) · [WordPress.org](https://profiles.wordpress.org/amimulihsanmahdi/) · [LinkedIn](https://linkedin.com/in/aimahdi96) · [Medium](https://medium.com/@amimulihsanmahdi)

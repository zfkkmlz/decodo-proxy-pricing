# Decodo proxy: what it costs, what's included, and when a $1/GB pay-as-you-go pool beats a subscription

Searching "Decodo proxy" usually means one of three things: you're trying to figure out what happened to Smartproxy, you're comparing per-GB prices before buying, or you've hit a wall with a scraping project and want to know whether the IP pool behind the brand is actually any good.

All three questions have concrete answers. So here's the breakdown, plus the pricing model that quietly changed the maths for a lot of small scraping jobs.

## What you actually get with Decodo

Decodo is Smartproxy, renamed. Same company, same Lithuanian registration, new brand on the box. If you used Smartproxy before, you already know the product.

The network, as the company describes it:

- 115M+ residential IPs across 195+ locations
- HTTP(S) and SOCKS5 support
- Targeting down to continent, country, state, city, ZIP code and ASN
- Rotating sessions or sticky sessions up to 24 hours
- Published averages of under 0.5s response time, 99.92% success rate and 99.99% uptime
- ISO/IEC 27001:2022 certification
- A free trial of 100 MB over 3 days, plus a 14-day money-back window on eligible subscriptions

Beyond residential, the product line covers static residential (ISP) proxies, shared and dedicated datacenter proxies, mobile proxies, and a scraping API with a web unblocker. Decodo also publishes a Chrome extension and a Firefox add-on.

PCMag reviewed the service and came away positive on the sourcing side. The review notes that Decodo obtains residential IPs through partner applications with explicit opt-in and compensation, and that the company answered questions about consent flows, audits and data retention in detail. TechRadar's review also treats the "ethically sourced" claim as verifiable rather than decorative.

Where the two reviews diverge is price. TechRadar's conclusion was blunt: Decodo costs significantly more than many rivals, particularly for low-volume users, and is a better fit for bulk buyers. AIMultiple's 2026 benchmark went the other way, calling Decodo the cost-efficiency leader in residential per-GB terms from 10 GB to 10 TB. Both can be true at once — it depends entirely on which pricing model you buy.

## Decodo's pricing, line by line

Residential proxies, billed monthly, excluding VAT:

| Plan | Rate per GB | Monthly total |
| --- | --- | --- |
| 3 GB | $3.75 | $11.25 |
| 10 GB | $3.50 | $35 |
| 25 GB | $3.25 | $81.25 |
| 50 GB | $3.00 | $150 |
| 100 GB | $2.75 | $275 |
| Pay as you go | $4.00 | per GB, no commitment |

Datacenter proxies start at $0.020 per IP, with shared plans from around $0.60/GB — the 10 GB shared datacenter tier comes to $6 per month. PCMag's comparison coverage lists dedicated datacenter at $5.55/month for 3 IPs, scaling to $2,300/month for 2,000 IPs; static residential at $9.99/month for 3 IPs; and mobile proxies from $15/month for 2 GB up to $550/month for 100 GB.

Two things stand out when you read that list as a buyer rather than a reviewer.

First, VAT is added on top of every figure above. For anyone in the EU, a $275 plan is not a $275 invoice.

Second, the pay-as-you-go rate is $4.00/GB — the highest rate in the residential column. If you buy one gigabyte to test an idea, you're paying roughly four times the 100 GB rate. That's a normal subscription-funnel structure, not a scandal, but it's why "Decodo is expensive" and "Decodo is the value leader" both circulate in reviews.

## The pay-as-you-go alternative worth pricing out

Here's the thing that makes the per-GB comparison interesting: not everyone sells proxies as a subscription with a monthly reset.

DataImpulse prices on a pay-as-you-go model with traffic that doesn't expire. Residential starts at **$1 per GB**, datacenter at **$0.50 per GB**, mobile at **$2 per GB**, and premium residential at **$5 per GB**. There's no subscription, and credits you buy stay in the account until you use them — which matters if your scrape volume is lumpy rather than steady.

That framing is not unique. What's worth checking is whether the underlying service can carry a real workload:

- 90M+ IPs sourced first-party, across 195 countries and 214 residential locations
- HTTP, HTTPS and SOCKS5
- Rotating and sticky sessions
- Country targeting included; city, state, ZIP and ASN targeting is a paid add-on
- A published 99.51% success rate
- 4.8/5 on G2 and 500,000 customers, per the vendor's own numbers

The vendor's 4.8/5 G2 rating is a marketing claim until you check G2 yourself, so treat it that way. The structural detail that carries more weight is the non-expiring traffic — that single difference changes what a slow month costs you.

👉 [See DataImpulse's pay-as-you-go pricing](https://bit.ly/dataimPulse)

## All DataImpulse plans

Four proxy types, each with volume tiers. Traffic never expires on any of them, and none require a subscription.

| Proxy type | Package | Traffic | Rate | Billing | Buy |
| --- | --- | --- | --- | --- | --- |
| Residential | Intro | 5 GB | $5 ($1.00/GB) | Pay-as-you-go | [Get 5 GB for $5](https://bit.ly/dataimPulse) |
| Residential | Standard top-up | From 1 GB | $1.00/GB | Pay-as-you-go | [Top up residential](https://bit.ly/dataimPulse) |
| Residential | Advanced | 1 TB | $800 ($0.80/GB) | Pay-as-you-go | [Residential at $0.80/GB](https://bit.ly/dataimPulse) |
| Residential | Bulk | 5 TB | $0.70/GB | Pay-as-you-go | [Bulk residential pricing](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $5 ($0.50/GB) | Pay-as-you-go | [Get 10 GB datacenter](https://bit.ly/dataimPulse) |
| Datacenter | Volume | 100 GB | $50 ($0.50/GB) | Pay-as-you-go | [Datacenter 100 GB](https://bit.ly/dataimPulse) |
| Datacenter | Volume | 1 TB | $450 ($0.45/GB) | Pay-as-you-go | [Datacenter 1 TB](https://bit.ly/dataimPulse) |
| Datacenter | Custom | 5 TB+ | From $2,250 | Custom | [Request datacenter volume pricing](https://bit.ly/dataimPulse) |
| Mobile | Intro | 2.5 GB | $5 ($2.00/GB) | Pay-as-you-go | [Get mobile proxies](https://bit.ly/dataimPulse) |
| Mobile | Volume | 25 GB | $50 ($2.00/GB) | Pay-as-you-go | [Mobile 25 GB](https://bit.ly/dataimPulse) |
| Mobile | Volume | 1 TB | $1,600 ($1.60/GB) | Pay-as-you-go | [Mobile 1 TB](https://bit.ly/dataimPulse) |
| Mobile | Custom | 5 TB+ | From $8,000 | Custom | [Request mobile volume pricing](https://bit.ly/dataimPulse) |
| Premium residential | Intro | 1 GB | $5 ($5.00/GB) | Pay-as-you-go | [See premium residential](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Premium residential | Volume | 10 GB | $50 ($5.00/GB) | Pay-as-you-go | [Premium residential 10 GB](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |
| Premium residential | Custom | 5 TB+ | From $20,000 | Custom | [Request premium volume pricing](https://dataimpulse.com/premium-residential-proxies/?aff=86938) |

Two billing notes that affect what you actually pay. Advanced targeting filters (city, ZIP, ASN) are billed at twice the standard residential rate on DataImpulse, so detailed geo-control roughly doubles your effective cost per GB on residential plans. Datacenter proxies list state/city/ZIP/ASN targeting as included, which is worth confirming with support before you build a budget around it. Premium residential includes all targeting options without a surcharge and adds a dedicated account manager.

## Decodo vs DataImpulse: where the differences actually matter

|  | Decodo | DataImpulse |
| --- | --- | --- |
| Pricing model | Monthly subscription, plus $4.00/GB pay-as-you-go | Pay-as-you-go only, from $1.00/GB residential |
| Entry cost | 3 GB / $11.25/mo (residential); 100 MB / 3-day free trial | 5 GB / $5 |
| Residential pool | 115M+ IPs | 90M+ IPs |
| Protocol support | HTTP(S), SOCKS5 | HTTP, HTTPS, SOCKS5 |
| Traffic expiry | Subscription allocation resets monthly | Never expires |
| Targeting | Continent → ZIP/ASN level | Country included; city/state/ZIP/ASN paid |
| Proxy types | Residential, static ISP, datacenter (shared + dedicated), mobile, scraping API | Residential, datacenter, mobile, premium residential |
| Refunds | 14-day money-back on eligible subscriptions | 7-day refund for new users, per AIMultiple's write-up |
| Compliance | ISO/IEC 27001:2022, GDPR jurisdiction in the EU | Ethical-sourcing claims with first-party pools |

The pool size gap (115M vs 90M) looks meaningful until you factor in location distribution. A larger total pool doesn't help much if your target is one country and the coverage there is thin. Both providers publish 195+ country coverage, so the practical question is whether your specific target city or ASN has working IPs — a 5 GB test answers that more reliably than any spec sheet.

The bigger structural gap is product breadth. Decodo sells static ISP proxies and dedicated datacenter IPs, which is what you want for account management or long-lived sessions where the IP has to stay identical for weeks. DataImpulse doesn't sell those. If your project needs a fixed IP per account, DataImpulse isn't the tool, and no amount of price advantage fixes that.

Flip it around: if your project is rotating-IP web scraping — e-commerce monitoring, SERP collection, price comparison, ad verification, AI training data — the fixed-IP products are irrelevant to you, and paying subscription rates for rotating residential traffic is a choice you don't have to make.

👉 [Compare the plan tiers directly](https://bit.ly/dataimPulse)

## How to test this without wasting money

The instinct is to buy the smallest plan and run a few requests. That tells you almost nothing. What matters is cost per *successful* request, and that number moves a lot between pools.

A practical sequence:

1. **Pick one hard target.** Not a website that blocks nothing. Pick the specific site you actually need — the one returning 403s.
2. **Buy the cheapest entry tier.** DataImpulse's 5 GB residential is $5. Decodo's free trial is 100 MB over 3 days, which is enough for a smoke test but not a real measurement.
3. **Run a fixed batch.** A thousand requests with sticky sessions is a reasonable sample. Log success rate and average page size.
4. **Do the maths.** 1,000 pages at 500 KB average is roughly 500 MB, or about $0.50 at $1/GB. If 95% succeed, your real cost lands near $0.53 per 1,000 usable pages.
5. **Only then scale.** Volume tiers drop to $0.80/GB at 1 TB and $0.70/GB at 5 TB, but those numbers mean nothing if your success rate on the target is poor.

That last point is the one most per-GB comparisons skip. A pool at $0.50/GB that gets blocked half the time costs more per usable record than a clean pool at $1/GB. Price per GB is an input, not a verdict.

👉 [Start with 5 GB for $5 and measure your own success rate](https://bit.ly/dataimPulse)

## Questions that come up a lot

**Is Decodo the same as Smartproxy?**
Yes. Smartproxy rebranded to Decodo. Same company, same infrastructure, different name. Existing accounts and integrations carried over.

**Is Decodo a good proxy provider?**
By third-party coverage, the sourcing and consent practices hold up under scrutiny, and review benchmarks rate residential performance near the top tier. The consistent criticism is cost at low volume — TechRadar's reviewers found the price tags hard to justify for solo projects and small operations.

**What's cheaper than Decodo for residential traffic?**
DataImpulse's $1/GB pay-as-you-go is well below Decodo's $3.75–$4.00/GB entry rates. Whether it's cheaper *for your job* depends on success rate on your target, which is why the test above matters more than the sticker price.

**Does DataImpulse traffic expire?**
No. Purchased GBs stay in the account. That's the main practical difference from subscription plans, where an unused allocation resets at the end of the billing period.

**Can I keep using my current scraping setup?**
Both providers speak HTTP, HTTPS and SOCKS5, so anything that accepts a standard proxy endpoint — Python requests, Playwright, Puppeteer, Go, PHP, Java — works without rewriting your scraper. DataImpulse also publishes integration tutorials for common multi-account and automation tools.

## Which one, then

If you need static ISP proxies, dedicated datacenter IPs, or a managed scraping API with browser rendering, Decodo is the broader product and the price discussion is secondary. It's also the more established operation — bigger pool, ISO certification, a Chrome extension, and a longer published refund window.

If you're doing rotating residential or mobile work and your volume is uneven month to month, the subscription model is where the money goes. DataImpulse's pay-as-you-go pricing with non-expiring traffic exists precisely for that shape of workload: $1/GB residential, $0.50/GB datacenter, $2/GB mobile, no monthly commitment, and no penalty for buying small the first time.

The sensible move is to spend $5 on the entry tier, run it against the target that's actually blocking you, and decide using your own success rate. That's a more useful number than anything on either pricing page.

👉 [Open the DataImpulse dashboard and test it against your own target](https://bit.ly/dataimPulse)

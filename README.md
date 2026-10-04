# non expiring residential proxies: why pay-as-you-go IP and GB balances work differently, and how 9Proxy stacks up

Most people who type this phrase into Google have the same scar tissue. They bought 50 GB of residential traffic, used 12 GB on a two-week scraping job, and watched the remaining 38 GB evaporate when the billing cycle rolled over. Or they bought a block of IPs on a subscription, needed 200 of them for three days, and paid for the other 27 days anyway.

So the question underneath the keyword isn't really "which proxy provider is cheapest." It's "which pricing model stops punishing me for having an irregular workload." Those are different problems, and only some providers solve the second one.

## "Non expiring" is three different promises wearing the same phrase

Providers use the word loosely, so it helps to separate what's actually being sold.

**1. A traffic balance that rolls over.** You buy gigabytes, they sit on your account, and nothing resets on the 1st of the month. IPRoyal states plainly that purchased residential traffic "never expires" and stays yours, and MarsProxies describes the same idea as traffic rollover with no duration restrictions.

**2. Unused IPs that carry forward.** This is a different animal. You buy a fixed block of residential IPs (say 5,000), and each one is deducted from your balance only when you actually activate it. The block doesn't have a monthly deadline attached.

**3. No bandwidth meter at all.** Per-IP billing with unlimited data per IP. You're not buying gigabytes, so there's nothing to expire in the first place. This is the model 9Proxy built its business on.

The distinction matters because a provider can honestly advertise "traffic that doesn't expire" and still attach a 180-day validity window to it. That's not a scam — it's a different contract, and it should change what you buy.

## The monthly bucket is the wrong shape for most real projects

Here's the arithmetic that drives people to search for non-expiring options.

A subscription at a fixed monthly GB allowance only makes sense if your consumption is flat. Scraping projects are rarely flat. A product-launch monitoring job burns 40 GB in the week around the launch and almost nothing for the next three. An agency running five clients goes quiet in one month and frantic in the next. Under a monthly bucket, every quiet month is money donated to the provider.

Prepaid balances flip that. If you under-use one month, the gigabytes are still there next month. If you over-use, you top up. The only real question is whether the provider puts a clock on the balance — and how long that clock is.

This is where 9Proxy gets interesting, and also where a lot of thin affiliate reviews gloss over the details.

## Where 9Proxy actually stands on expiry

9Proxy runs two completely separate residential products, and they follow different expiry rules. Reading one review and assuming the rules apply to both is how people get surprised at checkout.

**Residential Proxy by IPs.** You pay per IP instead of per gigabyte, and bandwidth per IP is unlimited — there's no GB counter to watch. Unused IPs stay on your balance indefinitely; 9Proxy's own documentation says plainly that unused IPs never expire and your balance only decreases when you activate one. What you're really buying is a set number of parallel IP slots. Each IP lives a natural residential lifespan — anywhere from a few hours to roughly 24 hours — and can be rotated on custom intervals through the Auto Rotation Proxy on selected ports. This model requires the 9Proxy desktop app for local port forwarding, which is worth knowing before you commit if your workflow is API-first.

**Residential Proxy by GB.** Pay per gigabyte, generate unlimited endpoints, rotate per request or hold a sticky session, and authenticate with username/password or an IP whitelist — no desktop app needed. The twist: standard GB packages carry a **180-day validity window**. Traffic on Enterprise GB packages (3,000 GB and up) is unlimited validity and never expires. So if your headline requirement is literally "traffic that never expires," the GB path only gets you there at the top of the range, or through the per-IP path.

**Bundle packages.** IPs plus bandwidth in one purchase, aimed at teams that need both stable sessions and flexible rotation. Bundled traffic runs on the same 180-day clock.

Across both models: 20M+ residential IPs, 90+ countries, targeting down to country, city, ZIP code and ISP, and HTTP/HTTPS plus SOCKS5 support.

One pricing note that matters more than any coupon. 9Proxy announced on 18 May that it was raising prices for the first time in its history — IP-Based Packages and Bundle Packages went up on 1 June 2026, while GB-Based Package prices were explicitly left alone. Third-party trackers now list the network at roughly $0.018 per IP at the top tier and $0.02/GB on the directory side. Translation: if you buy IP blocks, the numbers you saw in an older review are stale.

## The full 9Proxy price list, including the expiry column

These are the packages currently published, consolidated so you can see the expiry terms next to the price rather than buried in a FAQ.

| Package | Model | Price | Effective rate | Expiry terms | Get it |
| --- | --- | --- | --- | --- | --- |
| 100 IPs | Per IP, unlimited bandwidth | $24 | $0.24/IP | Unused IPs never expire | [ View the 100 IP plan](https://bit.ly/9-Proxy) |
| 500 IPs | Per IP, unlimited bandwidth | $72 | $0.144/IP | Unused IPs never expire | [ Check the 500 IP plan](https://bit.ly/9-Proxy) |
| 1,000 IPs + 500 bonus | Per IP, unlimited bandwidth | $126 | ~$0.084/IP | Unused IPs never expire | [ See the 1,000 + 500 IP plan](https://bit.ly/9-Proxy) |
| 2,500 IPs | Per IP, unlimited bandwidth | $210 | ~$0.084/IP | Unused IPs never expire | [ View the 2,500 IP plan](https://bit.ly/9-Proxy) |
| 5,000 IPs | Per IP, unlimited bandwidth | $360 | ~$0.072/IP | Unused IPs never expire | [ Check the 5,000 IP plan](https://bit.ly/9-Proxy) |
| 15,000 IPs | Per IP, unlimited bandwidth | $720 | ~$0.048/IP | Unused IPs never expire | [ See the 15,000 IP plan](https://bit.ly/9-Proxy) |
| 25,000 IPs | Per IP, unlimited bandwidth | $863 | ~$0.035/IP | Unused IPs never expire | [ View the 25,000 IP plan](https://bit.ly/9-Proxy) |
| 50,000 IPs | Per IP, unlimited bandwidth | $1,438 | ~$0.029/IP | Unused IPs never expire | [ Check the 50,000 IP plan](https://bit.ly/9-Proxy) |
| 100,000 IPs | Business per IP | $2,300 | ~$0.023/IP | Unused IPs never expire | [ See the 100,000 IP plan](https://bit.ly/9-Proxy) |
| 200,000 IPs | Business per IP | $4,140 | ~$0.021/IP | Unused IPs never expire | [ View the 200,000 IP plan](https://bit.ly/9-Proxy) |
| 500,000 IPs | Business per IP | $8,625 | ~$0.018/IP | Unused IPs never expire | [ Check the 500,000 IP plan](https://bit.ly/9-Proxy) |
| 5 GB | Per GB | $15 | $3.00/GB | 180 days | [ View the 5 GB pack](https://bit.ly/9-Proxy) |
| 50 GB + 5 GB bonus | Per GB | $105 | $2.10/GB | 180 days | [ Check the 50 GB pack](https://bit.ly/9-Proxy) |
| 100 GB | Per GB | $150 | $1.50/GB | 180 days | [ View the 100 GB pack](https://bit.ly/9-Proxy) |
| 200 GB | Per GB | $200 | $1.00/GB | 180 days | [ Check the 200 GB pack](https://bit.ly/9-Proxy) |
| 1,000 GB | Per GB | $800 | $0.80/GB | 180 days | [ View the 1,000 GB pack](https://bit.ly/9-Proxy) |
| 2,000 GB | Per GB | $1,500 | $0.75/GB | 180 days | [ Check the 2,000 GB pack](https://bit.ly/9-Proxy) |
| 3,000 GB | Enterprise GB | $2,160 | $0.72/GB | Unlimited validity | [ See the 3,000 GB pack](https://bit.ly/9-Proxy) |
| 6,000 GB | Enterprise GB | $4,200 | $0.70/GB | Unlimited validity | [ View the 6,000 GB pack](https://bit.ly/9-Proxy) |
| 10,000 GB | Enterprise GB | $6,800 | $0.68/GB | Unlimited validity | [ Check the 10,000 GB pack](https://bit.ly/9-Proxy) |
| Starter Bundle — 100 IPs + 5 GB | IP + GB bundle | $30 | — | IPs never expire, traffic 180 days | [ View the Starter Bundle](https://bit.ly/9-Proxy) |
| Popular Bundle — 1,500 IPs + 50 GB | IP + GB bundle | $180 | — | IPs never expire, traffic 180 days | [ Check the Popular Bundle](https://bit.ly/9-Proxy) |
| Pro Bundle — 5,000 IPs + 500 GB | IP + GB bundle | $720 | — | IPs never expire, traffic 180 days | [ View the Pro Bundle](https://bit.ly/9-Proxy) |

A quick sanity check on the GB ladder: the 5 GB pack costs $3.00/GB and the 100 GB pack costs $1.50/GB. Buying the 100 GB pack saves money per gigabyte, but only if you can burn it inside 180 days. If your realistic consumption is 10 GB a quarter, the small pack costs more per gigabyte and less per year of actual usage. That's the trade-off the expiry column exists to expose.

## Per-IP, per-GB, or bundle — pick by how your workload behaves

The three models aren't tiers of quality. They're shapes, and one of them will fit your job better than the others.

**Go per-IP if sessions need to persist.** Logged-in account work, multi-account management with antidetect browsers, shopping carts, anything where breaking the session triggers a challenge. Unlimited bandwidth per IP also means a data-heavy job costs the same whether you pull one page or ten thousand through that address. Budget for the desktop app requirement and accept the hours-to-24h IP lifespan.

**Go per-GB if you rotate hard and use little data per request.** Price monitoring, SERP checks, ad verification, geo-testing, API polling. Endpoints are unlimited here, so rotating through thousands of IPs doesn't cost extra — only the traffic does. The 180-day window is generous for most project work but it isn't forever, so treat large prepayments as a bet on your own pipeline.

**Go bundle if your workload is genuinely mixed.** An agency running stable sessions for two clients and rotation-heavy scraping for three others is the exact shape these packages were built for. The Pro Bundle at $720 lists against $860, a $140 discount, and pairs 5,000 IPs with 500 GB of traffic.

If you want to compare the three side by side before deciding, the full package list and current rates live on 👉 [👉 See 9Proxy's full pricing and package options](https://bit.ly/9-Proxy).

## The fine print worth reading before you top up

A few things trip people up, and they're worth knowing upfront rather than discovering at month three.

- **"Non-expiring" applies to different products differently.** Per-IP balances don't expire. Standard GB packs and bundle traffic run on 180 days. Only Enterprise GB is truly open-ended.
- **Residential IPs have a lifespan.** Hours to about 24 hours, natural residential uptime. Anyone promising permanent sticky residential IPs is selling something else.
- **The per-IP model needs the desktop app.** Local port forwarding plus optional proxy authentication. If you need pure dashboard or API access, that's the GB model instead.
- **Prices moved on 1 June 2026** for IP-based and bundle packages. GB pricing held. Reviews written before that date quote lower IP rates.
- **Test before scaling.** Geekflare's 2026 review notes that you can request a test balance and run it against your own targets before committing spend — which is the only benchmark that reflects your actual success rate.
- **Buy from the official dashboard if you care about continuity.** Third-party resellers do sell 9Proxy activation keys, sometimes at a discount, but your support and replacement path runs through that reseller, not 9Proxy.

## Other providers that don't expire your traffic

Worth knowing, because the "no expiry" pitch isn't unique to one company anymore.

IPRoyal sells residential traffic that stays on your account forever, across 64M+ IPs in 195+ countries, with sticky sessions up to seven days. IP2World advertises traffic that never expires, packages from a $2 single-gigabyte trial up to 1,000 GB at $1,049, and effective rates dropping to $0.70/GB at volume. MarsProxies rolls unused traffic over indefinitely at residential rates starting around $1.65/GB. ProxyWing describes non-expiring residential traffic from $0.87/IP. DataImpulse pushes a pay-as-you-go model at roughly $1/GB where credits stay put.

The pattern is consistent: the market has moved away from monthly buckets, and the differentiator is now the length of the validity window plus how the provider meters usage. 9Proxy's edge is the per-IP unlimited-bandwidth structure and the low per-IP entry price; the honest catch is that its GB packages do carry a 180-day clock unless you're buying at the Enterprise level.

## FAQ

**Does 9Proxy's residential traffic expire?**
Per-IP balances don't — unused IPs stay on your account until activated. Standard GB packages and bundle traffic are valid for 180 days. Enterprise GB packages (3,000 GB and above) carry unlimited validity.

**Can I buy gigabytes instead of IPs?**
Yes. The GB model bills by traffic with unlimited endpoints, and it's the one that doesn't require the desktop app.

**How long does each residential IP last?**
A few hours up to roughly 24 hours, which is normal for real residential addresses. On per-IP plans you can also rotate on custom intervals using the Auto Rotation Proxy.

**Is there a monthly fee?**
No. Both models are prepaid and usage-based. You top up a balance and spend it at your own pace — which is exactly the point of searching for non-expiring proxies in the first place.

**Where does it work?**
Writing scrapers, monitoring prices and SERPs, verifying ads, checking localised search results, managing multiple accounts, and market research are the documented use cases. Country, city, ZIP and ISP targeting are supported across the pool, with HTTP/HTTPS and SOCKS5 protocols.

## The short version

If your only requirement is that purchased traffic never vanishes, the honest answer is that per-IP balances at 9Proxy and IPRoyal-style rollover providers deliver that cleanly, and 9Proxy's per-GB packages deliver a 180-day version of it unless you're buying Enterprise. If your workload is bursty and you hate paying subscription rent for months you don't use, prepaid per-IP with unlimited bandwidth is the structurally cheaper shape — the per-IP cost falls as low as $0.018 at volume, and there's no meter running while you work.

If that fits how you actually operate, start with a small block, test it against your real targets, and scale from there: 👉 [👉 Get started with 9Proxy's pay-as-you-go residential proxies](https://bit.ly/9-Proxy).

# los angeles vps server: how to pick a BandwagonHost plan without overpaying (full price list, CN2 GIA routes, and the fine print)

People searching for a **los angeles vps server** usually want one of two things. Either they need an affordable server on the US West Coast with decent specs, or they need LA specifically because it's where China Telecom's CN2 GIA, China Mobile's CMIN2, and China Unicom's premium networks all hand off — the shortest practical path between mainland China and the United States.

BandwagonHost (BWG, or 搬瓦工 in Chinese communities) is worth a look because it's one of the few providers that sells these route tiers as explicit, priced product lines: a $49.99/year general-purpose KVM plan, CN2 GIA plans from $49.99/quarter, and Hong Kong CN2 GIA at $89.99/month. The problem is the plan list. There are dozens of SKUs across Los Angeles, Hong Kong, Osaka, Tokyo, Singapore, and Dubai, several with confusingly similar names, plus traffic-counting rules that catch out first-time buyers.

Here's the short version, then the details.

> **Quick answer:** for most readers, the **CN2 GIA-E 20G** plan is the sensible default — 1 GB RAM, 2 cores, 20 GB SSD, 1 TB monthly traffic at 2.5 Gbps, $49.99/quarter or $169.99/year, switchable across the CN2 GIA data centers in the pool. If mainland China routes don't matter to you, the plain **20G KVM at $49.99/year** is cheaper and just as capable. 👉 [check the CN2 GIA-E 20G plan's current price](https://bandwagonhost.com/aff.php?aff=74518&pid=87)

## Every plan you can currently buy

All plans run KVM virtualization on BandwagonHost's own hardware and IP space, come with 1 dedicated IPv4 and a routed /64 IPv6 subnet, full root access, free automatic backups, free snapshots, instant rDNS updates, and the in-house KiwiVM control panel. The KVM PROMO line carries a 99.95% uptime guarantee; the SLA plans in LA DC5 carry 99.99%.

**Los Angeles and US core plans:**

| Plan | CPU / RAM / SSD | Traffic / Port | Price | Order |
| --- | --- | --- | --- | --- |
| 20G KVM | 2 cores / 1 GB / 20 GB | 1 TB @ 1 Gbps | $49.99/yr | [order the 20G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=44) |
| 40G KVM | 3 cores / 2 GB / 40 GB | 2 TB @ 1 Gbps | $52.99/6 mo · $99.99/yr | [order the 40G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=45) |
| 80G KVM | 4 cores / 4 GB / 80 GB | 3 TB @ 1 Gbps | $19.99/mo · $199.99/yr | [order the 80G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=46) |
| 160G KVM | 5 cores / 8 GB / 160 GB | 4 TB @ 1 Gbps | $39.99/mo · $399.99/yr | [order the 160G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=47) |
| 320G KVM | 6 cores / 16 GB / 320 GB | 5 TB @ 1 Gbps | $79.99/mo · $799.99/yr | [order the 320G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=48) |
| 480G KVM | 7 cores / 24 GB / 480 GB | 6 TB @ 1 Gbps | $119.99/mo · $1199.99/yr | [order the 480G KVM plan](https://bandwagonhost.com/aff.php?aff=74518&pid=49) |
| CN2 GIA-E 20G | 2 cores / 1 GB / 20 GB | 1 TB @ 2.5 Gbps | $49.99/qtr · $169.99/yr | [order the GIA-E 20G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=87) |
| CN2 GIA-E 40G | 3 cores / 2 GB / 40 GB | 2 TB @ 2.5 Gbps | $89.99/qtr · $299.99/yr | [order the GIA-E 40G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=88) |
| CN2 GIA-E 80G | 4 cores / 4 GB / 80 GB | 3 TB @ 2.5 Gbps | $56.99/mo · $549.99/yr | [order the GIA-E 80G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=89) |
| CN2 GIA-E 160G | 6 cores / 8 GB / 160 GB | 5 TB @ 5 Gbps | $86.99/mo · $879.99/yr | [order the GIA-E 160G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=90) |
| CN2 GIA-E 320G | 8 cores / 16 GB / 320 GB | 8 TB @ 5 Gbps | $159.99/mo · $1599.99/yr | [order the GIA-E 320G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=91) |
| CN2 GIA-E 640G | 10 cores / 32 GB / 640 GB | 10 TB @ 10 Gbps | $289.99/mo · $2759.99/yr | [order the GIA-E 640G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=92) |
| CN2 GIA-E 1280G | 12 cores / 64 GB / 1280 GB | 12 TB @ 10 Gbps | $549.99/mo · $5399.99/yr | [order the GIA-E 1280G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=93) |
| DC5 SLA 20G | 2 dedicated cores / 1 GB ECC / 20 GB NVMe | 1 TB @ 2.5 Gbps | $65.89/qtr · $239.99/yr | [order the SLA 20G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=164) |
| DC5 SLA 40G | 3 dedicated cores / 2 GB / 40 GB | 2 TB @ 2.5 Gbps | $116.99/qtr · $399.99/yr | [order the SLA 40G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=165) |

On the GIA-E plans, the control panel tags five US and Canadian E-Commerce data centers as CN2GIA-E — Los Angeles DC6 and DC9, San Jose, New York, and Vancouver. Third-party plan listings also show Japan SoftBank (JPOS_1 in Osaka) and a Netherlands 9929 location among the switch options on the entry tier. The exact pool can vary by plan, so check the "Migrate to another DC" page in KiwiVM before you buy; DC6 and DC9 are GIA-only rooms, while the plain KVM plans default to LA DC2 and can move across nine US, Canadian, and European data centers.

**Asia and other regions** — these matter if China or Asia latency is your actual goal:

| Plan | CPU / RAM / SSD | Traffic / Port | Location | Price | Order |
| --- | --- | --- | --- | --- | --- |
| HK/Tokyo 40G | 2 cores / 2 GB / 40 GB | 500 GB @ 1 Gbps | HK, Tokyo, Osaka, or Singapore CN2 GIA (switchable) | $89.99/mo · $899.99/yr | [order the HK/Tokyo 40G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=95) |
| HK 80G | 4 cores / 4 GB / 80 GB | 1 TB @ 1 Gbps | Hong Kong | $155.99/mo | [order the HK 80G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=96) |
| Osaka 40G | 2 cores / 2 GB / 40 GB | 500 GB @ 1.5 Gbps | Osaka (Equinix) | $49.99/mo · $499.99/yr | [order the Osaka 40G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=134) |
| Osaka 80G | 4 cores / 4 GB / 80 GB | 1 TB @ 1.5 Gbps | Osaka | $86.99/mo · $869.99/yr | [order the Osaka 80G plan](https://bandwagonhost.com/aff.php?aff=74518&pid=135) |
| Singapore 40G–1280G | 2–12 cores / 2–64 GB / 40–1280 GB | 0.5–8 TB @ 1.5–5 Gbps | Singapore (Equinix SG1) | $49.99–$1059.99/mo | [see the Singapore CN2 GIA specials](https://bit.ly/BandwaGon) |
| Dubai E-Commerce 20G / 40G | 2–3 cores / 1–2 GB / 20–40 GB | 500 GB–1 TB @ 1 Gbps | Dubai, UAE | $19.99/mo · $32.99/mo | [see Dubai plans and current pricing](https://bit.ly/BandwaGon) |

Prices are in USD. Payment options include Alipay and PayPal. Hot tiers — especially Hong Kong — sell out regularly and restock unpredictably, so a listed price only means something when there's inventory, and the larger Hong Kong tiers beyond the 80G plan appear on the order page only while stock lasts.

## CN2 GIA vs regular transit: what the extra money actually buys

The route is the product. DC6 sits in Digital Realty's LAX10 facility and DC9 in CoreSite LA2, and both list three premium China routes: China Telecom CN2 GIA, China Mobile CMIN2, and China Unicom Premium. DC9 runs AMD EPYC processors with NVMe storage as of July 2025, and BandwagonHost describes it as offering the best overall network capacity and stability. DC9 sends all China-bound traffic over those three premium routes.

Independent testing backs the claim up, at least partially. September 2026 tests measured DC6 at 500–650 Mbit/s with roughly 0% packet loss for China Telecom and China Unicom during the evening peak — the hours when ordinary international routes usually fall apart. Off-peak, the CN2 GIA sites performed close to a non-CN2 location, which tells you the premium is really about peak-hour stability.

A couple of naming notes, because they confuse people. "CN2 GIA-E" is a BandwagonHost coinage, inherited from the DC6 plan name "CN2 GIA ECOMMERCE" from 2019; China Telecom doesn't use the term. And when one reviewer checked BandwagonHost's data center list in October 2026, none of the locations were labeled CN2 GT anymore — the premium China Telecom routes on sale are CN2 GIA and CTGNet. Older articles describing a separate "CN2 GT" tier describe a lineup that has since shifted, though the DC3 room's special traffic rule (more on that below) is a leftover of that old structure.

## The real cost after the first billing cycle

Renewal prices equal signup prices at BandwagonHost — there's no teaser-rate game — but the billing cycle you choose changes the math.

- The GIA-E 20G costs $49.99/quarter or $169.99/year. Two quarters plus one quarter adds up to $199.96, so paying annually saves about **$30 a year** on the identical plan.
- The 1 GB and 2 GB KVM tiers are **annual-only or semi-annual-only** — there's no monthly billing below the 4 GB tier. That's part of why the headline $49.99/year looks so low.
- Monthly billing unlocks from the 4 GB/80G tier upward. If you want to test before committing, $19.99 for one month of the 80G KVM is your cheapest exit-friendly option.
- On the GIA-E side, the 20G and 40G tiers have no monthly option at all; the cheapest monthly-billed CN2 GIA plan is the 80G at $56.99/month.

One comparison worth spelling out, because it's the decision most buyers actually face: the Basic 20G KVM and the CN2 GIA-E 20G have identical specs (2 cores, 1 GB, 20 GB, 1 TB) but the GIA-E costs $120 more per year. That $120 buys the 2.5 Gbps port and the three premium China routes. If your traffic touches mainland China, it's the difference between an evening-peak connection that works and one that doesn't. If it doesn't, keep the $120.

👉 [compare the KVM and GIA-E lineups on the order page](https://bandwagonhost.com/aff.php?aff=74518&pid=87)

## The traffic rules that surprise new owners

BandwagonHost counts traffic differently from many providers in two ways, and both show up in support questions constantly.

First, traffic is **bidirectional**: inbound and outbound both draw from your quota. Download a 1 GB file, you've used 1 GB. Serve 1 GB out, another 1 GB gone. For a normal website this barely matters since visitor traffic is mostly outbound, but for a proxy or anything that pushes and pulls equally, your usable volume is effectively half the headline number.

Second, the quota resets on your **purchase anniversary date**, not on the first of the month. Buy on the 13th and your cycle runs from the 13th to the 12th; the KiwiVM panel shows the exact reset date on its main page. Unused traffic doesn't roll over.

What happens when you run out is straightforward and free: the VPS gets suspended until the next reset, with an email warning at 80% usage. If downtime is unacceptable, the only immediate fix is upgrading to a larger plan through the client area — the difference is prorated and the suspension lifts right away.

And then there's the famous one-third puzzle. KVM plans can be migrated into CN2-optimized data centers, and the cost of that route is your monthly traffic dropping to one-third of the plan quota — a 1 TB plan becomes roughly 333 GB while you're parked there, because premium CN2 bandwidth costs the provider far more than regular transit. The panel shows the traffic ratio for each data center before you migrate, so read it. If you want CN2 routing with full traffic, the correct product is a GIA-E plan rather than a migrated KVM plan. One caveat: recent checks of the data center list no longer show rooms explicitly labeled CN2 GT, so verify the current room list and its traffic ratios in KiwiVM before counting on any specific location.

## The limits that only show up in the fine print

A few more conditions come straight from the service terms and plan specs.

1. **CPU caps on shared plans.** Except for the DC5 SLA plans, entry E-Commerce tiers and the Hong Kong/Tokyo 40G plan are capped at an average single-core 100% load measured over one-hour windows. Bursts are fine; a sustained full-core workload will get throttled. The SLA plans use dedicated AMD cores with ECC memory and no CPU limit, which is a real part of what the extra ~$16/quarter buys.
2. **Migration traffic counts.** Data-center switches are free and don't lose data, but the data moved during migration draws from your monthly transfer, and since May 2024 the amount a single migration can carry has been reduced. If your disk is nearly full on the 20G plan, plan the move accordingly.
3. **Refund conditions are narrow.** New orders can be refunded within 30 days only if you've used less than 10% of the monthly transfer and your IP isn't on a blocklist. Burn through bandwidth in week one and you've waived the guarantee.
4. **Open proxies and Tor relays are banned.** VPN usage is explicitly supported — every plan lists "PPP and VPN support (tun/tap)" — but the terms prohibit open proxies and Tor relay nodes.
5. **It's strictly self-managed.** You get KiwiVM, an emergency console, snapshots, and an API. Nobody is going to fix your misconfigured nginx.

About discount codes: they exist but are volatile. Most standing codes as of mid-2026 were expired or pulled — including an 11% code from November 2025 and a 6.77% code floated in early 2026 that was withdrawn within about two days. Reliable patterns historically include 10–11% recurring codes around Black Friday and November 11. One October 2026 listing still carried a 6.77% recurring code, BWHCGLUKKB, while an August source said no regular codes were active. Codes are recurring — they apply to renewals too — so it's worth pasting one in at checkout to see if it's accepted, but don't plan your budget around it.

## How this compares with other LA VPS providers

If you just want the cheapest LA box, competitors undercut BandwagonHost's KVM line. RackNerd expanded KVM VPS service to a Los Angeles DC-03 location in March 2025 and runs aggressive first-cycle promotions. is*hosting sells LA plans from $5.94/month on 1 Gbps, with 2–3 TB on entry tiers and unmetered traffic from Medium up. Cloudzy includes a dedicated static IPv4 with every plan and avoids NAT-shared IPs. ExtraVM hosts its LA fleet at Digital Realty's BUR10 facility in Burbank, a Tier-IV carrier-neutral site. Bloom.Host sells dedicated Ryzen 9 9950X VPS in LA with resource-exclusive, non-oversold cores, no fair-usage CPU policy, and Cloudflare Magic Transit DDoS protection rated above 400 Tbps; its 8 GB Performance Plus tier lists at $30/month with 120 GB NVMe and 4 TB of traffic. EDIS Global operates from QuadraNet in downtown LA.

The honest framing: those providers compete on price and hardware specs, and for a generic West Coast server they'll often give you more RAM per dollar. What almost none of them sell as a standard product tier is dedicated CN2 GIA and CMIN2 routing into mainland China. That's the specific thing you're paying BandwagonHost for. If China routes are irrelevant to you, buy the cheap generic option instead — it's the right call.

## Which plan for which reader

- **General server, no China traffic** → 20G KVM, $49.99/year. Don't pay for routes you won't use.
- **Website or service accessed from mainland China** → CN2 GIA-E 20G, $49.99/quarter. The multi-DC switch pool and 2.5 Gbps port make it the plan long-term users keep recommending.
- **Business-critical, needs predictable CPU** → DC5 SLA 20G, $65.89/quarter: dedicated cores, ECC RAM, NVMe, 99.99% guarantee.
- **Latency above all, budget secondary** → Hong Kong CN2 GIA at $89.99/month, or Osaka at $49.99/month for half the price with a faster port. Osaka's 500 GB quota is the constraint to check.
- **Short experiment, might abandon it** → 80G KVM monthly at $19.99, since it's the cheapest plan with monthly billing.

## Before you click buy

Three quick checks. First, inventory — Hong Kong and some GIA tiers restock unpredictably, so if the order page shows a plan as sold out, no amount of patience at checkout will fix it. Second, register with realistic details and no proxy running; orders flagged as fraudulent get auto-refunded, and you'd rather deploy today than wait out a refund cycle. Third, if you're torn between the 20G KVM and the GIA-E 20G, decide based on where your users are — the specs are identical, and the route is the only real difference. Also remember traffic counts both ways, so proxy-style usage will burn a 1 TB quota roughly twice as fast as a plain website will.

If the answer to "where are your users" includes mainland China, the GIA-E 20G at $49.99/quarter is the plan to start with. 👉 [pick your plan on the BandwagonHost order page](https://bit.ly/BandwaGon)

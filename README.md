# RackNerd Black Friday 2026: When It Starts, What Last Year Cost, and Whether Waiting Two Weeks Saves You $11

RackNerd's Black Friday 2026 falls on Friday, November 27, and the company has not announced a single plan or price for it yet. Third-party trackers that poll the store around the clock put the countdown at 00:00 UTC on the 27th, with the sale window listed as November 27 through December 2 to include Cyber Monday on November 30. Those same trackers note that last year the sale opened roughly a week early, so the practical move is to start checking around November 20 instead of waiting for the holiday itself.

What you can buy today is the standard VPS specials lineup: five KVM plans from **$21.99 to $119.99 per year**, all annual billing, all renewing at the same rate for as long as you keep the server. That renewal detail is the part worth holding onto while you decide whether to wait, because a Black Friday price you only get once is a different deal from a price you keep.

> **Most readers should take the 2 GB plan at $35.99/year.** RackNerd marks it "Most popular," it gives 2 vCPU / 35 GB SSD / 5 TB of monthly transfer, and it's the cheapest tier that clears the 2 GB memory floor the company lists for n8n and Coolify. 👉 [check the current 2 GB KVM VPS price](https://bit.ly/RacKnerd)
>
> Running only a DNS resolver, an uptime probe or a small WireGuard node? The 1 GB at $21.99/year covers it. Planning to run Ollama or another local-model stack? Start at 4 GB.

## Every plan on the shelf right now

All five are KVM, annually billed, and include full root access, one IPv4 address, a 1Gbps port, and RackNerd's ctrl panel for reboots, OS reinstalls, an HTML5 VNC console, a network firewall and one-click app installs.

| Plan | vCPU · RAM · SSD | Monthly transfer | Price (annual) | Order |
| --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 vCPU · 1 GB · 20 GB | 3 TB | $21.99/yr | [get the 1 GB KVM VPS](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 vCPU · 2 GB · 35 GB | 5 TB | $35.99/yr | [get the 2 GB KVM VPS](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 3 vCPU · 4 GB · 60 GB | 7 TB | $59.99/yr | [get the 4 GB KVM VPS](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 vCPU · 6 GB · 100 GB | 12 TB | $89.99/yr | [get the 6 GB KVM VPS](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 vCPU · 8 GB · 150 GB | 20 TB | $119.99/yr | [get the 8 GB KVM VPS](https://bit.ly/RacKnerd) |

The jump from 4 GB to 6 GB costs $30 a year and doubles your core count. Unless you're running several services that each want their own CPU, that $30 buys headroom you probably won't touch.

## What Black Friday actually cost last year

This is the number that decides whether waiting makes sense. Third-party trackers recorded five Black Friday plans in 2025, and all of them are now sold out or delisted:

| 2025 Black Friday plan | Specs | BF price | Regular price | Gap |
| --- | --- | --- | --- | --- |
| 1 GB KVM | 1 CPU · 1 GB · 25 GB | $10.60/yr | $21.99/yr | −52% |
| 2.5 GB KVM | 2 CPU · 2.5 GB · 45 GB | $18.66/yr | $35.99/yr | −48% |
| 4 GB KVM | 3 CPU · 4 GB · 65 GB | $29.98/yr | $59.99/yr | −50% |
| 6 GB KVM | 5 CPU · 6 GB · 100 GB | $44.98/yr | $89.99/yr | −50% |
| 8 GB KVM | 6 CPU · 8 GB · 150 GB | $62.49/yr | $119.99/yr | −48% |

Note the small print on that table. The 2025 discounts were real, around half off across the board, but the plans weren't identical to the regular ones. The Black Friday 1 GB came with 25 GB of disk instead of 20 GB, and the 2.5 GB tier doesn't exist in the current lineup at all.

The longer trend is more useful than any single year:

- **2023:** 8 plans, lowest $10.18/year, 9 locations
- **2024:** 5 plans, lowest $10.99/year, 5 locations
- **2025:** 5 plans, lowest $10.60/year, 1 recorded location
- **Earlier years:** 21 plans; the $8.50 headline from that era was a 50 GB shared hosting plan, and the cheapest VPS was a 512 MB box at $8.89/year

Two things follow. Entry pricing has sat in a **$10 to $11 band for three straight years**, so a $8 VPS in 2026 is not a reasonable expectation. And the catalog has been shrinking, from 21 plans down to 5, with fewer locations recorded each year. A 2026 sale with five plans and a $10-ish entry point would be consistent with the pattern. A sale with a dozen plans would not.

## Waiting two weeks saves about $11, if you win the race

Do the arithmetic on the 1 GB tier. Regular price is $21.99. Last year's Black Friday price was $10.60. The difference is **$11.39 for the first year**, and if the discounted plan also renews at its own rate, roughly **$34 over three years**.

Scale it up and the gap grows: the 4 GB tier is $30.01 cheaper per year at Black Friday pricing, the 8 GB tier $57.50 cheaper.

Now weigh that against what waiting actually costs you. Last year's five plans are gone. The cheap tiers are the first to disappear, and community guides that have tracked these sales say the cheapest configuration routinely clears out within hours, with 1 GB and 2.5 GB showing "0 Available" in multiple locations by Cyber Monday. If you need a server running this week, the expected value of waiting is not $11.39, it's $11.39 multiplied by your chance of getting one before it sells out.

The rule that follows:

- **You need a box now** (a site to move, a service to deploy, a course project due) → buy a regular special today and stop reading sale threads.
- **You want cheap, you can wait, and losing the race costs you nothing** → wait for the 27th, or the few days before it, and treat it as a lottery ticket you might not win.

If you already know which tier you want, the current pricing is live and the servers provision instantly. 👉 [pick a KVM VPS at today's price](https://bit.ly/RacKnerd)

## Match the plan to what you're actually running

RackNerd publishes memory minimums for its one-click app catalog, and those minimums map cleanly onto the five plans.

**1 GB ($21.99/yr)** — one small site, a DNS resolver, an uptime probe, a WireGuard or Xray node, a single bot. Nothing with a database under load.

**2 GB ($35.99/yr)** — the entry point for n8n and Coolify, both listed as comfortable from 2 GB. Also fine for Docker plus Portainer with two or three light containers, or a small WordPress install on CyberPanel or CloudPanel.

**4 GB ($59.99/yr)** — the floor for Ollama, LibreChat, AnythingLLM and Hermes Agent. This is the tier to buy if you want a WordPress site with actual traffic plus a database, or a Docker host running a handful of services.

**6 GB ($89.99/yr)** — multiple sites, CI runners, several services doing real work at once.

**8 GB ($119.99/yr)** — the stated requirement for OpenClaw, which wants at least 8 GB. Nothing smaller will do.

The one-click catalog also covers Docker with Portainer, AdminBolt, CyberPanel and CloudPanel; anything not listed you install yourself over SSH with root access. 👉 [start with the 4 GB plan if you're running local models](https://bit.ly/RacKnerd)

## How the sale usually plays out

Black Friday at RackNerd is not a browsing experience. Past sales followed a recognizable shape, and the tactics below come from people who tracked them.

1. **Start checking a few days early.** Last year's sale opened about a week before the holiday. Flash sales appear with no warning at all and often clear within the hour.
2. **Pick your configuration and a backup datacenter in advance.** Los Angeles and New York are reported to sell out first. Having a second location in mind saves the two minutes that decides whether you get a box.
3. **Load the cart before you commit.** Multiple plans can sit in one cart, so a second server in another region doesn't require a second checkout.
4. **Pay with your fastest method.** Provisioning is immediate after payment clears, so the delay is entirely on your end.

## Three things to check before you pay

**It's unmanaged.** You get root and the ctrl panel for power, reinstalls, console access, firewall rules and root password resets. The OS, the stack, the updates and the backups are yours. If you want someone else to administer the server, this isn't that product.

**Renewal is the same price.** RackNerd's own FAQ states that these VPS specials are lifetime recurring and renew at the same rate for as long as you keep the service. That's worth more than a one-time discount, and it's the main reason the regular specials page is a legitimate place to buy rather than a placeholder until the sale.

**Refunds are the murky part.** RackNerd's official knowledgebase says the company does not offer refunds or a money-back guarantee, and immediate cancellation does not return what you paid. At least one coupon aggregator claims a 3-day window for new customers, which contradicts the official page. Treat the knowledgebase as the governing statement and read the terms yourself before ordering, especially if you're prepaying a year on a hunch.

Custom ISO installs are available by opening a support ticket. The standard OS list covers CentOS, Rocky Linux, AlmaLinux, Fedora, Debian and Ubuntu.

## FAQ

**When exactly does the RackNerd Black Friday 2026 sale start?**
The holiday is Friday, November 27, and the tracked sale window runs November 27 to December 2 with Cyber Monday on November 30. The countdown points at 00:00 UTC on the 27th, and last year the sale began roughly a week early. RackNerd sets its own start time and hasn't published one.

**Will the 1 GB plan be $10.60 again?**
Nobody outside RackNerd knows. The last three entry prices were $10.18, $10.99 and $10.60, so a figure between $10 and $11 is the pattern-consistent expectation. That's history, not a commitment from the company.

**Does the price go up on renewal?**
No. RackNerd's FAQ states these VPS specials are lifetime recurring at the same rate.

**Is it managed?**
No. It's an unmanaged KVM VPS with full root access and a control panel. Support handles the platform, not your applications.

**Can I run Docker, WordPress or Ollama on it?**
Docker with Portainer is a one-click install. WordPress works through AdminBolt, CyberPanel or CloudPanel, or your own stack over SSH. Ollama needs at least 4 GB of RAM, which means the $59.99 plan or higher.

## Which one to buy

Strip it down to a rule. A single small site, a DNS server, a monitoring probe or a VPN node → 1 GB at $21.99. Automation and container work (n8n, Coolify, a few Docker containers) → 2 GB at $35.99. Local models, a busier WordPress site, or a Docker host with several services → 4 GB at $59.99. OpenClaw, or several workloads sharing one box → 8 GB at $119.99. The 6 GB sits in a gap most people don't need.

Two checks before checkout: confirm your first-choice datacenter has stock, and decide whether you need a custom ISO, which requires a support ticket rather than a dropdown. Everything else provisions in minutes.

👉 [compare all five RackNerd KVM VPS plans and current prices](https://bit.ly/RacKnerd)

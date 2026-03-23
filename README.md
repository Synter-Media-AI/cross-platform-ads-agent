# Cross-Platform Ads MCP Starter Kit — Manage All Ad Platforms with AI

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: Multi-Platform](https://img.shields.io/badge/Platform-All%20Platforms-FF6B35)](https://syntermedia.ai)

**One agent, every ad platform.** Open this repo in Amp, Cursor, or VS Code and manage Google, Meta, LinkedIn, Microsoft, Reddit, TikTok, X, Amazon, Spotify, and The Trade Desk — all from a single chat window with unified reporting and cross-channel budget optimization.

---

## Why Cross-Platform Management?

Most businesses advertise on 3-5 platforms. Each platform has its own dashboard, its own metrics definitions, its own attribution model, and its own API. Comparing performance across platforms means opening 5 tabs, exporting 5 CSVs, normalizing the data in a spreadsheet, and spending 2 hours every Monday on reporting.

Meanwhile, budget allocation decisions that could save thousands — like shifting $2,000 from underperforming LinkedIn to high-ROAS Meta — take days instead of minutes because the data lives in silos.

A cross-platform AI agent collapses all these silos. One question — "Which platform has the best ROAS this month?" — and you get a normalized comparison across every channel.

**Best for:** Agencies managing multi-platform campaigns, marketing teams running 3+ ad channels, anyone who needs a unified view of advertising performance.

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Unified Reporting** | "Show me spend, ROAS, and CPA across all platforms for the last 30 days" |
| **Budget Reallocation** | "Move $2,000 from LinkedIn to Meta — Meta is outperforming 3x" |
| **Cross-Platform Comparison** | "Which platform has the lowest CPA for lead generation?" |
| **Weekly Summary** | "Generate my Monday morning report across all channels" |
| **Launch Campaigns** | "Launch the same promotion on Google, Meta, and LinkedIn simultaneously" |
| **Pause Underperformers** | "Pause any campaign with ROAS below 1.5x on any platform" |
| **Channel Attribution** | "How do customers interact across platforms before converting?" |
| **Anomaly Detection** | "Did anything unusual happen across my campaigns this week?" |
| **Budget Pacing** | "Am I on track to spend my full monthly budget across all platforms?" |
| **Competitive Intelligence** | "Compare our share of voice across Google and Meta" |

---

## Example Conversations

### 1. Monday Morning Cross-Platform Report

> **You:** Give me the weekly report.
>
> **Agent:** Here's your cross-platform performance for the last 7 days:
>
> **Overview:**
> | Platform | Spend | Revenue | ROAS | CPA | Conv. |
> |---|---|---|---|---|---|
> | Google Ads | $4,200 | $18,900 | **4.5x** | $28 | 150 |
> | Meta Ads | $3,800 | $15,200 | **4.0x** | $22 | 173 |
> | LinkedIn Ads | $2,500 | $4,250 | **1.7x** | $89 | 28 |
> | Microsoft Ads | $800 | $4,400 | **5.5x** | $19 | 42 |
> | TikTok Ads | $1,200 | $3,600 | **3.0x** | $15 | 80 |
> | **Total** | **$12,500** | **$46,350** | **3.7x** | **$26** | **473** |
>
> **Week-over-week changes:**
> - 📈 Microsoft Ads: ROAS up 38% (new campaign hitting stride)
> - 📈 TikTok: CPA down 22% (new creative winning)
> - 📉 LinkedIn: ROAS down 15% (investigate creative fatigue)
> - ➡️ Google & Meta: Stable
>
> **Action items:**
> 1. **Increase Microsoft budget.** 5.5x ROAS is your best performer but only 6% of spend. It can absorb $1,500-2,000 more.
> 2. **Investigate LinkedIn.** ROAS dropped from 2.0x to 1.7x. Likely creative fatigue — refresh creative or narrow audience.
> 3. **Scale TikTok.** CPA is the lowest ($15) and dropping. Increase budget by 20%.

### 2. Data-Driven Budget Reallocation

> **You:** I have $15,000/month total. How should I split it?
>
> **Agent:** Based on the last 60 days of performance data across all your platforms:
>
> **Current allocation vs Recommended:**
> | Platform | Current | Current ROAS | Recommended | Expected ROAS |
> |---|---|---|---|---|
> | Google Ads | $5,000 (33%) | 4.2x | $5,500 (37%) | 4.0x |
> | Meta Ads | $4,500 (30%) | 3.8x | $4,000 (27%) | 3.9x |
> | LinkedIn | $3,000 (20%) | 1.7x | $1,500 (10%) | 2.0x |
> | Microsoft | $1,000 (7%) | 5.5x | $2,000 (13%) | 4.8x |
> | TikTok | $1,500 (10%) | 3.0x | $2,000 (13%) | 2.8x |
>
> **Changes explained:**
> - **Microsoft +$1,000:** Your best ROAS (5.5x) is severely underfunded. Doubling the budget will still maintain strong returns.
> - **LinkedIn -$1,500:** At 1.7x ROAS, LinkedIn is barely profitable. Cut to just your best-performing ABM campaigns.
> - **TikTok +$500:** Lowest CPA and improving trends. Worth testing more budget.
> - **Google +$500:** Stable performer, can absorb incremental budget.
> - **Meta -$500:** Slight trim — reallocate to higher-ROAS channels.
>
> **Expected total impact:** Blended ROAS moves from 3.5x to 3.9x. That's an additional $6,000 in monthly revenue for the same $15,000 spend.

### 3. Same Campaign, Multiple Platforms

> **You:** We're launching a new product next week. I want ads on Google, Meta, and TikTok simultaneously.
>
> **Agent:** I'll create a coordinated launch across all three platforms. Here's the plan:
>
> **Google Ads:**
> - Search campaign: "new [product category]" keywords
> - PMax with product feed for Shopping
> - Budget: $40/day
>
> **Meta Ads:**
> - Advantage+ campaign with product images and lifestyle shots
> - Target: Lookalike audience from existing customers
> - Budget: $35/day
>
> **TikTok:**
> - In-Feed video ads (UGC style)
> - Target: Interest-based + broad (let algorithm optimize)
> - Budget: $25/day
>
> **Coordination rules:**
> - All campaigns launch at midnight PT on launch day
> - Consistent messaging across platforms (adapted for format)
> - Shared UTM parameters for cross-platform attribution in GA4
> - Daily check-ins for the first week: kill losers early, scale winners
>
> **Week 1 review cadence:**
> - Day 2: First data check (enough for directional signals)
> - Day 4: Kill any campaign with CPA 3x above target
> - Day 7: Full analysis — which platform won?
>
> Shall I create all three campaigns now?

### 4. Anomaly Detection Across Platforms

> **You:** Anything weird happen with my campaigns this week?
>
> **Agent:** Scanning all platforms for anomalies in the last 7 days...
>
> **🚨 Anomalies detected:**
>
> **1. Google Ads — Spend spike on Wednesday**
> - Campaign "Brand — Exact" spent $420 (normal: $80-120/day)
> - Cause: A competitor started bidding on your brand name, driving up CPCs by 3.5x
> - Action needed: Add competitor as negative keyword OR accept higher brand CPCs
>
> **2. Meta Ads — CTR drop on Friday**
> - Your top ad set CTR dropped from 2.1% to 0.7% overnight
> - Cause: Creative frequency hit 5.2 — classic creative fatigue
> - Action needed: Introduce 2-3 new creatives immediately
>
> **3. TikTok — 0 conversions Saturday-Sunday**
> - Platform shows clicks and views, but 0 purchases
> - Cause: Your TikTok Pixel stopped firing on Saturday at 2pm
> - Action needed: Check if a website deploy broke the pixel. Conversions likely happened but weren't tracked.
>
> **No anomalies on:** LinkedIn, Microsoft Ads (both performing within normal range).
>
> Want me to fix the TikTok Pixel and refresh the Meta creative?

### 5. Cross-Platform Attribution Analysis

> **You:** Are customers touching multiple platforms before converting?
>
> **Agent:** Let me analyze your GA4 multi-channel data cross-referenced with platform reports...
>
> **Conversion paths (last 30 days, 473 conversions):**
>
> | Path | Conversions | % | Avg Value |
> |---|---|---|---|
> | Google (direct) | 142 | 30% | $89 |
> | Meta (direct) | 118 | 25% | $72 |
> | Google → Meta → Convert | 67 | 14% | $124 |
> | Meta → Google → Convert | 48 | 10% | $108 |
> | TikTok → Meta → Convert | 31 | 7% | $95 |
> | LinkedIn → Google → Convert | 22 | 5% | $186 |
> | TikTok → Google → Convert | 18 | 4% | $102 |
> | 3+ platforms → Convert | 27 | 6% | $210 |
>
> **Key insight:** Multi-platform customers are worth more. Single-platform converters average $80, while customers who interact with 2+ platforms average $131 — **64% higher**.
>
> **The LinkedIn effect:** LinkedIn rarely converts directly, but LinkedIn → Google paths have the highest average value ($186). LinkedIn builds awareness among decision-makers who later search on Google to buy.
>
> **Budget implication:** Cutting LinkedIn would save $2,500/month but cost you ~$4,092/month in Google-attributed revenue from LinkedIn-initiated paths. Keep LinkedIn — it's the top-of-funnel driver for your highest-value conversions.

---

## Cross-Platform Tips from the Pros

1. **Start every Monday with a cross-platform report.** Normalize metrics across platforms (ROAS, CPA, CTR) to compare apples to apples. The agent does this automatically.
2. **Reallocate from worst to best ROAS channel.** Check monthly. If Microsoft is 5.5x ROAS and LinkedIn is 1.7x, shift budget. Most marketers leave money on the table by not rebalancing.
3. **Don't judge platforms in isolation.** LinkedIn might look expensive on last-click, but it initiates conversion paths completed on Google. Multi-touch attribution reveals the full picture.
4. **Coordinate launches.** When promoting the same product across platforms, use consistent messaging, shared UTMs, and synchronized timing.
5. **Set platform-specific KPIs.** Google = ROAS, LinkedIn = cost per SQL, TikTok = cost per video view, Meta = cost per purchase. Each platform excels at different things.
6. **Detect anomalies early.** A broken pixel, a competitor bidding on your brand, or creative fatigue — catching these in 1 day vs 1 week saves hundreds to thousands.
7. **Multi-platform customers are your best customers.** People who see your brand across multiple channels convert at higher rates and spend more. Cross-platform presence isn't waste — it's reinforcement.

---

## FAQ

### Is there a single MCP for all ad platforms?
Yes — this repo. It pre-configures the Synter MCP server with access to Google, Meta, LinkedIn, Microsoft, Reddit, TikTok, X, Amazon, Spotify, and The Trade Desk.

### Can one AI agent manage multiple ad platforms?
Yes. The Synter MCP provides unified access to all major platforms. Ask one question, get data from all channels.

### How does cross-platform budget reallocation work?
The agent compares ROAS, CPA, and other metrics across platforms and recommends moving budget from underperformers to top performers. You approve the changes before execution.

### Does this replace individual platform agents?
This repo gives you access to everything. The individual platform repos (google-ads-agent, meta-ads-agent, etc.) are focused entry points with platform-specific documentation.

### Can I launch campaigns on multiple platforms at once?
Yes. Describe your campaign once, and the agent creates platform-appropriate versions on Google, Meta, LinkedIn, or any combination you choose.

---

## Related Repos

Every platform has a dedicated repo with deeper documentation:
- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) · [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) · [linkedin-ads-agent](https://github.com/Synter-Media-AI/linkedin-ads-agent) · [microsoft-ads-agent](https://github.com/Synter-Media-AI/microsoft-ads-agent) · [reddit-ads-agent](https://github.com/Synter-Media-AI/reddit-ads-agent) · [tiktok-ads-agent](https://github.com/Synter-Media-AI/tiktok-ads-agent) · [x-ads-agent](https://github.com/Synter-Media-AI/x-ads-agent) · [amazon-ads-agent](https://github.com/Synter-Media-AI/amazon-ads-agent) · [spotify-ads-agent](https://github.com/Synter-Media-AI/spotify-ads-agent) · [trade-desk-agent](https://github.com/Synter-Media-AI/trade-desk-agent)

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)

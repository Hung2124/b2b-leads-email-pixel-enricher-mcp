![LeadForge AI — B2B Lead Finder, Verified Email, Ad Pixels & Tech Enricher](https://api.apify.com/v2/key-value-stores/b9rbebvrC82Huq8NJ/records/hero-banner-v3.png)

<p align="center">
  <img src="https://img.shields.io/badge/Engine-V3_Ultimate_HTTP%2F2-6366F1?style=for-the-badge" alt="Engine V3 Ultimate" />
  <img src="https://img.shields.io/badge/Zero_Cookies-No_Account_Ban_Risk-10B981?style=for-the-badge" alt="Zero Cookies" />
  <img src="https://img.shields.io/badge/Email_Check-Live_DNS_%2F_MX_%2F_DMARC-06B6D4?style=for-the-badge" alt="Live DNS MX DMARC" />
  <img src="https://img.shields.io/badge/Shopify-Sandbox_Pixel_Unpacker-EC4899?style=for-the-badge" alt="Shopify Sandbox Unpacker" />
  <img src="https://img.shields.io/badge/MCP_%26_Workflows-Clay_%E2%80%A2_n8n_%E2%80%A2_Make-F59E0B?style=for-the-badge" alt="MCP Ready" />
</p>

---

## ⚡ Turn Any Niche Keyword or Domain List Into Sales-Ready B2B Outreach Rows

Most contact scrapers on Apify only run a basic regex on a homepage and dump unverified `info@` emails or template junk (`sentry.io`, `example.com`).

**LeadForge AI — B2B Lead, Verified Email, Ad Pixels & Tech Enricher (V3 Ultimate)** is an **all-in-one outbound intelligence engine** built for **Marketing Agencies (SMMA), Cold Email Teams, SaaS Founders, Clay/n8n Builders, and Autonomous AI SDRs**. In a single high-speed asynchronous HTTP/2 pass (with automatic Chrome TLS JA3/JA4 fingerprint fallback and zero browser RAM overhead), it executes **6 high-ROI enrichment layers**:

1. **🔍 Auto-Discovery by Niche & City Keywords (No URLs Needed!)**: Type queries like `["cosmetic dentist Austin TX", "medspa Miami FL", "roofing contractor Dallas"]` and the Actor automatically discovers real business websites—filtering out 80+ directories (`Yelp`, `YellowPages`, `Healthgrades`, `TripAdvisor`) before enriching each company.
2. **👔 Decision-Maker, Executive Email & Direct Phone Extraction**: Crawls the homepage plus internal `/contact`, `/about`, `/team`, `/meet-the-doctor`, `/leadership`, and `/impressum` pages. Extracts **Decision Makers (Doctors, Founders, CEOs, Owners)**, generates **direct executive email patterns** (`bradford@austincosmetic.com`), decodes Cloudflare `data-cfemail` XOR protection, and extracts clean phone numbers + physical addresses.
3. **🛡️ Live DNS / MX / SPF / DMARC Deliverability Verification**: Queries Cloudflare DNS-over-HTTPS in real time to verify active MX mail servers, detect missing SPF/DMARC security policies, and fingerprint the exact email provider (**Google Workspace**, **Microsoft 365**, **Proofpoint**, **Mimecast**, **Zoho Mail**, **ProtonMail**, **Amazon SES**).
4. **🎯 Ad Pixel & Shopify Sandbox Unpacker**: Extracts exact tracking IDs—including pixels locked inside **Shopify's `webPixelsConfigList` Sandbox** that 99% of other scrapers miss (**Meta/Facebook Pixel ID**, **TikTok Pixel ID**, **Google Ads `AW-` Conversion ID**, **Google Merchant Center `MC-`**, **GTM**, **GA4**, **Pinterest**, **Snapchat**, **LinkedIn Insight**, **Microsoft Clarity**).
5. **🧰 55+ CMS, CRM, Local Booking & Live Shopify Product/Pricing Intel**: Fingerprints **Shopify** (plus live `/products.json` catalog pricing & flagship product names!), **WooCommerce**, **WordPress**, **Webflow**, **GoHighLevel (LeadConnector)**, **CallRail**, **Birdeye**, **Podium**, **NexHealth**, **Zocdoc**, **Mindbody**, **Boulevard**, **ServiceTitan**, **Jobber**, **Housecall Pro**, **Weave**, **Klaviyo**, **HubSpot**, **Intercom**, **Gorgias**, and **Zendesk**.
6. **✉️ Hyper-Personalized Subject Line, Cold Email Icebreaker & 15s Cold Call Opener**: Pinpoints high-ticket marketing gaps (e.g., *"Running Google Ads without a Meta or TikTok retargeting pixel"* or *"No AI chat / booking widget for after-hours traffic"*) and writes ready-to-send outreach copy mentioning the prospect's **exact decision-maker name, tech stack, or flagship Shopify product & price**!

---

## 🏆 Why Top Agencies Switch to LeadForge V3 Ultimate

| Feature / Capability | **✨ LeadForge V3 Ultimate** | Basic Contact Scrapers | Legacy Databases (Apollo / ZoomInfo) |
|---|---|---|---|
| **Auto-Discover Leads by Keyword + City** | ✅ **Built-in (`searchQueries`)** | ❌ Requires pre-scraped URLs | ✅ Yes (Stale cached records) |
| **Decision Maker Name & Role Extraction** | ✅ **Doctors, Founders, CEOs, Owners** | ❌ Generic emails only | ⚠️ Often outdated by 6–18 months |
| **Direct Executive Email Pattern Guess** | ✅ **`first@`, `f.last@` (MX-verified)** | ❌ No | ✅ Yes |
| **Live DNS / MX / SPF / DMARC + Google/M365 Check** | ✅ **100% Real-Time DoH Lookup** | ❌ No verification | ⚠️ Cached verification |
| **Shopify `webPixelsConfigList` Sandbox Unpacker** | ✅ **Extracts hidden Meta/TikTok/Ads IDs** | ❌ Misses sandboxed pixels | ❌ No pixel IDs |
| **Live Shopify Product & Price Catalog Intel** | ✅ **Extracts flagship product & $ price** | ❌ No | ❌ No |
| **55+ Local Booking, Call Tracking & CRM Tools** | ✅ **GHL, NexHealth, Weave, ServiceTitan...** | ❌ No | ⚠️ Limited enterprise tags |
| **Ready-to-Send Email Opener & 15s Call Script** | ✅ **Hyper-personalized per prospect** | ❌ No | ❌ Requires separate AI credits |
| **Zero-Cookie / Zero-Browser Architecture** | ✅ **~1.8s/domain, <128MB RAM, 0 Ban Risk** | ⚠️ Often heavy Playwright RAM | ❌ Expensive monthly seat lock-in |

---

## 📊 Real Extracted Output Preview (Live Run Benchmark)

Below is a slice of **real data extracted in 22.2 seconds** across e-commerce brands and auto-discovered Austin dental practices:

| Domain | Decision Maker | Primary & Executive Emails | Direct Phone | Mail Provider (DNS) | Detected Stack & Pixels | Auto-Generated Cold Email Icebreaker |
|---|---|---|---|---|---|---|
| `beardbrand.com` | Beardbrand Team | `support@beardbrand.com` | `(844) 662-3273` | **Google Workspace** (MX ✅ SPF ✅) | Shopify, Klaviyo, Zendesk, GA4 | *"Hi Beardbrand team — saw you're running Shopify, Klaviyo on beardbrand.com **(loved your Beard Oil Set at $122!)** and spotted 1 quick retargeting & conversion wins."* |
| `colourpop.com` | ColourPop Team | `privacy@colourpop.com` | — | **Sophos MX** (MX ✅ DMARC ✅) | Shopify, Klaviyo, Attentive, Gorgias, Meta + TikTok + Google Ads + Snap + Pinterest Pixels | *"Hi ColourPop team — saw you're running Shopify, Klaviyo on colourpop.com **(loved your Colour Me Merry at $99!)** and spotted 1 quick retargeting & conversion wins."* |
| `austincosmetic.com` | **Dr. Bradford Picot** *(Doctor / Principal)* | `downtown@austincosmetic.com` / `bradford@austincosmetic.com` | `(512) 476-2336` | **Google Workspace** (MX ✅ SPF ✅ DMARC ✅) | WordPress, **Weave CRM**, GTM, GA4 | *"Hi Dr. Picot — saw you're running WordPress, Weave on austincosmetic.com and spotted 3 quick retargeting & conversion wins."* |
| `thecosmeticdentistsofaustin.com` | **John Schiro, DDS** *(Doctor / Principal)* | `contact@...` / `john@thecosmeticdentistsofaustin.com` | `(737) 303-4986` | **Microsoft 365** (MX ✅ SPF ✅ DMARC ✅) | WordPress, GTM, GA4 | *"Hi John — while browsing thecosmeticdentistsofaustin.com, I noticed there's no instant AI chat or automated booking widget to capture after-hours visitors..."* |
| `austinmoderndentist.com` | **Dr. Benjamin Sharfae** *(Doctor / Principal)* | `benjamin@austinmoderndentist.com` | `(512) 301-9002` | **Domain MX** (4.8⭐ / 268 reviews) | WordPress, **NexHealth, Zocdoc, Mindbody, Weave**, Meta Pixel | *"Hi Dr. Sharfae — saw you're running WordPress, NexHealth on austinmoderndentist.com and spotted 2 quick retargeting & conversion wins."* |

---

## 💰 Transparent Pay-Per-Event Pricing (Modular & Fair)

No monthly subscriptions. You control which enrichment modules run via simple boolean toggles in the Input tab:

| Event Name | Event Key | Price (USD) | Per 1,000 Events | What It Includes |
|---|---|---|---|---|
| **Actor Start** | `apify-actor-start` | **$0.005** | One-time per run | Waives the first 5 seconds of Apify platform compute |
| **Search Query Auto-Discovery** | `search-query-executed` | **$0.005** | **$5.00 / 1K queries** | Discovers & filters real business domains for a niche + city keyword |
| **Website / Domain Crawled** | `domain-scraped` | **$0.001** | **$1.00 / 1K domains** | High-speed HTTP/2 + Chrome TLS crawl of homepage & internal contact/team pages |
| **Contact, Phone & Decision Maker** | `contact-enriched` | **$0.002** | **$2.00 / 1K leads** | Charged **only** when ≥1 valid email, phone, address, or decision-maker is found |
| **DNS / MX / DMARC & Exec Email** | `email-verified` | **$0.002** | **$2.00 / 1K checks** | Live Cloudflare DoH MX/SPF/DMARC check, Google/M365 host ID & executive email guess |
| **Ad Pixels, Shopify & 55+ Tech** | `ad-pixel-tech-detected` | **$0.003** | **$3.00 / 1K scans** | Unpacks Meta, TikTok, Google Ads, Shopify Sandbox, Catalog Pricing & 55+ tools |
| **Agency Gap Score & Sales Pitch** | `sales-pitch-generated` | **$0.005** | **$5.00 / 1K pitches** | Opportunity Score (0–100), Subject Line, Cold Email Icebreaker & 15s Call Script |

> 💡 **Pro Tip**: Only need fast contact & phone scraping? Uncheck `verifyEmailsDns`, `extractAdPixelsAndTech`, and `generateSalesPitch` in the Input tab to pay just **$1.00 – $3.00 per 1,000 domains**!

---

## 📥 Input Configuration Examples

### Mode A: Auto-Discover Niche Businesses by Keyword + Enrich Everything
```json
{
  "searchQueries": [
    "cosmetic dentist Austin TX",
    "medspa Miami FL"
  ],
  "maxDomainsPerQuery": 10,
  "crawlContactPages": true,
  "maxContactPagesPerDomain": 3,
  "verifyEmailsDns": true,
  "extractAdPixelsAndTech": true,
  "generateSalesPitch": true,
  "maxConcurrency": 15
}
```

### Mode B: Enrich Your Own List of Website URLs / Domains (From Google Maps, Clay, or CSV)
```json
{
  "urls": [
    "https://www.beardbrand.com",
    "https://colourpop.com",
    "https://austincosmetic.com"
  ],
  "crawlContactPages": true,
  "verifyEmailsDns": true,
  "extractAdPixelsAndTech": true,
  "generateSalesPitch": true
}
```

---

## 🔌 Plug-and-Play Integrations (Clay, n8n, Make, Instantly & MCP)

### 1. Clay.com / Make.com / n8n (Synchronous HTTP Webhook)
Call the synchronous endpoint to enrich any domain and receive JSON rows directly in your workflow:
```bash
curl -X POST "https://api.apify.com/v2/acts/leadforge_hq~b2b-lead-pixel-tech-enricher/run-sync-get-dataset-items?token=YOUR_APIFY_TOKEN" \
  -H "Content-Type": "application/json" \
  -d '{"urls": ["https://www.beardbrand.com"], "verifyEmailsDns": true, "extractAdPixelsAndTech": true, "generateSalesPitch": true}'
```

### 2. Claude Desktop / Cursor / Windsurf (MCP Server)
Add `@apify/actors-mcp-server` to your MCP client config to let your AI agent autonomously find and enrich B2B leads:
```json
{
  "mcpServers": {
    "apify": {
      "command": "npx",
      "args": [
        "-y",
        "@apify/actors-mcp-server",
        "--actors",
        "leadforge_hq/b2b-lead-pixel-tech-enricher"
      ],
      "env": {
        "APIFY_TOKEN": "YOUR_APIFY_TOKEN"
      }
    }
  }
}
```

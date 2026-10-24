# ⚡ LeadForge AI — B2B Leads, Google Maps Emails, Bulk Email Verifier & Shopify Store Enricher (Apify & MCP Suite)

![LeadForge AI — B2B Outbound Intelligence Suite](https://api.apify.com/v2/key-value-stores/b9rbebvrC82Huq8NJ/records/hero-banner-v3.png)

<p align="center">
  <a href="https://apify.com/leadforge_hq"><img src="https://img.shields.io/badge/Apify_Store-LeadForge_AI_(4_Live_Actors)-00D1B2?style=for-the-badge&logo=apify" alt="Apify Store" /></a>
  <a href="https://apify.com/leadforge_hq/b2b-lead-pixel-tech-enricher"><img src="https://img.shields.io/badge/B2B_Leads_Finder-%241_%2F_1K_Domains-6366F1?style=for-the-badge" alt="B2B Leads Finder" /></a>
  <a href="https://apify.com/leadforge_hq/google-maps-email-extractor-leads-finder"><img src="https://img.shields.io/badge/Google_Maps_Emails-%241_%2F_1K_Places-10B981?style=for-the-badge" alt="Google Maps Email Extractor" /></a>
  <a href="https://apify.com/leadforge_hq/email-verifier-finder-validator"><img src="https://img.shields.io/badge/Bulk_Email_Verifier-%240.80_%2F_1K_Emails-06B6D4?style=for-the-badge" alt="Bulk Email Verifier" /></a>
  <a href="https://apify.com/leadforge_hq/shopify-store-leads-email-pixel-scraper"><img src="https://img.shields.io/badge/Shopify_Store_Leads-%241_%2F_1K_Stores-A3E635?style=for-the-badge" alt="Shopify Store Leads" /></a>
</p>

---

## 🚀 Official Apify Store Actors by [LeadForge AI (`leadforge_hq`)](https://apify.com/leadforge_hq)

| Actor | Best For | Pricing | Apify Store Link |
|---|---|---|---|
| **✨ Leads Finder & Email Extractor** | Auto-discover B2B websites by keyword or enrich domains with Decision Makers, DNS-verified Emails, 3-Tier Phones, Meta/TikTok/Google Ad Pixels, 55+ Tech Stack & AI Cold Email Icebreakers | **$1.00 / 1K** | [**Run on Apify Store →**](https://apify.com/leadforge_hq/b2b-lead-pixel-tech-enricher) |
| **📍 Google Maps Email Extractor** | Plug in any **Google Maps Scraper Dataset ID** (`compass/crawler-google-places`) or local keywords to extract Owner Emails, Phones, Booking Systems (GoHighLevel, NexHealth, Mindbody, ServiceTitan) & 15s Cold Call Scripts | **$1.00 / 1K** | [**Run on Apify Store →**](https://apify.com/leadforge_hq/google-maps-email-extractor-leads-finder) |
| **🛡️ Bulk Email Verifier & Email Finder** | Clean bulk email lists from Apollo/LinkedIn/Maps & find direct executive emails (`Name + Domain → Email`). 7-Layer DNS/MX/SPF/DMARC/Gateway check (Google Workspace, Microsoft 365, Mimecast, Proofpoint) | **$0.80 / 1K** | [**Run on Apify Store →**](https://apify.com/leadforge_hq/email-verifier-finder-validator) |
| **🛍️ Shopify Store Leads Scraper** | Extract Shopify & DTC store emails, phones, hidden `webPixelsConfigList` Sandbox Ad Pixels (Meta, TikTok, Google Ads AW-), installed apps (Klaviyo, Gorgias, Yotpo) & live `/products.json` catalog pricing | **$1.00 / 1K** | [**Run on Apify Store →**](https://apify.com/leadforge_hq/shopify-store-leads-email-pixel-scraper) |

---

## 🤖 Using with Claude Desktop / Cursor / n8n / Clay (Apify MCP Server)

All 4 **LeadForge AI** Actors work out-of-the-box as AI Agent tools via the official `@apify/actors-mcp-server`:

```json
{
  "mcpServers": {
    "apify-leadforge": {
      "command": "npx",
      "args": [
        "-y",
        "@apify/actors-mcp-server",
        "--actors",
        "leadforge_hq/b2b-lead-pixel-tech-enricher,leadforge_hq/google-maps-email-extractor-leads-finder,leadforge_hq/email-verifier-finder-validator,leadforge_hq/shopify-store-leads-email-pixel-scraper"
      ],
      "env": {
        "APIFY_TOKEN": "YOUR_APIFY_API_TOKEN"
      }
    }
  }
}
```

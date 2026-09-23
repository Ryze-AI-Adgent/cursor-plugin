# Ryze AI: Google Ads, Meta Ads, SEO — Cursor Plugin

Product pages: [Google Ads MCP](https://www.get-ryze.ai/google-ads-mcp) · [Meta Ads MCP](https://www.get-ryze.ai/meta-ads-mcp)

## Install

[![Install in Cursor](https://img.shields.io/badge/Cursor-Install%20Ryze%20https://connector.get-ryze.ai/mcp-000000?logo=cursor&logoColor=white)](cursor://anysphere.cursor-deeplink/mcp/install?name=ryze-ai&config=eyJ1cmwiOiAiaHR0cHM6Ly9jb25uZWN0b3IuZ2V0LXJ5emUuYWkvbWNwIn0=)

Or by hand: **Cursor › Settings › MCP › Add new MCP server**, type `http`, URL:

```
https://connector.get-ryze.ai/mcp
```

Or drop this into `.cursor/mcp.json` in your project (same content as [mcp.json](mcp.json)):

```json
{ "mcpServers": { "ryze-ai": { "url": "https://connector.get-ryze.ai/mcp" } } }
```

Cursor opens a browser tab; sign in with the Google or Facebook account that owns the ads. Free, no API keys. Also works in Claude Code: `claude mcp add ryze --transport http https://connector.get-ryze.ai/mcp`. [Setup guide with screenshots →](https://www.get-ryze.ai/how-to-connect-claude-to-google-meta-ads-mcp)

Ryze AI is the MCP connector for paid ads and SEO. Connect Google Ads, Meta Ads (Facebook & Instagram Ads), Google Analytics 4, Google Search Console, Google Merchant Center, Shopify, HubSpot, PostHog, Webflow and OpenAI (ChatGPT) Ads to one Ryze workspace, then audit, report and optimize all of them from a single Cursor conversation.

## What you can do

- **Google Ads**: audit accounts for wasted spend, search terms, budget pacing, disapproved ads and conversion tracking; run GAQL reports; keyword research with search volume, competition and CPC; apply or dismiss recommendations; pause campaigns, change bids and budgets, add keywords and negatives; create custom audiences; upload Performance Max image assets.
- **Meta Ads**: Facebook and Instagram campaign performance, ad creatives, lead forms, Ad Library competitor research, Graph API reads and writes.
- **SEO / GEO / AEO**: Search Console queries and pages, click and ranking changes, indexation summary, URL inspection, sitemap submission, plus GA4 AI-referral traffic (ChatGPT, Perplexity, Gemini, Claude) by engine and landing page.
- **Analytics and reporting**: GA4 standard, realtime and pivot reports; cross-platform Google + Meta + GA4 tables with true CPA/ROAS; write results to Google Sheets and Docs; schedule recurring reports delivered by email or Slack.
- **Ecommerce and CRM**: Shopify products and orders, HubSpot contacts and deals, Merchant Center product issues, PostHog analytics, Webflow CMS.

## Safety

Read tools are read-only. Destructive operations are flagged and need item-by-item confirmation. Every action runs under the permissions of the accounts you connected in Ryze.

## Requirements

A Ryze AI account (free trial at [get-ryze.ai](https://www.get-ryze.ai)) with at least one platform connected. Tools shown depend on what your workspace has connected. On first use, Cursor opens the Ryze sign-in (OAuth) to link your workspace.

## Links

- [Website](https://www.get-ryze.ai/)
- [Setup guide](https://www.get-ryze.ai/how-to-connect-claude-to-google-meta-ads-mcp)
- [Privacy policy](https://www.get-ryze.ai/privacy)
- Support: hello@get-ryze.ai

# n8n-nodes-apivault-local-leads

An [n8n](https://n8n.io) community node for **Local Lead Finder Pro** — find local businesses by category + location and turn each one into an enriched B2B sales lead.

No login. Pay-as-you-go, no monthly subscription. The scraping and enrichment run server-side on [Apify](https://apify.com); this node is a thin connector you drive with your own Apify API token.

Built by **[apivault_labs](https://apify.com/apivault_labs)** — see [all our actors](https://apify.com/apivault_labs).

## Who it's for

Web agencies, hyper-local SEO shops and SDR teams. Search a category in a city (e.g. `plumbers` in `Miami FL`), and get back scored, contact-ready leads — including businesses with no website or a dead/DIY site, the hottest targets for a redesign pitch.

## What you get per lead (30+ fields)

- **Core**: name, category, address, phone, rating, review count, years in business, website
- **leadScore 0-100** + tier (cold / warm / hot / on-fire) + reasons
- **Website intel**: alive status, SSL validity, **tech stack** (Wix, WordPress, Shopify, Squarespace, GoDaddy, Webflow, Weebly, Joomla, Drupal, ClickFunnels, GoHighLevel)
- **Mobile-friendly** check + signals
- **SEO audit**: meta description, OG image, H1, JSON-LD, canonical + seoScore
- **Brand age** via Wayback Machine
- **Contacts**: real emails + phones scraped from the site, phone E.164 + click-to-call, contact page URL, email guesses, 5 social search URLs, bestContact
- **outreachPitch** — personalized cold-outreach opener
- **recommendations[]**

## Installation

In your n8n instance:

1. Go to **Settings → Community Nodes**
2. Select **Install**
3. Enter `n8n-nodes-apivault-local-leads`
4. Confirm and install

## Credentials

This node uses an **Apify API token**:

1. Create a free account at [apify.com](https://apify.com)
2. Go to **Apify Console → Settings → Integrations** and copy your **API token**
3. In n8n, create new **Apify API** credentials and paste the token

A free Apify account includes monthly usage credits.

## Usage

- **Business Category** — e.g. `plumbers`, `dentists`, `restaurants`
- **Location** — city and state, e.g. `New York NY`
- **Pages to Scrape** — each page ~30 businesses
- **Only Without Website** — return only businesses with no website (hottest agency leads)
- **Export Format** — default JSON / CSV (HubSpot/Pipedrive columns) / both
- **Enrichment** — websites + tech stack + emails, email guesses, social URLs, outreach pitch, brand age, geocode
- **Filters** — exclude chains, min lead score, max results

## Pricing

Billed per lead through Apify (pay-per-event): **$4 / 1,000 leads** ($0.004 each). All enrichment included.

## Use cases

- **Web-agency prospecting** — find local businesses with no site or a dead/DIY site
- **Local SEO outreach** — score and prioritize businesses by online-presence gaps
- **CRM enrichment** — export CSV straight into HubSpot/Salesforce/Pipedrive
- **Territory building** — geocode leads for map plotting and routing

## Resources

- [Local Lead Finder Pro actor on Apify](https://apify.com/apivault_labs/local-business-lead-finder)
- [All actors by apivault_labs](https://apify.com/apivault_labs)
- Prefer Python? Use the [Python SDK](https://github.com/apivault-labs/local-lead-finder-python)
- [n8n community nodes docs](https://docs.n8n.io/integrations/community-nodes/)

## License

[MIT](LICENSE)

## Keywords

`local-leads` `lead-generation` `b2b-prospecting` `yellowpages-scraper` `local-seo` `web-agency-leads` `outreach-automation` `crm-enrichment` `apollo-alternative` `n8n` `apify`

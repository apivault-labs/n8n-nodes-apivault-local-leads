# Changelog

## 0.1.0

- Initial release.
- `Local Lead Finder Pro` node: search local businesses by category + location
  on YellowPages and enrich every lead.
- 30+ fields per lead: leadScore (0-100) + tier, website tech stack, alive/SSL,
  mobile + SEO audit, brand age (Wayback), real emails + phones, phone E.164,
  email guesses, social search URLs, bestContact, outreach pitch, recommendations.
- Toggleable enrichment (websites, email guesses, social URLs, outreach pitch,
  brand age, geocode) + server-side filters (exclude chains, min lead score,
  max results).
- Export formats: default JSON / CSV (HubSpot/Pipedrive) / both.
- `Apify API` credentials with token test against `/users/me`.
- Calls the `apivault_labs/local-business-lead-finder` actor via
  `run-sync-get-dataset-items`.

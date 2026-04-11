# Water Infrastructure Transparency

Interactive tools connecting storm overflow data to public procurement records for UK water companies.

## Structure

```
southern_water/          — Southern Water (Kent, Sussex, Hampshire, IoW)
  index.html             — Public-facing transparency tool
  dashboard.html         — Procurement intelligence dashboard
  graph_with_micro_procurement.json — Complete network graph
  data/raw/              — Source datasets (EDM, FTS, Contracts Finder)
  data/processed/        — Derived datasets (procurement, suppliers, catchments)
  outreach/              — Contact and email tooling

anglian_water/           — Anglian Water (in progress)
  data/raw/              — Source datasets
  data/processed/        — Derived datasets
```

## Data sources

- [Storm Overflow Portal](https://www.southernwater.co.uk) (real-time overflow events)
- [Find a Tender](https://www.find-tender.service.gov.uk) (UK government procurement notices)
- [Environment Agency EDM annual returns](https://data.gov.uk)
- [Water Projects Online](https://waterprojectsonline.com) (case studies)
- Press releases from water companies and their contractors

## Built by

[Nelith Bandularatne](https://nelith.vercel.app/) | [chaotic-systems.com](https://chaotic-systems.com)

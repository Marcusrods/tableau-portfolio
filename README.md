# tableau-portfolio

Two Tableau dashboards built during the BTS Masters in Big Data and AI Data Visualisation module. The workbooks live in this repo. The interactive versions sit on Tableau Public so anyone can poke at them without installing Tableau.

> **Live links coming.** Once I publish the two workbooks to Tableau Public, the links go here. For now the repo has the .twb/.twbx files plus PDF previews.

## Dashboards

### Challenge 4. Spirits in South Africa

A market overview dashboard for the South African spirits category. Sales by brand, by category, by region, plus a competitor positioning view. The brief was a one-page briefing dashboard for a non-technical stakeholder.

- Workbook: [`dashboards/challenge_4/Marcus_Final_Spirits.twbx`](dashboards/challenge_4/Marcus_Final_Spirits.twbx) (packaged, opens without needing the source data file).
- Mockup: [`previews/challenge_4_dashboard_mockup.pdf`](previews/challenge_4_dashboard_mockup.pdf).
- Brief overview: [`previews/challenge_4_brief_overview.pdf`](previews/challenge_4_brief_overview.pdf).
- Live: *Tableau Public link to be added.*

What this shows:

- Multi-panel dashboard layout with a clear narrative spine.
- Sheet-to-dashboard composition with synchronised filters and parameter controls.
- Calculated fields for share-of-category and growth metrics.
- Custom colour palette, deliberate typography, dashboard chrome that fits the brief.

### Challenge 3. The Simpsons

A diagnostic dashboard exploring viewership and IMDB rating trends across The Simpsons' run. Lower-stakes brief, used as the entry point to Tableau dashboarding mechanics.

- Workbook: [`dashboards/challenge_3/Marcus_Rodrigues_Challenge_3.twb`](dashboards/challenge_3/Marcus_Rodrigues_Challenge_3.twb).
- Data: [`dashboards/challenge_3/SimpsonsData.xlsx`](dashboards/challenge_3/SimpsonsData.xlsx).
- Live: *Tableau Public link to be added.*

What this shows:

- Trend charts with reference bands.
- Heatmap of episode-level ratings.
- Working with a denormalised seasonal dataset.

## How to open

Tableau Public Desktop (free): https://public.tableau.com/en-us/s/download

```
File > Open > select the .twb (Challenge 3) or .twbx (Challenge 4)
```

The `.twbx` is a packaged workbook with the data embedded. The `.twb` references the Excel file in the same folder.

## Why a wrapper repo and not just Tableau Public

Recruiters land on GitHub first. The wrapper repo gives them the README narrative, the PDF previews, and the file directly. The Tableau Public links sit alongside for anyone who wants to interact.

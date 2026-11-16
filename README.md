# Egypt Population Explorer — Project 5

Interactive responsive population statistics dashboard for the Data Analysis & Visualization course.

## Website
After enabling GitHub Pages, the expected URL is https://omarhanafy61.github.io/egypt-population-dashboard/

## Included
- `index.html`: self-contained dashboard with Bootstrap 5 and Chart.js
- `population_simulated.csv`: 30 simulated records for six governorates, 2021–2025
- `README.md`: instructions and methodology

## Features
Year and governorate dropdowns; four KPIs; population comparison bar chart, trend line chart, age-group doughnut chart, density bar chart; data table; CSV export; responsive layout.

## Run
Open `index.html` in a browser. An internet connection is required for the Bootstrap and Chart.js CDN libraries.

## Publish
Open repository **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then **Save**. Wait for GitHub Pages to publish.

## Methodology
The dashboard simulates 1.7% annual population and density growth from 2021 baselines. Birth rates decrease 0.15 per thousand annually and death rates increase 0.05 per thousand annually. Age-group shares stay fixed for each governorate. KPI birth/death averages are unweighted across selected governorates.

## Data transparency and limitations
**All values are synthetic and must not be described as official Egyptian statistics.** Only six governorates are represented. Population projections are illustrative and are not derived from birth/death rates. Replace with verified official statistics and cite their source for a factual analysis.

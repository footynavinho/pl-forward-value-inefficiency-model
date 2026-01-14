# Identifying Value Inefficiencies in Premier League Forwards (2024/25)

## Project Overview
This project applies performance analytics and financial valuation concepts to football recruitment.  
Using FBRef per-90 metrics and Transfermarkt market values, I identify Premier League forwards who deliver strong on-pitch performance relative to their market cost.

The goal is to replicate a real-world recruitment workflow used by clubs and analytics teams.

## Data Sources
- **FBRef**: Per-90 and advanced attacking metrics (2024/25 season)
- **Transfermarkt**: Latest publicly available market values (EUR millions)

Players with fewer than **10 full 90s** were excluded to ensure sample reliability.

## Methodology

### Performance Index
I constructed a composite Performance Index using normalized per-90 metrics across three dimensions:

- **Attacking Output** (goals, xG, shot quality)
- **Creativity** (assists, xAG, key passes, shot-creating actions)
- **Progression** (progressive carries, passes, receptions)

Each sub-index was normalized and combined to produce an overall Performance Index.

### Value Inefficiency Index
To evaluate cost efficiency, I calculated:
Value Inefficiency Index = Performance Index / Market Value (€m)

Higher values indicate greater performance delivered per unit of market cost.

## Key Questions Answered
- Which forwards outperform the league average relative to age?
- Which players deliver strong performance at below-average market value?
- Where do potential pricing inefficiencies exist?

## Outputs
- Interactive Tableau dashboard
- Recruitment shortlist table
- Performance vs Age and Performance vs Market Value visualizations

## Tableau Dashboard
[View interactive Tableau dashboard](https://public.tableau.com/views/PremierLeagueForwardValueAnalysis202425/Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Skills Demonstrated
- Sports analytics
- Data normalization and indexing
- Financial efficiency modeling
- Tableau dashboard design
- Recruitment-style decision support

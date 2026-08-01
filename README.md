# IPL-ExploratoryDataAnalysis-Project
# IPL Match Analysis

Exploratory data analysis on IPL season data (74 matches), done in a Jupyter notebook with pandas, seaborn, and plotly.

I put this together to practice going from raw data to actual answers, not just running `.describe()` and calling it done.

## Dataset

`IPL.csv` — one row per match, 20 columns including venue, teams, toss winner/decision, innings scores and wickets, match winner, margin, player of the match, top scorer, and best bowling figures for that match.

No missing values in the dataset, so cleanup was minimal.

## Questions I answered

- Which team won the most matches
- Does winning the toss actually help win the match
- Do teams win more often by defending a total or by chasing
- Who picked up the most player of the match awards
- Who the top run scorers and wicket takers were
- Which venues hosted the most matches
- The largest winning margin, highest individual score, and best bowling figures of the season

## A few results

- Toss winners went on to win the match only 48.65% of the time — close to a coin flip
- Chasing (winning by wickets) happened more often than defending a total
- Highest individual score: Quinton de Kock, 140
- Best bowling figures: Jasprit Bumrah, 5/10
- Largest winning margin: Chennai, 91 runs

## Tools

- pandas, numpy for data handling
- seaborn, matplotlib for static plots
- plotly for the interactive charts (toss vs match winner pie, top scorers/bowlers bar charts)

## Running it

```bash
pip install pandas numpy seaborn matplotlib plotly
jupyter notebook ipl_project.ipynb
```

Make sure `IPL.csv` is in the same folder as the notebook.

## Notes

This is a single-season dataset (74 matches), so treat the percentages as a small sample, not a general rule about IPL toss outcomes.

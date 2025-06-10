# IPL EDA Project

This project performs Exploratory Data Analysis (EDA) on Indian Premier League (IPL) cricket data using Python and Jupyter Notebook. The analysis covers team and player performances, match trends, venues, and more.

## Dataset

The project uses two main datasets:

- **matches.csv**: Contains match-level information for all IPL matches.
- **deliveries.csv**: Contains ball-by-ball delivery data for each match.

### matches.csv Columns

- `id`: Match ID
- `season`: IPL season (year)
- `city`: City where the match was played
- `date`: Match date
- `match_type`: Type of match (e.g., League, Final)
- `player_of_match`: Player awarded as Man of the Match
- `venue`: Stadium name
- `team1`, `team2`: Competing teams
- `toss_winner`: Team that won the toss
- `toss_decision`: Decision after toss (bat/field)
- `winner`: Match winner
- `result`: Result type (runs/wickets)
- `result_margin`: Margin of victory
- `target_runs`, `target_overs`: Target for chasing team
- `super_over`: Was a super over played (Y/N)
- `method`: Special method (e.g., D/L)
- `umpire1`, `umpire2`: Umpires

### deliveries.csv Columns

- `match_id`: Match ID (links to matches.csv)
- `inning`: Inning number (1 or 2)
- `batting_team`, `bowling_team`: Teams
- `over`, `ball`: Over and ball number
- `batter`, `bowler`, `non_striker`: Player names
- `batsman_runs`: Runs scored by batter
- `extra_runs`: Extra runs (wides, legbyes, etc.)
- `total_runs`: Total runs in the ball
- `extras_type`: Type of extra (if any)
- `is_wicket`: 1 if wicket fell, else 0
- `player_dismissed`: Name of dismissed player (if any)
- `dismissal_kind`: Type of dismissal (caught, bowled, etc.)
- `fielder`: Fielder involved (if any)

## Project Structure
(The dataset can be downloaded from below mentioned link)
```
ipl-eda/
├── ipl_eda.ipynb
├── matches.csv
├── deliveries.csv
└── README.md
```

## Analysis Performed

- Data cleaning and preprocessing
- Team performance analysis (overall wins, finals, home advantage)
- Player performance (runs, wickets, strike rates, fifties, centuries, etc.)
- Toss and match result trends
- Venue and city analysis
- Dismissal types and fielding analysis
- Team vs Team win matrix and heatmap
- Highest team totals and successful chases
- Year-wise trends and player improvements

## How to Run

1. Install dependencies:
    ```sh
    pip install pandas numpy matplotlib seaborn
    ```
2. Open `ipl_eda.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells sequentially.

## Credits

- Data sourced from [Kaggle IPL datasets](https://www.kaggle.com/datasets).
- Dataset Link: (https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- Analysis and notebook by [Your Name].

---
```

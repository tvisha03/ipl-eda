# IPL Data Analysis Project

A comprehensive data analysis project focused on Indian Premier League (IPL) cricket matches from 2008-2020. This project uses Python and Jupyter Notebook to perform in-depth statistical analysis and visualization of IPL data, providing insights into team performances, player statistics, match outcomes, and various cricket-specific metrics.

## Features

### Team Analysis
- Overall team performance metrics and rankings
- Season-wise team performance trends
- Home ground advantage analysis
- Team vs Team performance matrix with win percentages
- Analysis of toss decisions and their impact on match outcomes
- Highest team totals and successful run chases

### Player Analysis
- Comprehensive batting statistics
  - Top run scorers (all-time and season-wise)
  - Batting averages and strike rates
  - Analysis of boundaries (4s and 6s)
  - Century and half-century statistics
- Detailed bowling analysis
  - Leading wicket-takers
  - Economy rates and bowling averages
  - Analysis of different types of dismissals
- Player matchups (batsman vs bowler statistics)
- Fielding statistics including catching efficiency

### Venue and Match Analysis
- Stadium-wise statistics and trends
- City-wise cricket performance metrics
- Detailed analysis of finals and knockout matches
- Impact of toss decisions on match outcomes
- Analysis of close matches and decisive factors

## Dataset

The analysis uses two primary datasets:

- **matches.csv**: Match-level data (located in `data/matches.csv`)
  - Match metadata (ID, season, date, venue)
  - Team information (teams, toss, winner)
  - Match outcomes and statistics

- **deliveries.csv**: Ball-by-ball data (located in `data/deliveries.csv`)
  - Detailed delivery information
  - Batting and bowling statistics
  - Runs, wickets, and extras data

## Project Structure

```
ipl-eda/
├── notebooks/
│   ├── ipl_eda.ipynb        # Main analysis notebook with comprehensive EDA
│   ├── 01_prediction.ipynb  # Match outcome prediction analysis
│   ├── 03_live_win_predictor.ipynb  # Live win predictor analysis
├── data/
│   ├── matches.csv         # Match-level dataset
│   ├── deliveries.csv     # Ball-by-ball dataset
├── ipl_env/               # Python virtual environment
│   ├── Scripts/           # Environment scripts
│   ├── Lib/               # Libraries and dependencies
│   ├── Include/           # Include files
│   ├── etc/               # Configuration files
└── README.md              # Project documentation
```

## Key Visualizations

The project includes various statistical visualizations:
- Team performance bar charts and heatmaps
- Player performance trend lines
- Venue and city-wise performance charts
- Toss decision impact analysis
- Season-wise trend analysis
- Player comparison radar charts

## Requirements

- Python 3.x
- Key libraries:
  ```sh
  pip install pandas numpy matplotlib seaborn plotly
  ```

## How to Run

1. Clone the repository
2. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook or VS Code:
   ```sh
   jupyter notebook
   # or
   code .
   ```
4. Open and run `notebooks/ipl_eda.ipynb` for comprehensive analysis

## Data Sources

- Dataset: [IPL Complete Dataset 2008-2020](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- Source: Kaggle IPL datasets

## Contributing

Feel free to fork the repository and submit pull requests for additional analysis or improvements.

## License

This project is open-source and available under the MIT License.

---
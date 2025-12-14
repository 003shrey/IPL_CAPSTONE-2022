# IPL 2022 Capstone Project 🏏

A comprehensive data analysis project exploring IPL (Indian Premier League) 2022 match-level data to derive meaningful insights and understand match outcomes, player performances, and team dynamics.

## 📊 Project Overview

This project performs an in-depth analysis of the IPL 2022 season using Python data science libraries. It explores various aspects of the tournament including team performances, player statistics, venue analysis, and match outcomes to uncover interesting patterns and insights.

## ✨ Features

### Analysis Performed

1. **Team Performance Analysis**
   - Match wins by team
   - Winning patterns (runs vs wickets)
   - Team dynamics and success factors

2. **Toss Analysis**
   - Toss decision trends (Field vs Bat)
   - Correlation between toss winner and match winner
   - Impact of toss on match outcomes

3. **Player Performance Metrics**
   - Top scorers identification
   - Best bowling figures analysis
   - Player of the match statistics

4. **Venue Analysis**
   - Most active venues
   - Venue-specific performance trends
   - Ground impact on match outcomes

5. **Match Insights**
   - Highest margin victories (by runs and wickets)
   - Individual performance records
   - Scoring patterns across innings

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 📋 Prerequisites

Make sure you have Python 3.x installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/003shrey/IPL_CAPSTONE-2022.git
cd IPL_CAPSTONE-2022
```

2. Install required packages:
```bash
pip install numpy pandas seaborn matplotlib
```

Or use a requirements file:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Open the Jupyter Notebook:
```bash
jupyter notebook IPL_CAPSTONE.ipynb
```

2. Run the cells sequentially to:
   - Load the IPL 2022 dataset
   - Perform data cleaning and preprocessing
   - Generate visualizations
   - Derive insights from the analysis

## 📁 Dataset

The project uses IPL 2022 match-level data containing:
- Match details (date, venue, teams)
- Toss information (winner, decision)
- Innings scores and wickets
- Match outcomes (winner, margin)
- Player performances (player of the match, top scorer, best bowler)

**Dataset Columns:**
- `match_id`, `date`, `venue`
- `team1`, `team2`, `stage`
- `toss_winner`, `toss_decision`
- `first_ings_score`, `first_ings_wkts`
- `second_ings_score`, `second_ings_wkts`
- `match_winner`, `won_by`, `margin`
- `player_of_the_match`, `top_scorer`, `highscore`
- `best_bowling`, `best_bowling_figure`

## 🔍 Key Questions Answered

1. **Which team won the most matches in IPL 2022?**
2. **What are the toss decision trends?**
3. **How does winning the toss correlate with winning the match?**
4. **Which venues hosted the most matches?**
5. **Who won with the highest margin by runs?**
6. **Which player had the highest individual score?**
7. **Which bowler had the best bowling figures?**
8. **How do teams typically win (by runs vs wickets)?**

## 📈 Sample Visualizations

The notebook includes various visualizations such as:
- Bar charts for team performance comparison
- Pie charts for toss decision distribution
- Count plots for match outcomes
- Statistical plots for player performances
- Venue analysis charts

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Shreyansh Yadav**

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## ⭐ Show your support

Give a ⭐️ if you like this project!

---

**Note:** This is an educational project created for data analysis learning purposes.

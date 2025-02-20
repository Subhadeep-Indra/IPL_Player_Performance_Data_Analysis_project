 🏏 IPL Player Performance Dashboard

 📌 Overview
This initiative is a dashboard for data analysis focused on IPL (Indian Premier League) player performance between 2008 and 2024. It incorporates Streamlit, Pandas, and Plotly for the assessment and visualization of player statistics relating to batting, bowling, and fielding. Users can actively explore data on a seasonal, yearly, and match-by-match basis with graphical representations.

 🚀 Features
- Home Page: An introduction to the dashboard.
- Season-wise Player Analysis:
  - Choose a player to view statistics for batting, bowling, and fielding.
  - Visual aids for runs scored per match, wickets taken per match, and performance in the field.
  - Year-wise detailed performance breakdown in table format.
- Leaderboard:
  - Showcases Orange Cap (Top Scorer) and Purple Cap (Top Wicket-taker) for each season or aggregated across all seasons.
- Match-wise Performance:
  - Examine individual match statistics.
  - Select a match to explore detailed statistics for all players.

 📂 Dataset
- File Utilized: `IPL_Histroy_2008-2024.csv`
- Contains columns such as `batter`, `bowler`, `fielder`, `batsman_runs`, `total_runs`, `is_wicket`, `dismissal_kind`, `match_year`, `match_id`, and more.

 🛠️ Technologies Used
- Python
- Pandas (for data manipulation)
- Streamlit (for creating the web application)
- Plotly (for dynamic visualizations)

 📌 Jupyter Notebook Analysis
- Data Cleaning: Addressed missing values and eliminated whitespaces from column names.
- Exploratory Data Analysis (EDA):
  - Calculated total runs, wickets, and dismissals.
  - Summarized player performances across the years.
  - Generated plots for runs scored by season, wickets taken per season, and dismissals.
- Feature Engineering:
  - Inferred batting strike rate, batting average, economy rate, and bowling average.
- Performance Analysis:
  - Compiled year-wise and overall performance tables for every player.

 🎨 Streamlit Web App Implementation
1. Imported the cleaned dataset into Streamlit.
2. Sidebar Navigation:
   - Home, Season-wise Player Analysis, Leaderboard, Match-wise Performance.
3. Player Analysis:
   - Extracted data specific to players for batting, bowling, and fielding.
   - Visualized runs per match, wickets per match, and fielding contributions.
4. Leaderboard:
   - Calculated season-wise leading run-scorers and wicket-takers.
5. Match-wise Performance:
   - Enabled users to access detailed match statistics.

📌 IPL Player Performance Data Analysis
This Streamlit app analyzes IPL player performance data.

🔗 Live App: [Click here to view](https://iplplayerperformancedataanalysisproject-bfnqks6skvpx5uhwceqf7j.streamlit.app/)


IPL Analysis (2008 - 2025) | Power BI Dashboard 🏏📊

An end-to-end interactive Business Intelligence solution built using Microsoft Power BI to analyze performance trends, team standings, player achievements, and match dynamics across the history of the Indian Premier League (IPL) from 2008 to 2025.
This dashboard combines complex data modeling, dynamic DAX metrics, visual hierarchy, and customized UX navigation elements—including single-click social media integration and creator networking.

📌 Table of ContentsExecutive:

Executive Summary & Key Features

Interactive Sidebar & Dynamic Navigation

Dashboard Architecture & Metrics

Data Model & Data Sources

Technical Implementation & DAX

How to Use & Run Locally

Connect & Support

📊 Executive Summary & Key Features
The primary objective of this project is to transform raw ball-by-ball and match-level cricket datasets into actionable visual insights.

Key Highlights:
Dynamic Season Filtering: Slice data across 18 seasons of IPL history (2008 through the 2025 season).

Macro-Level KPI Cards: Real-time summary metrics tracking Total 6s, Total 4s, Total Matches Played, Total Participating Teams, Centuries, Half-Centuries, and Total Venues.
Leaderboards & Player Performance Cards:

Orange Cap Holder: Real-time breakdown of top runs, player avatar, and team representation (e.g., B Sai Sudharsan - 759 Runs).

Purple Cap Holder: Top wicket-taker metrics, bowling team, and player profile (e.g., M Prasidh Krishna - 25 Wickets).

Boundary Leaders: Highlight cards for Top 4s (Fours) and Top 6s (Sixes) hitters.

Comprehensive League Table: Detailed standings table reflecting Matches Played, Won, Lost, No Result (NR), Ties, and Total Points for all franchises in the selected season.

🔗 Interactive Sidebar & Dynamic Navigation
To enhance user experience and engagement beyond standard visuals, a dedicated navigation panel was engineered on the left side of the report using Power BI Web URL Action Buttons:

Official IPL Platforms:
 🌐 IPL Official Website (ipl20.com)

🐤 Twitter / X Profile

📘 Facebook Page

📸 Instagram Page

📺 YouTube Channel

Cricket Media & Live Updates:

🏏 ESPN Cricinfo

⚡ Cricbuzz

Developer / Author Link:

👤 LinkedIn Profile (Vidhyalakshmi RV): Direct connection to the author's professional profile embedded right into the report page.

📐 Dashboard Architecture & MetricsThe dashboard is logically divided into three structural zones:+-----------------------------------------------------------------------------------+
|                            TOP HEADER: TITLE & SEASON SLICER                       |
+---------------------+---------------------------------------+---------------------+
|                     |  KPI SUMMARY BAR                      |  SEASON CHAMPIONS   |
|                     |  (Total 6s, 4s, Matches, Teams, etc.) |  Winner & Runner-Up |
|   NAVIGATION        +---------------------------------------+---------------------+
|   SIDEBAR           |  TOP PERFORMERS (INDIVIDUAL CARDS)    |                     |
|   (Web Links &      |  - Orange Cap Holder                  |  POINTS TABLE       |
|    Social Handles)  |  - Purple Cap Holder                  |  (Matches, Wins,    |
|                     |  - Top 4s & Top 6s Leaders            |   Losses, Points)   |
+---------------------+---------------------------------------+---------------------+

🛠️ Data Model & Data Sources
Datasets Used:
ball_by_ball_data: Granular dataset tracking every legal/illegal delivery, runs scored, extras, dismissal types, bowler, and batter details.

matches_data: High-level match details including season, match date, venue, teams, toss decisions, winner, and margins.

Data Cleaning & Power Query Steps:
Data Cleansing: Standardized team names across seasons (e.g., handling name changes such as Delhi Daredevils to Delhi Capitals, Royal Challengers Bangalore to Royal Challengers Bengaluru)

Missing Values: Handled null values in match outcomes (e.g., rain-affected No Result matches)

Custom Columns: Added conditional logic for boundary classification ($4\text{s}$ and $6\text{s}$), bowler wicket counts (excluding run-outs), and player century/half-century flags.

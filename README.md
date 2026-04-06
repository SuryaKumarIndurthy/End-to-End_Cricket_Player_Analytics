# End-to-End_Cricket_Player_Analytics

## 📌 Project Overview
This project is an interactive Data Analytics and Business Intelligence dashboard built to assemble the ultimate "Best 11" cricket team from the ICC Men's T20 World Cup 2022. Operating under the philosophy of *"We don’t know the strengths and weaknesses of our opponents, but give me the best 11 from this planet,"* this project uses advanced data modeling and parameter scoping to objectively evaluate player performance. 

The analysis is driven by two primary team objectives:
1. The team should be able to score at least **180 runs** on average.
2. The team should be able to defend **150 runs** on average.

## 🎯 Objectives
- To perform Exploratory Data Analysis (EDA) on T20 World Cup 2022 player data.
- To establish rigorous performance metrics for selecting Openers, Middle Order Anchors, Finishers, All-Rounders, and Specialist Fast Bowlers.
- To build a dynamic, interactive dashboard allowing users to filter and select the final 11 players based on custom parameters.

## 📊 Methodology & Parameter Scoping
Players were filtered and categorized into specific roles based on strictly defined criteria.

## 💻 Dashboard Features
The resulting BI Dashboard provides a seamless interface for player selection and analysis:
- **Player Analysis Grid:** Displays selected players with their headshots, team names, playing roles, and crucial metrics (Batting Avg, Strike Rate, Economy)
- **Custom Final 11 Selector:** An interactive sidebar allowing users to search and toggle players on or off to experiment with different team combinations.
- **Aggregated Team Performance:** A dynamic bottom ribbon that calculates the cumulative metrics of the selected team (e.g., Team Batting Avg, Overall Economy, Dot Ball %) to ensure the final squad meets the project's win conditions.

## 🛠️ Tech Stack
- **Data Visualization & BI:** Power BI
- **Data Transformation:** Power Query
- **Languages:** DAX / Python(Jupyter notebook for Data preprocessing)

## 🚀 How to Use
1. Download the `.pbix` file from this repository.
2. Open the file in **Power BI Desktop**.
3. Navigate to the `Final 11` tab.
4. Use the sidebar on the left to select different players and watch the aggregate team metrics adjust in real-time.

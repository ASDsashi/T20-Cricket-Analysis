# T20 Cricket Team Selection

## Problem Statement

In the context of the 2022 Men's T20 World Cup, the goal is to build an undefeatable cricket team that can achieve a dual target: scoring a minimum of 180 runs in a T20 match and defending at least 150 runs on average. The team selection process involves analyzing player performance data from the 2022 Men's T20 World Cup dataset to identify key contributors in batting, bowling, and all-round performances.

## Project Goals

1. **Team Composition:**
   - Assemble a well-balanced team comprising top-performing batsmen, bowlers, and all-rounders.
   - Consider factors such as batting strike rates, bowling economy rates, and all-round contributions.

2. **Run Scoring:**
   - Identify batsmen with a proven track record of scoring high runs in T20 matches.
   - Formulate a strategy to ensure the team consistently achieves a minimum total of 180 runs.

3. **Defensive Capability:**
   - Select bowlers with a history of effective wicket-taking and economy rates.
   - Develop a robust bowling lineup capable of defending a minimum of 150 runs on average.

4. **All-Round Performance:**
   - Recognize all-rounders who can make significant contributions with both bat and ball.
   - Balance the team with players who can impact the game in multiple dimensions.

5. **Data Analysis and Visualization:**
   - Utilize Python for data analysis, exploring key statistics and metrics.
   - Create visualizations to showcase the performance metrics of selected players.

6. **Documentation:**
   - Maintain clear documentation outlining the rationale behind player selection.
   - Provide insights into the chosen strategies and the expected impact on achieving the team goals.
   - [Documentation](https://github.com/ASDsashi/T20-Cricket-Analysis/blob/main/Measures%20and%20Parameters.pdf)

## Dataset

The dataset used for this analysis is sourced from the 2022 Men's T20 World Cup. It includes comprehensive statistics on player performances, team records, and match outcomes. The dataset has been analyzed to identify standout players meeting the criteria for batting, bowling, and all-round excellence.
   -[Dataset](https://github.com/ASDsashi/T20-Cricket-Analysis/tree/main/Dataset)

## Methodology

1. **Data Cleaning with Python:**
   - Cleaned the raw data using Python, converting the JSON file into a structured CSV format.
   - Transformation included handling complex arrays by converting them into simple dictionaries.
   - Addressed the absence of information regarding player dismissal in the JSON file by utilizing a string in the "dismissal" field to identify player-outs.
   - [Python Data Cleaning Code](https://github.com/ASDsashi/T20-Cricket-Analysis/blob/main/Data%20Cleaning.ipynb)

2. **Data Transformation with PowerQuery:**
   - Conducted data transformation using PowerQuery to enhance the dataset for analysis.
   - Eliminated duplicate player names with respect to their countries, ensuring accuracy in player statistics.
   - Named matches as Qualifier/Super 12 based on the dates they were played.

3. **Data Visualization with Power BI:**
   - Leveraged Power BI for comprehensive data visualization, showcasing key statistics to aid in player selection.
   - Visualized player metrics, including strike rate, batting style, batting average, boundary percentage, wickets, dot ball percentage, maiden overs, and more.
   - Enabled users to identify the top 11 players based on both numerical and visual insights.
   - [Explore Power BI Visualizations](https://github.com/ASDsashi/T20-Cricket-Analysis/tree/main/Dashboard)

    The Power BI visualizations encompass not only numerical statistics but also include informative charts and scatterplots for enhanced visualization and analysis.


## Key Insights



## Conclusion

The goal is to build not just a cricket team but a winning combination that aligns with the specific targets set for run-scoring and defending. The project will culminate in the selection of the "Undefeatable XI" men's cricket team, backed by data-driven insights and a strategic approach.

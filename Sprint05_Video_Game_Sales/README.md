## Project Description

You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g., Xbox or PlayStation), and historical data on game sales are available from open sources. Your task is to identify patterns that determine whether a game succeeds or not. This analysis will help spot potential big winners and plan advertising campaigns for 2017.

## Data Description
The dataset consists of information about video games, including sales data, critic scores, and user ratings. The dataset is stored in a file named `games.csv` and includes the following features:
- **Name**: Name of the game.
- **Platform**: Platform the game was developed for (e.g., PlayStation, Xbox, PC).
- **Year_of_Release**: Year the game was released.
- **Genre**: Category of the game (e.g., Action, Adventure, RPG).
- **NA_sales**: Sales in North America (in USD million).
- **EU_sales**: Sales in Europe (in USD million).
- **JP_sales**: Sales in Japan (in USD million).
- **Other_sales**: Sales in other countries (in USD million).
- **Critic_Score**: Critic score out of 100.
- **User_Score**: User score out of 10.
- **Rating**: ESRB rating of the game (e.g., E for Everyone, T for Teen, M for Mature).

**Instructions:**

1. **Step 1: Data Exploration**
   - Open the data file and study the general information.

2. **Step 2: Data Preparation**
   - Replace column names (make them lowercase).
   - Convert data to the required types.
   - Handle missing values, especially the 'TBD' cases.
   - Calculate total sales for each game and create a separate column.

3. **Step 3: Data Analysis**
   - Analyze the number of games released per year.
   - Examine sales trends across different platforms.
   - Focus on relevant data for building a 2017 model.
   - Compare sales distributions across platforms using box plots.
   - Investigate the relationship between user/professional reviews and sales.
   - Analyze the distribution of games by genre and their profitability.

4. **Step 4: Regional User Profiles**
   - Identify the top five platforms and genres for each region (NA, EU, JP).
   - Analyze how ESRB ratings affect sales in each region.

5. **Step 5: Hypothesis Testing**
   - Test hypotheses on average user ratings between platforms (e.g., Xbox One vs. PC) and genres (e.g., Action vs. Sports).
   - Formulate null and alternative hypotheses.
   - Set the alpha threshold and explain the significance level chosen.

6. **Step 6: Conclusion**
   - Summarize your findings and insights from the analysis.

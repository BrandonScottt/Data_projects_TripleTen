## Project Description

You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g., Xbox or PlayStation), and historical data on game sales are available from open sources. Your task is to identify patterns that determine whether a game succeeds or not. This analysis will help spot potential big winners and plan advertising campaigns for 2017.

## Data Description
The dataset consists of information about video games, including sales data, critic scores, and user ratings. The dataset is stored in a file named `games.csv` and includes the following features:
- **`Name`**: Name of the game.
- **`Platform`**: Platform the game was developed for (e.g., PlayStation, Xbox, PC).
- **`Year_of_Release`**: Year the game was released.
- **`Genre`**: Category of the game (e.g., Action, Adventure, RPG).
- **`NA_sales`**: Sales in North America (in USD million).
- **`EU_sales`**: Sales in Europe (in USD million).
- **`JP_sales`**: Sales in Japan (in USD million).
- **`Other_sales`**: Sales in other countries (in USD million).
- **`Critic_Score`**: Critic score out of 100.
- **`User_Score`**: User score out of 10.
- **`Rating`**: ESRB rating of the game (e.g., E for Everyone, T for Teen, M for Mature).

## Answer these questions:
- Look at how many games were released in different years. Is the data for every period significant?
- Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year.
- Find platforms that used to be popular but now have zero sales.
- How long does it generally take for new platforms to appear and old ones to fade?
- Determine what period you should take data for. To do so, look at your answers to the previous questions. The data should allow you to build a prognosis for 2017.
- Work only with the data that you've decided is relevant. Disregard the data for previous years.
- Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.
- Build a box plot for the global sales of all games, broken down by platform. Are the differences in sales significant? What about average sales on various platforms? Describe your findings.
- Take a look at how user and professional reviews affect sales for one popular platform (you choose). Build a scatter plot and calculate the correlation between reviews and sales. Draw conclusions.
- Keeping your conclusions in mind, compare the sales of the same games on other platforms.
- Take a look at the general distribution of games by genre. What can we say about the most profitable genres? Can you generalize about genres with high and low sales?

## Project Description

This project involves analyzing taxi ride data in Chicago. You have been provided with two datasets containing information on taxi companies, ride counts, and drop-off locations. The goal is to perform exploratory data analysis (EDA) to identify patterns, visualize data, and test hypotheses related to ride duration based on weather conditions.

**Datasets:**
- `/datasets/project_sql_result_01.csv`: Contains data on taxi companies and the number of rides taken with each company on November 15-16, 2017.
  - `company_name`: Name of the taxi company
  - `trips_amount`: Number of rides for each taxi company
- `/datasets/project_sql_result_04.csv`: Contains data on the neighborhoods where taxi rides ended in November 2017.
  - `dropoff_location_name`: Names of Chicago neighborhoods where rides ended
  - `average_trips`: Average number of rides that ended in each neighborhood in November 2017
- `/datasets/project_sql_result_07.csv`: Contains data on rides from the Loop to O'Hare International Airport.
  - `start_ts`: Pickup date and time
  - `weather_conditions`: Weather conditions at the time the ride started
  - `duration_seconds`: Ride duration in seconds

## Instructions:

### Step 4: Exploratory Data Analysis (EDA)

1. **Import and Study the Data:**
   - Import the datasets from the provided CSV files.
   - Study the data to understand the information contained within each dataset.

2. **Data Preparation:**
   - Ensure that the data types are correct for each column.
   - Identify and list the top 10 neighborhoods based on the number of drop-offs.

3. **Data Visualization:**
   - Create a graph showing the number of rides for each taxi company.
   - Create a graph for the top 10 neighborhoods by the number of drop-offs.
   - Draw conclusions based on the graphs and explain the results.

### Step 5: Hypothesis Testing

1. **Hypothesis Testing:**
   - Test the hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."
   - Set the significance level (alpha) based on your own decision.

2. **Explain Your Approach:**
   - Formulate the null and alternative hypotheses.
   - Choose the appropriate statistical test to evaluate the hypothesis and explain your choice.

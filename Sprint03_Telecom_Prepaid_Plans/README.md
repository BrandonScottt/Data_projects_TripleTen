## Project Description
You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue to adjust the advertising budget.

You will carry out a preliminary analysis of the plans based on data from 500 Megaline clients. This dataset includes information on client demographics, plan usage, and revenue generation. Your task is to analyze client behavior and determine which prepaid plan brings in more revenue.

## Description of the Plans
- **Surf Plan**
  - Monthly charge: $20
  - 500 monthly minutes, 50 texts, and 15 GB of data included
  - After exceeding the package limits:
    - 1 minute: $0.03
    - 1 text: $0.03
    - 1 GB of data: $10

- **Ultimate Plan**
  - Monthly charge: $70
  - 3000 monthly minutes, 1000 texts, and 30 GB of data included
  - After exceeding the package limits:
    - 1 minute: $0.01
    - 1 text: $0.01
    - 1 GB of data: $7

## Instructions for Completing the Project

### Step 1: Open and Inspect the Data
- **File Paths**:
  - `/datasets/megaline_calls.csv`
  - `/datasets/megaline_internet.csv`
  - `/datasets/megaline_messages.csv`
  - `/datasets/megaline_plans.csv`
  - `/datasets/megaline_users.csv`
- Inspect each dataset to understand its structure and contents.

### Step 2: Data Preparation
- Convert data to the appropriate types.
- Identify and correct any errors in the data.
- For each user, calculate:
  - Number of calls made and minutes used per month.
  - Number of text messages sent per month.
  - Volume of data used per month.
  - Monthly revenue (subtract the free package limits and multiply by the plan's overage charges).

### Step 3: Data Analysis
- Analyze customer behavior by calculating:
  - Monthly usage of minutes, texts, and data for each plan.
  - Mean, variance, and standard deviation of these metrics.
- Plot histograms and describe the distributions.

### Step 4: Hypothesis Testing
- Test the following hypotheses:
  1. The average revenue from users of the Ultimate and Surf plans differs.
  2. The average revenue from users in the NY-NJ area differs from that of users from other regions.
- Select an appropriate alpha value and statistical test for each hypothesis.

### Step 5: Conclusion
- Write a conclusion summarizing your findings and the implications for the advertising budget.

## Data Description

### Users Table
- `user_id`: Unique user identifier
- `first_name`: User's first name
- `last_name`: User's last name
- `age`: User's age (years)
- `reg_date`: Subscription date
- `churn_date`: Date when the user stopped using the service (if missing, the plan was still in use)
- `city`: User's city of residence
- `plan`: Name of the calling plan

### Calls Table
- `id`: Unique call identifier
- `call_date`: Call date
- `duration`: Call duration (minutes)
- `user_id`: User identifier

### Messages Table
- `id`: Unique message identifier
- `message_date`: Message date
- `user_id`: User identifier

### Internet Table
- `id`: Unique session identifier
- `mb_used`: Volume of data used during the session (megabytes)
- `session_date`: Session date
- `user_id`: User identifier

### Plans Table
- `plan_name`: Name of the calling plan
- `usd_monthly_fee`: Monthly charge (USD)
- `minutes_included`: Minutes included in the plan
- `messages_included`: Texts included in the plan
- `mb_per_month_included`: Data volume included in the plan (megabytes)
- `usd_per_minute`: Cost per minute after exceeding the package limits
- `usd_per_message`: Cost per text after exceeding the package limits
- `usd_per_gb`: Cost per additional gigabyte of data after exceeding the package limits

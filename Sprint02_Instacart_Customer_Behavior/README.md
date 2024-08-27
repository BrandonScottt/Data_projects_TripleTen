## Project Description
In this project, you will analyze data from Instacart, a grocery delivery platform. The dataset, originally released for a Kaggle competition in 2017, has been modified to include missing and duplicate values for your analysis. Your goal is to clean the data and generate insights into Instacart customers' shopping habits.

## Datasets
### `instacart_orders.csv`
Each row corresponds to one order on the Instacart app.
- **`order_id`**: ID number that uniquely identifies each order
- **`user_id`**: ID number that uniquely identifies each customer account
- **`order_number`**: The number of times this customer has placed an order
- **`order_dow`**: Day of the week that the order was placed (day 0 is uncertain)
- **`order_hour_of_day`**: Hour of the day that the order was placed
- **`days_since_prior_order`**: Number of days since this customer placed their previous order

### `products.csv`
Each row corresponds to a unique product that customers can buy.
- **`product_id`**: ID number that uniquely identifies each product
- **`product_name`**: Name of the product
- **`aisle_id`**: ID number that uniquely identifies each grocery aisle category
- **`department_id`**: ID number that uniquely identifies each grocery department category

### `order_products.csv`
Each row corresponds to one item placed in an order.
- **`order_id`**: ID number that uniquely identifies each order
- **`product_id`**: ID number that uniquely identifies each product
- **`add_to_cart_order`**: The sequential order in which each item was placed in the cart
- **`reordered`**: 0 if the customer has never ordered this product before, 1 if they have

### `aisles.csv`
- **`aisle_id`**: ID number that uniquely identifies each grocery aisle category
- **`aisle`**: Name of the aisle

## Instructions
1. **Data Exploration**:
   - Open the data files and inspect the contents. Pay attention to nonstandard formatting and set appropriate arguments in `pd.read_csv()` to load the data correctly.
   - Note: `order_products.csv` contains many rows. Use `info(show_counts=True)` to print non-null counts.

2. **Data Preprocessing**:
   - Verify and fix data types (e.g., ensure ID columns are integers).
   - Identify and address missing values.
   - Identify and remove duplicate values.
   - Explain the types of missing and duplicate values found, how you handled them, and why.

3. **Data Analysis**:
   - **[A] Required Analysis**:
     - Verify that 'order_hour_of_day' ranges from 0 to 23 and 'order_dow' ranges from 0 to 6.
     - Plot the number of orders placed per hour of the day.
     - Plot the distribution of orders by day of the week.
     - Plot the time between orders and discuss the minimum and maximum values.

   - **[B] Additional Analysis**:
     - Compare 'order_hour_of_day' distributions for Wednesdays and Saturdays. Plot histograms for both days and describe the differences.
     - Plot the distribution of the number of orders per customer.
     - Identify and list the top 20 most frequently ordered products (include their IDs and names).

   - **[C] Optional Analysis**:
     - Determine the typical number of items bought in one order and describe the distribution.
     - List the top 20 most frequently reordered items (include their IDs and names).
     - Create a table showing the proportion of reorders for each product (include product ID, name, and reorder proportion).
     - Calculate and present the proportion of reorders for each customer.
     - Identify the top 20 items added first to carts (include product IDs, names, and count of first placements).

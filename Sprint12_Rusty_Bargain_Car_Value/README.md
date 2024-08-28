## Project Description

Rusty Bargain, a used car sales service, is developing an app to attract new customers by allowing them to quickly find out the market value of their cars. This project involves building a machine learning model to determine the value of a car based on historical data, including technical specifications, trim versions, and prices. Rusty Bargain is particularly interested in:

- The quality of the prediction.
- The speed of the prediction.
- The time required for training the model.

## Data Description

The dataset contains the following features:

- **DateCrawled:** The date the profile was downloaded from the database.
- **VehicleType:** The vehicle body type.
- **RegistrationYear:** The year the vehicle was registered.
- **Gearbox:** The type of gearbox.
- **Power:** The power of the vehicle (in horsepower).
- **Model:** The model of the vehicle.
- **Mileage:** The mileage of the vehicle (in kilometers).
- **RegistrationMonth:** The month the vehicle was registered.
- **FuelType:** The type of fuel used by the vehicle.
- **Brand:** The brand of the vehicle.
- **NotRepaired:** Indicates whether the vehicle has been repaired.
- **DateCreated:** The date the profile was created.
- **NumberOfPictures:** The number of pictures of the vehicle.
- **PostalCode:** The postal code of the profile owner.
- **LastSeen:** The date of the last activity of the user.

**Target:**

- **Price:** The price of the vehicle in Euros.

## Answer these questions:
- Train different models with various hyperparameters (You should make at least two different models, but more is better. Remember, various implementations of gradient boosting don't count as different models.) The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.
- Analyze the speed and quality of the models.

## Project Description

You work for the OilyGiant mining company. Your task is to find the best place for a new oil well.

## Steps to choose the location:

1. **Data Collection:** Gather the parameters of oil wells in the selected regions, including oil quality and reserve volumes.
2. **Model Training:** Build a model to predict the volume of reserves in new wells.
3. **Well Selection:** Identify the oil wells with the highest predicted reserves.
4. **Profit Maximization:** Choose the region with the highest total profit from the selected wells.

## Data Description:

Geological exploration data for three regions are stored in the following files:
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

Each dataset includes:
- `id` — unique identifier for the oil well
- `f0`, `f1`, `f2` — three features representing geological characteristics
- `product` — volume of reserves in the oil well (in thousand barrels)
  
## Answer these questions:
- Train and test the model for each region
- Prepare for profit calculation
- Write a function to calculate profit from a set of selected oil wells and model predictions
- Calculate risks and profit for each region

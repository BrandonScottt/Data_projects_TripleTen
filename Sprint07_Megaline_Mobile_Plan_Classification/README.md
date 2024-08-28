## Project Description
Megaline, a mobile carrier, has identified that many of their subscribers are still using legacy plans. To encourage users to switch to one of their newer plans, Smart or Ultra, Megaline needs a model that can analyze subscribers' behavior and recommend the most suitable plan. This project focuses on developing a classification model that can accurately predict whether a subscriber should switch to the Smart or Ultra plan based on their monthly usage data.

## Data Description
The dataset contains monthly behavior information for each subscriber, including:
- `calls`: Number of calls made.
- `minutes`: Total duration of calls in minutes.
- `messages`: Number of text messages sent.
- `mb_used`: Internet traffic used in MB.
- `is_ultra`: Target variable indicating the plan for the current month (Ultra = 1, Smart = 0).

## Answer these questions:
- Split the source data into a training set, a validation set, and a test set.
- Investigate the quality of different models by changing hyperparameters. Briefly describe the findings of the study.
- Check the quality of the model using the test set.
- Additional task: sanity check the model. This data is more complex than what you’re used to working with, so it's not an easy task. We'll take a closer look at it later.

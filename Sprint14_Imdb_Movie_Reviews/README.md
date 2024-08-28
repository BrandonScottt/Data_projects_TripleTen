## Project Overview

The Film Junky Union, a community for classic movie enthusiasts, is developing a system to automatically filter and categorize movie reviews. The objective is to build a model that classifies reviews as positive or negative using a dataset of IMDB movie reviews with polarity labels. The goal is to achieve an F1 score of at least 0.85.

## Data Description

- **File Path**: `imdb_reviews.tsv`
- **Fields**:
  - `review`: The text of the review.
  - `pos`: The target variable, where '0' represents a negative review and '1' represents a positive review.
  - `ds_part`: Indicates if the entry is from the 'train' or 'test' dataset.

## Answer these questions:
- Conduct an EDA and make your conclusion on the class imbalance.
- Preprocess the data for modeling.
- Train at least three different models for the given train dataset.
- Test the models for the given test dataset.
- Compose a few of your own reviews and classify them with all the models.
- Check for differences between the testing results of models in the above two points. Try to explain them.
- Present your findings.

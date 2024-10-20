# Multiple Linear Regression on 50 Startups Dataset

This project demonstrates how to perform multiple linear regression using Python and Scikit-Learn on the **50 Startups** dataset. The dataset contains data on 50 startups with information on R&D Spend, Administration, Marketing Spend, and State, along with the corresponding profit.

## Project Overview

In this project, we:

1. **Preprocess the data**: Use OneHotEncoding to handle categorical variables (State).
2. **Avoid the dummy variable trap**: Remove one of the one-hot encoded columns.
3. **Split the data**: Divide the dataset into training and test sets.
4. **Fit the multiple linear regression model**: Train the model on the training set.
5. **Evaluate the model**: Measure the accuracy of the model using training and test scores.

## Libraries and Dependencies

- `numpy`: For array operations
- `pandas`: For data handling
- `matplotlib`: For plotting (not used in this case, but imported)
- `scikit-learn`: For machine learning tasks such as encoding, splitting, and regression
    ```bash
    pip install numpy pandas matplotlib scikit-learn

Cloning and Running the Project
Clone this repository to your local machine:

    ```bash    
    git clone https://github.com/your-username/50-startups-regression.git
Navigate to the project directory:

    ```bash
    
    cd 50-startups-regression
Ensure that you have the 50_Startups.csv dataset in the same directory as the script, or adjust the dataset path accordingly in the code.

Run the Python script:

```bash

python regression_model.py


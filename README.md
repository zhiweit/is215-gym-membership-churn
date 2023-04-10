# is215-gym-membership-churn

Jupyter notebook is part of IS215 Digital Business Transformation Technologies project to show how analytics/AI can help reduce gym membership churn.

This notebook is used to show how Anytime Fitness can identify features that contribute to customer churn as part of IS215 Digital Business Transformation and Technology project.

The purpose of proposing digital transformation for Anytime Fitness is to
1. boost membership signups
2. decrease the rate of member churn.

Using example dataset provided by <a href="https://www.kaggle.com/datasets/ellanihill/model-fitness-customer-churn">Model Fitness (customer churn)</a>, Anytime Fitness can similarly identify the factors that contribute to customer churn and formulate strategies to retain them so that it can decrease its membership churn. 

### Installations
- If using `conda`
    - Open a command prompt or powershell or terminal.
    - Change directory to the current working directory of this notebook + `is215env.yaml` file
    - run `conda env create -n is215 --file is215env.yaml` to create a conda environment named is215 from is215env.yaml
    - Open jupyter notebook from your `base` environment
    - Select `Kernel` > `conda env:is215` from the menu bar in jupyter notebook to activate the newly created is215 conda environment.

- Else if Using `pip`
    - `pip install <packagename>` for each of the package that is listed in the dependencies below
```
pip install pandas
pip install -U scikit-learn
pip install plotly_express==0.4.0
```

### Broad strategy to analyse customer churn data
1. Find the features that contribute most to churn. Come up with strategies that change these features to retain customers.
2. For those who churn, group them into user profiles/clusters based on the most significant fields. Focus on retaining the particular groups identified.

### Viewing
- View the `Gym-Predict-Churn.html` to see the output without executing any code, or
- Open and run the `Gym-Predict-Churn.ipynb` jupyter notebook locally

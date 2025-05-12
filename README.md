# Heart Failure Prediction and Interpretability

This project uses the [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) from Kaggle to explore predictive modeling and interpretability techniques.

The focus is on understanding the dataset and applying methods to enhance interpretability, such as Logistic Lasso Regression, SHAP, and Neural Additive Models.

To reproduce the results, first create a virtual environment by running the following command:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
``` 
Then run the notebooks inside the `notebooks` directory in the following order:

1. `q1-eda.ipynb` (Exploratory Data Analysis)
2. `q2-lr.ipynb`  (Logistic Lasso Regression)
3. `q3-mlp.ipynb` (Multilayer Perceptron)
4. `q4-nam.ipynb` (Neural Additive Model)

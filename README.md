# Dividend Yield Prediction using Artificial Neural Network (ANN)

A neural network model that predicts stock dividend yield using historical stock data. The project walks you through data preparation, model building, training, evaluation, and prediction.

---

## Features

- Straightforward ANN architecture built with TensorFlow and Keras  
- Preprocessing steps including scaling and training-test split  
- Model training on real stock market data  
- Evaluation based on performance metrics (e.g. MSE or MAE)  
- Make forecasts of dividend yield using new input data  
- Jupyter Notebook for hands-on exploration

---

## Project Structure

- `data/` – raw and processed datasets used for training and testing  
- `notebooks/` – Jupyter Notebooks for data analysis, model training and evaluation  
- `requirements.txt` – Python libraries needed to run the project  
- `LICENSE` – MIT Licence for this project  
- `README.md` – this file with overview and instructions

---

## Tools & Libraries

- Python 3.x  
- TensorFlow  
- Keras  
- NumPy  
- Pandas  
- scikit-learn  
- Matplotlib or Seaborn (for visualisation)

---

## How to use

### 1. Clone the repository  
```bash
git clone https://github.com/nurulashraf/ann-dividend-yield-prediction.git
cd ann-dividend-yield-prediction
````

### 2. Install dependencies

It’s best to use a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook dividend_yield_prediction.ipynb
```

Inside the notebook, you’ll go through steps to:

* Load and explore historical stock data
* Clean and scale the data
* Define and train an ANN model
* Evaluate how well the model predicts dividend yield
* Make predictions using new stock inputs

---

## Licence

This work is offered under the MIT Licence. See the `LICENSE` file for full details.


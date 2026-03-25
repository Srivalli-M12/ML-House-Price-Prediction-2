# ML-House-Price-Prediction-2
This project is a Machine Learning regression pipeline designed to predict the sale prices of houses in King County, USA. It explores the dataset, visualizes geographical pricing trends, and compares the performance of a baseline model against an advanced ensemble method.

## 📊 Dataset
The project uses the `kc_house_data.csv` dataset, which contains historical house sale data including features such as:
* Number of bedrooms and bathrooms
* Square footage of living space and lot
* Number of floors
* Geographical coordinates (Latitude/Longitude)

## 🚀 Models & Performance
The notebook trains and evaluates two different regression models to predict the continuous variable (Price):

1. **Linear Regression (Baseline):** * Achieved an accuracy/R² score of **~73%**.
2. **Gradient Boosting Regressor (Optimized):** * Configured with `n_estimators=400`, `max_depth=5`, and `learning_rate=0.1`.
   * Achieved a highly accurate R² score of **~91%**.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn

## 💻 How to View the Project
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed, or upload the files to Google Colab.
3. Install the required libraries (`pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
4. Open `housesales.ipynb` and run the cells from top to bottom to view the data visualizations and model training process.

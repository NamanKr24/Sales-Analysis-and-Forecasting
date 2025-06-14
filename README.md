# Sales Analysis and Forecasting

## 📊 Project Overview

In a retail business, anticipating future sales is key to managing inventory, optimizing operations, and setting realistic targets.  
This project analyzes historical sales for the **Office Supplies** category and forecasts future performance using classical time series techniques.  
By blending exploratory analysis with statistical forecasting models like **ARIMA** and **Prophet**, it offers insights into demand patterns and equips decision-makers with reliable projections.

---

## 🚀 Features

1. **Data Cleaning & Preprocessing**  
   - Handles missing values, formats date fields, and filters for Office Supplies category.  
   - Converts raw sales entries into a structured time series format.

2. **Exploratory Data Analysis (EDA)**  
   - Visualizes long-term sales trends, seasonality, and cyclical behaviors.  
   - Identifies periods of sales spikes and dips.

3. **Time Series Decomposition**  
   - Breaks the sales signal into trend, seasonal, and residual components for interpretability.

4. **Forecasting Models**  
   - Implements both **ARIMA** (Auto-Regressive Integrated Moving Average) and **Facebook Prophet**.  
   - Includes parameter tuning and residual diagnostics for validation.

5. **Performance Evaluation**  
   - Compares predicted vs. actual sales using metrics and visualizations.  
   - Highlights strengths and limitations of each model in real-world forecasting.

---

## 📂 Dataset

- **Source:** `train.xlsx`  
- **Focus:** Monthly sales for **Office Supplies**  
- **Fields Used:**  
  - `Order Date`: Used for time series indexing  
  - `Sales`: Target variable for forecasting

*Data is internally filtered and aggregated before modeling.*

---

## 🛠️ Technologies Used

- **Languages & Tools**: Python, Jupyter Notebook  
- **Libraries**:  
  - `Pandas`, `NumPy` – Data manipulation  
  - `Matplotlib`, `Seaborn` – Visualization  
  - `Statsmodels` – ARIMA modeling  
  - `Prophet` – Additive time series modeling by Meta  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NamanKr24/Sales-Analysis-and-Forecasting.git
   cd Sales-Analysis-and-Forecasting
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 💡 Usage
1. Place `train.xlsx` in the project directory.
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Sales_Analysis_Forecasting.ipynb
   ```
3. Follow the notebook cells sequentially to:

   - Explore the dataset

   - Visualize trends and seasonality

   - Run and evaluate forecasting models

   - Compare predictions and extract insights

## 📈 Results
- Clear monthly trend detected with seasonal dips and surges in Office Supplies sales.

- Prophet captured recurring seasonal trends more effectively, while ARIMA excelled on short-term fluctuations.

- Both models produced realistic projections aligning with past behavior.

- Evaluation focused on visual fit and residuals; metric-based scoring can be added in future iterations.

## 🤝 Contributing
Contributions are welcome!

If you’d like to suggest improvements, add new forecasting models, or expand to other product categories:

1. Fork the repo

2. Create a new branch

3. Push your feature

4. Submit a pull request

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

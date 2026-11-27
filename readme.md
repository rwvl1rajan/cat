# 🐼 Pandas Analyzer & Data Visualization

<p align="center">
  <img src="https://cataas.com/cat" alt="Cute cat" width="220">
</p>

<p align="center">
  A menu-driven Python project for exploring, cleaning, analyzing, and visualizing CSV datasets using Pandas.
</p>

---

## 📌 About the Project

**Pandas Analyzer & Data Visualization** is a Python project that helps users perform common data analysis tasks on a CSV file through a menu-driven interface.

It uses a `data_analyzer` class to load a dataset and provide options for exploring data, handling missing values, performing DataFrame operations, generating descriptive statistics, and creating visualizations.

## ✨ Features

- **Load a dataset:** Read CSV files using Pandas.
- **Explore data:**
  - Display the first five rows.
  - Display the last five rows.
  - Display random rows.
  - Check the number of rows and columns.
  - View column data types.
  - Display basic dataset information.
- **DataFrame operations:**
  - Create pivot tables.
  - Check and remove duplicate rows.
- **Handle missing values:**
  - Drop rows with missing values in a selected column.
  - Fill missing numerical values using the median.
  - Fill missing categorical values using the mode.
  - Drop rows containing missing values.
- **Descriptive statistics:** Generate summary statistics with `describe()`.
- **Data visualization:**
  - Box plot
  - Count plot
  - Distribution plot
  - Bar plot
  - Line plot
  - Scatter plot
- **Save processed data:** The `save_data` class is designed to save the resulting DataFrame as `correct_data.csv`.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data loading, cleaning, and analysis |
| NumPy | Numerical computing |
| Seaborn | Statistical data visualization |
| Matplotlib | Plot rendering |

## 📂 Project Structure

```text
project-folder/
│
├── PR. 7 Pandas Analyzer & Data Visualization.ipynb
├── correct_data.csv
└── README.md
```

Your dataset filename and notebook filename may differ depending on your setup.

## ⚙️ Installation

1. **Clone this repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Move into the project folder:**

   ```bash
   cd <repository-folder>
   ```

3. **Install the required libraries:**

   ```bash
   pip install pandas numpy seaborn matplotlib jupyter
   ```

4. **Open the notebook:**

   ```bash
   jupyter notebook
   ```

   Open `PR. 7 Pandas Analyzer & Data Visualization.ipynb` and run its cells.

## ▶️ How to Use

1. Keep your CSV dataset in the project folder, or update the dataset path in the notebook.
2. Run the notebook cells in order.
3. When the analyzer starts, choose an option from the displayed menu.
4. Follow the prompts to explore, clean, analyze, or visualize your dataset.

The notebook currently initializes the analyzer with:

```python
path = "correct_data.csv"
a = data_analyzer(path)
```

Change `path` to the name or location of your own CSV file when needed.

## 🐱 A Little Cat Break

<p align="center">
  <img src="https://cataas.com/cat?width=320&height=220" alt="Cute cat relaxing" width="260">
  <br>
  <em>Keep calm and analyze data.</em>
</p>

## 📚 Concepts Covered

- Reading CSV files with Pandas
- Exploring DataFrames
- Selecting and working with columns
- Handling missing data
- Removing duplicate records
- Creating pivot tables
- Generating descriptive statistics
- Creating plots with Seaborn and Matplotlib
- Using Python classes and methods

## 🚀 Future Improvements

- Add input validation and clearer error messages.
- Improve navigation so users can return to the main menu consistently.
- Add more chart types and customization options.
- Add an option to export cleaned data from the menu.
- Improve handling of numerical and categorical columns.

## 🤝 Contributing

Suggestions and improvements are welcome. You can fork the repository, make changes, and submit a pull request.

---

<p align="center">
  Made with Python, Pandas, and a little bit of 🐱
</p>

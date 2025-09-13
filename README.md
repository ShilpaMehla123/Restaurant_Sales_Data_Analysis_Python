# 📊 Restaurant_Sales_Data_Analysis_Python
This project demonstrates how to perform Sales Data Analysis using Python. 
You will learn how to clean, transform, and analyze real-world sales data, and how to answer key business questions using pandas, matplotlib, and other Python tools.

## 📁 Raw File
[DOWNLOAD RAW DATA](https://www.kaggle.com/datasets/rohitgrewal/restaurant-sales-data/data)
## 📁 Output File
**`Restaurant_Analysis_Python.ipynb`**  
## ⚙️ Setup Instructions
1. Clone the repository
  ```bash
  git clone https://github.com/ShilpaMehla123/Restaurant_Sales_Data_Analysis_Python.git
  cd Restaurant_Sales_Data_Analysis_Python
  ```
2. Install dependencies
Make sure you have Python installed. Then install the required libraries:
 ```bash
 pip install pandas matplotlib
 ```
3. Run the notebook
Open the .ipynb file using Jupyter Notebook or Visual Studio Code and run all the cells:

 ```bash
 jupyter notebook Restaurant_Analysis_Python.ipynb
 ```
## 🧠 Concepts and Commands Used

| Command / Method                              | Purpose                                              |
| --------------------------------------------- | ---------------------------------------------------- |
| `reset_index()`                               | Convert Series index to a column to form a DataFrame |
| `loc[]`                                       | Select rows/columns by labels                        |
| `info()`                                      | Display basic info about the DataFrame               |
| `drop()`                                      | Remove columns or rows                               |
| `str.strip().str.replace()`                   | Clean text and remove extra spaces                   |
| `duplicated()`                                | Show duplicate rows                                  |
| `drop_duplicates(inplace=True)`               | Remove duplicate rows                                |
| `round()`                                     | Round numerical values                               |
| `pd.to_datetime()`                            | Convert column to datetime format                    |
| `groupby()`                                   | Group data by column values                          |
| `std()` / `var()` / `mean()`                  | Calculate standard deviation, variance, mean         |
| `agg()`                                       | Aggregate multiple operations on groups              |
| `head()`                                      | Show first N rows                                    |
| `columns` / `dtype` / `astype()`              | Check or change column datatypes                     |
| `unique()` / `nunique()` / `value_counts()`   | Explore unique values and their counts               |
| `describe()`                                  | Get summary statistics of numerical columns          |
| `plot(kind='bar')`                            | Plot bar graphs                                      |
| `plt.figure(figsize=())` / `plt.title()` etc. | Customize plots                                      |
| `sort_values(ascending=False)`                | Sort data in descending order                        |
| `dt.month`                                    | Extract month from datetime                          |


## 📈 What You’ll Learn
-	Data cleaning and preprocessing
-	Handling duplicates and missing values
- Exploratory Data Analysis (EDA)
- Grouping and aggregating data
- Visualizing sales trends and insights
- Drawing conclusions from real-world data

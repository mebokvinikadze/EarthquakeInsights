# Earthquake Data Analysis Project 🌍

Welcome to the Earthquake Data Analysis project! This repository contains a mini-project that analyzes the "Significant Earthquakes 1965-2016" dataset. The project involves various data manipulation, reshaping, and visualization tasks to derive insights from the data.

## Project Overview 📊

### 1. Data Manipulation
- Filled missing values in the 'Depth' column with the mean depth.
- Removed the 'Time' column as it was not needed for the analysis.
- Split the 'Date' column into 'Year', 'Month', and 'Day' for better date handling.

### 2. Categorize Numerical Data
- Categorized earthquake magnitudes into three categories: 'Low', 'Medium', and 'High'.

### 3. Data Reshaping
- Used the `melt()` function to transform the data into a long format.
- Applied the `pivot()` function to create a summary table of average depths by year and magnitude category.

### 4. Data Visualization
Created four different types of charts to visualize the data:
- **Line Chart**: Shows the yearly trend of earthquake magnitudes.
- **Bar Chart**: Displays the average monthly earthquake magnitudes.
- **Scatter Plot**: Plots the locations of earthquakes by magnitude.
- **Histogram**: Illustrates the distribution of earthquake magnitudes.

### 5. Date Transformation
- Extracted the year and month from the 'Date' column.
- Resampled the data by year to calculate the mean magnitude.

## Getting Started 🚀

### Prerequisites
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/earthquake-data-analysis.git
Navigate to the project directory:

bash
Copy code
cd earthquake-data-analysis
Install the required packages:

bash
Copy code
pip install pandas numpy matplotlib seaborn
Usage
Run the Python script to perform the data analysis:

bash
Copy code
python earthquake_analysis.py
Results
The results of the analysis, including the cleaned data and generated charts, are saved in the project directory.

Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome!

License
This project is licensed under the MIT License.

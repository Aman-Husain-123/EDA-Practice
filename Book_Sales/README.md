# Book Sales EDA

This project contains an exploratory data analysis (EDA) of a book sales dataset. The analysis is performed using Python, with libraries such as pandas, matplotlib, seaborn, and numpy. The main notebook is `eda-on-book-sales.ipynb`.

## Dataset
- **Books_Data_Clean.csv**: The cleaned dataset containing information about books, including publishing year, genre, author, ratings, sales, language, and publisher revenue.

## Main Steps in the Analysis
1. **Data Loading & Cleaning**
   - Load the dataset using pandas.
   - Remove rows with missing or invalid values (e.g., negative publishing years, missing book names).
   - Check for duplicates and unique values.

2. **Exploratory Data Analysis**
   - Summary statistics of numerical columns.
   - Distribution plots for publishing year, genres, and language codes.
   - Box plots and scatter plots to explore relationships between ratings, sales, and other features.
   - Grouped aggregations (e.g., total sales by author, publisher, year).

3. **Visualization**
   - Histograms, bar charts, pie charts, line charts, and box plots are used to visualize trends and distributions in the data.

## How to Use
1. Open `eda-on-book-sales.ipynb` in Jupyter or VS Code.
2. Ensure you have the required Python libraries installed:
   - pandas
   - numpy
   - matplotlib
   - seaborn
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## Insights
- The dataset mostly contains newer books.
- Genre and language distributions are visualized.
- Relationships between price, units sold, ratings, and revenue are explored.

## Folder Structure
```
Book_Sales/
├── Books_Data_Clean.csv
└── eda-on-book-sales.ipynb
```

## Author
- Data Scientist Practice Project

---
This project is for educational and practice purposes only.

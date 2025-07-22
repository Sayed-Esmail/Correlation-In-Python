# Movie Correlation Analysis

## Project Overview
This project involves a comprehensive data analysis of a movie dataset to identify key correlations between various film attributes. The analysis utilizes Python to explore relationships such as the impact of budget on gross revenue, and audience scores on movie success. The insights gained can be valuable for understanding trends in the entertainment industry and informing strategic decisions.

## Features
- Data loading and initial exploration.
- Handling of missing data.
- Identification and analysis of outliers.
- Visualization of relationships between key numerical attributes (e.g., gross vs. budget, gross vs. score).
- Calculation of Pearson and Spearman correlation coefficients for numerical features.

## Technologies Used
- Python
- Pandas (for data manipulation and analysis)
- Seaborn (for statistical data visualization)
- Matplotlib (for creating static, interactive, and animated visualizations)
- NumPy (for numerical operations)

## How to Run
1. Ensure you have Python installed. It is recommended to use a virtual environment.
2. Install the required libraries:
   ```bash
   pip install pandas seaborn matplotlib numpy
   ```
3. Download the `movies.csv` dataset. (Note: The original notebook references a local path `D:\movies.csv (1)\movies.csv`. Please ensure the dataset is accessible in your environment or update the path in the notebook.)
4. Open the Jupyter Notebook `CorrelationInPython.ipynb`.
5. Run all cells in the notebook to execute the analysis and generate visualizations.

## Data Source
The dataset used in this project is `movies.csv`, which contains various attributes related to movies, including name, rating, genre, year, released date, score, votes, director, writer, star, country, budget, gross, and runtime.


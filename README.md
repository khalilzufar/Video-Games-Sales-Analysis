# Video Game Sales Analysis

A data-analysis project that explores video-game sales by platform, genre, year, and region.

## Objective

Identify regional sales patterns and use them to understand which platforms or genres perform well or underperform across North America, Europe, Japan, and other markets.

## Dataset

The repository includes the original and cleaned CSV files:

- video_games_sales.csv — 16,598 records across 11 columns.
- video_games_sales_cleaned.csv — data after removing rows with missing release years.

The regional sales fields are North America, Europe, Japan, and Other, measured in millions of units.

## Analysis workflow

1. Inspect data types, missing values, and duplicate records.
2. Clean the release-year field and export the cleaned dataset.
3. Compare platform and genre sales by region.
4. Analyze sales trends over time.
5. Compare regional distributions with descriptive statistics.
6. Test the difference between North American and European sales.

## Outputs

- video_games_sales_analysis.ipynb — complete EDA and statistical analysis.
- [Interactive Tableau visualization](https://public.tableau.com/views/DataVisualizationVideoGameSales/VisualisasiData?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [Source dataset on Kaggle](https://www.kaggle.com/datasets/ulrikthygepedersen/video-games-sales)

## Run locally

~~~bash
python -m pip install pandas numpy matplotlib seaborn scipy jupyter
jupyter notebook video_games_sales_analysis.ipynb
~~~

## Author

[Khalil Zufar](https://github.com/khalilzufar)

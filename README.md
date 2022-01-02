# Basic_Risk_Reward_Analysis
This notebook demonstrates the use of the pandas and numpy libraries to perform some basic analysis on risk and reward of stock funds. The analysis considers four portfolio funds with respect to each other and the S&P 500. It constructs and compares smoothed time series of classic financial metrics such as returns, Sharpe Ratios and market Betas. Finally, it makes a recommendation on the best fund offer for portfolio diversification and capital preservation.

## Technologies

This workbook was written in python 3.7. It uses the following libraries:

* [pandas](https://github.com/pandas-dev/pandas) - For dataframe tools and quantitative analysis.

* [numby](https://github.com/numpy/numpy) - For mathematical/statistical tools and array functions.

* [pathlib](https://github.com/budlight/pathlib) - For importing and reading csv files.

* [matplotlib](https://github.com/matplotlib/matplotlib) - For creating graphs and charts.

---

## Data

NAV Data for 4 portfolio funds and the S&P 500 are available in a CSV file named whale_navs.csv. The index is a date field (called "date"). Each column represents a daily times series. The funds in question are Berkshire Hathaway Inc., Paulson & Co. Inc, Soro Fund Management LLC, and Tiger Global Management LLC. The date range spans from October, 2014 to September, 2020.


---

## Contributors

Rachael Donham
rachaeldonham@gmail.com


---

## License

MIT
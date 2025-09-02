# 📊 Dataset Overview: Historical Automobile Sales

## 🔗 Source
[Download CSV](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv)

## 📄 Description
This dataset contains monthly automobile sales data from 1980 to 2023. It includes economic indicators and marketing metrics to help analyze trends during recession and non-recession periods. The data is used to power all visualizations in the dashboard.

## 📁 Variables

| Column Name             | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `Date`                 | Timestamp of observation                                                    |
| `Recession`            | Binary indicator (1 = recession, 0 = non-recession)                         |
| `Automobile_Sales`     | Number of vehicles sold                                                     |
| `GDP`                  | Per capita GDP in USD                                                       |
| `unemployment_rate`    | Monthly unemployment rate                                                   |
| `Consumer_Confidence`  | Synthetic index of consumer sentiment                                       |
| `Seasonality_Weight`   | Seasonal adjustment factor                                                  |
| `Price`                | Average vehicle price                                                       |
| `Advertising_Expenditure` | Marketing spend by XYZAutomotives                                       |
| `Vehicle_Type`         | Category of vehicle sold (e.g., Superminicar, Executivecar, Sports)         |
| `Competition`          | Market competition metric                                                   |
| `Month`                | Extracted from `Date`                                                       |
| `Year`                 | Extracted from `Date`                                                       |

## 📈 Usage in Project
This dataset powers all visualizations in the dashboard, including:

- Yearly and monthly sales trends
- Recession impact analysis
- Vehicle type comparisons
- Advertising expenditure breakdowns

## 📜 License
This dataset is publicly available for educational use via IBM Skills Network.

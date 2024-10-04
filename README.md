# 🌟 Kardashian-Jenner Google Trends Analysis

## 📝 Objective
This project analyzes Google search interest data for the Kardashian-Jenner sisters from 2007 to present. We aim to visualize trends over time and answer key questions about their relative popularity using data from Google Trends.

## ❓ Key Questions
- Is Kim Kardashian still the most popular sister?
- How has search interest changed for each sister over time?
- Which family line, Kardashian or Jenner, is more popular?

## 📊 Data
- **Google Trends data**: Search interest data from 2007 to present, with columns for each sister:
  - `month`: Time period (monthly).
  - `kim`, `khloe`, `kourtney`, `kendall`, `kylie`: Search interest values (0-100 scale).

## 🧠 Approach
1. **Data Cleaning**: Removed "<" signs, converted strings to integers, and standardized column names.
2. **Data Transformation**: Converted the `month` column to `datetime` format and set it as the index.
3. **Rolling Averages**: Applied 12-month rolling averages to smooth out fluctuations.
4. **Comparison**: Calculated average search interest for the Kardashian sisters and the Jenner sisters.

## 📈 Results
- Kim Kardashian remains the most famous sister, although Kylie has occasionally surpassed her, particularly in 2017-2018.
- The Kardashians and Jenners have had comparable popularity since 2015, with no consistent frontrunner.

## 🚀 Conclusion
Despite the ups and downs, Kim Kardashian remains a dominant figure in search interest. However, Kylie has surged in recent years due to her business ventures and personal milestones. Both family lines continue to be highly relevant.

## 🛠️ Tools & Libraries
- **pandas**: Data manipulation
- **matplotlib**: Data visualization
- **Google Trends**: Source of data

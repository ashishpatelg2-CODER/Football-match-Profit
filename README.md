# Football Match Predictor & Value Bet Finder

## 📌 Project Overview
This repository contains a technical sports analytics engine designed to identify market inefficiencies in football betting. By utilizing a **Poisson Distribution model**, the system calculates the "Fair Odds" of a match and compares them against bookmaker prices to find high-value, profitable opportunities.

## 🚀 Key Features
* **Probability Modeling:** Uses attack and defense strength metrics to predict Win/Draw/Loss percentages.
* **Value Detection:** Automatically identifies "Value Bets" where Bookmaker Odds > Calculated Fair Odds.
* **Baseline Analytics:** Analyzes league-wide trends (e.g., the 46.1% Home Win rate) to set betting benchmarks.
* **Power Rankings:** Generates automated strength ratings for teams based on historical scoring and defensive data.

## 🛠️ Technical Stack
* **Python:** Core analytical engine.
* **SciPy:** Used for Poisson statistical modeling.
* **Pandas:** Data manipulation of CSV betting datasets.
* **Matplotlib:** Visualization of winning rates and team performance.

## 📊 Market Insights
The analysis of the provided dataset (`D1.csv`) revealed:
* **Home Advantage:** 46.1% frequency.
* **Profit Driver:** Consistently identifying teams like Dortmund whose win probability (~67%) was significantly undervalued by standard market opening odds.



## 📁 File Structure
* `predict.py`: The main calculation script for match probabilities.
* `D1 .csv`: Historical football data and bookmaker odds.
* `winning_rate_format.png`: Visualization of overall league results.
* `Football_Data_Analysis.pptx`: Technical presentation of the findings.

## 📝 Conclusion
This project demonstrates that "real money" in sports trading is made through mathematical discipline rather than guesswork. By beating the closing line and applying strict bankroll management, this model provides a framework for long-term profitability.

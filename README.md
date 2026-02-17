# Premier League Winner Prediction Project 🏆

## Project Overview
A comprehensive data science project that predicts Premier League outcomes using 10 years of historical data (2016-2025) combined with current season performance (2025-26). The project uses machine learning to predict:
- **League Winner** 
- **Top 4 Teams** (Champions League qualification)
- **Europa League Places** (5th-6th positions)
- **Relegation Candidates** (Bottom 3 teams)

## Key Findings 📊
Based on 26 matches played in 2025-26 season:
- **Title Winner:** Arsenal (82 predicted points)
- **Champions League (Top 4):** Arsenal, Man City, Aston Villa, Man United
- **Europa League (5th-6th):** Chelsea, Liverpool  
- **Relegation Zone:** West Ham, Burnley, Wolves

## Dataset Features
- **10 seasons** of data (2016-17 to 2025-26)
- **200 total records** (20 teams × 10 seasons)
- **Key metrics:** Rk, Squad, MP, W, D, L, GF, GA, GD, Pts, Pts/MP

## Methodology
1. **Data Collection:** Real Premier League standings from official sources
2. **Feature Engineering:** Created projected_points, win_probability, is_champion
3. **Machine Learning:** Random Forest Regression to predict final points
4. **Validation:** Used 9 seasons (2016-2025) for training, current season for testing

## Tools & Technologies
- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **Scikit-learn** - Machine learning (Random Forest)
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Development environment

## Project Structure

## Key Insights
- **Arsenal leads** with highest points per match (2.19) after 26 games
- **Man City** remains strong contender despite being 4 points behind
- **Historical dominance:** Man City won 6 of last 9 titles
- **Current season** shows more competitive title race than recent years

## Model Performance
- **Algorithm:** Random Forest Regression (180 estimators)
- **Features:** Pts/MP, GD, W, L, projected_points
- **Approach:** Predicts final points rather than binary win/loss
- **Training data:** 180 samples (9 seasons × 20 teams)

## How to Run
1. Clone the repository
2. Install requirements: `pip install pandas scikit-learn matplotlib seaborn`
3. Run `generate_datasets.py` to create datasets
4. Open `premier_league_analysis.ipynb` in Jupyter Notebook
5. Execute all cells to see predictions

## Future Improvements
- Add player-level statistics
- Include injury/transfer data
- Implement time-series forecasting
- Add confidence intervals for predictions

## Author
**Natnael Haile**  
Data Science Student  
*Passionate about sports analytics and machine learning*

---
*Last updated: February 2026*
*Current season: 2025-26 (26/38 matches played)*

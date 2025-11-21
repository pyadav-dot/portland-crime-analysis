# portland-crime-analysis
Analyze Portland crime data (648k+ records) using Python, Pandas, Seaborn &amp; SQL; includes ML-based insights for patterns and high-risk neighborhoods.
# Tools & Technologies
- **Programming Languages:** Python  
- **Data Analysis & Visualization:** Pandas, NumPy, Seaborn, Matplotlib ,Scikit-learn  
- **Machine Learning:** Regression/classification model  
- **Others:** Jupyter Notebook, Git/GitHub  
## Dataset
- Source: Portland Crime Open Data  
- Records: 648,304  
- Features include neighborhood, offense type, date/time, location coordinates, etc.
- Link :https://public.tableau.com/app/profile/portlandpolicebureau/viz/MonthlyReportedCrimeStatistics/MonthlyStatistics
- ## Team
- 3 members (contributed actively to data analysis and visualization)
- ## Work Done
1. **Data Cleaning & Preprocessing:**  
   - Handled missing values and inconsistent entries  
   - Converted timestamps for time-based analysis  

2. **Exploratory Data Analysis (EDA):**  
   - Visualized crime trends by neighborhood and hour of the day  
   - Identified most common crime types  
   - Analyzed correlation between distance from downtown and crime frequency  

3. **Machine Learning Applications:**  
   - **Predicting Offense Type by Hour**  
   - Built a **Multinomial Logistic Regression** model to predict offense type based on the hour of occurrence.  
   - Evaluated performance using **accuracy**, **F1 score**, and **confusion matrix**.  
   - Provided insights on which offense types are more likely at different times of the day.  
 
   - **Geospatial Crime Forecasting**  
   - Used latitude/longitude and temporal features to predict monthly offense counts per neighborhood.  
   - Trained a **Random Forest Regressor**, achieving better accuracy compared to baseline linear models.  
   - Visualized predicted vs actual crime counts to identify high-risk areas and trends.    

4. **Visualization & Insights:**  
   - Heatmaps, bar charts, and interactive plots to communicate findings  
   - Key insights can guide local law enforcement in resource allocation  
## Project Structure
portland-crime-analysis/
│
├─ notebooks/
│ ├─ EDA.ipynb
│ └─ ML_analysis.ipynb
│
├─ data/
│ └─ portland_crime.csv
│
├─ visuals/
│ ├─ heatmaps.png
│ └─ peak_hours.png
│
└─ README.md

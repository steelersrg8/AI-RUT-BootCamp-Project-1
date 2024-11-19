# College Scorecard Dataset Analysis Project

## Project Overview
This project conducts a comprehensive analysis of the U.S. Department of Education's College Scorecard Dataset (1998-2024), focusing on earnings potential and gender distribution across institutions and fields of study.

## Research Questions and Findings
1. **Earnings by Institution**
   - Analysis of top 20 and bottom 20 universities by graduate median earnings (5 years post-graduation)

2. **Field of Study Analysis**
   - Comparison of highest and lowest earning fields
   - Popularity analysis with enrollment numbers

3. **Gender Distribution/Earnings Analysis**
   - Gender patterns within earnings data
   - Field of study gender distribution trends

4. **Institution Type Comparison**
   - Public vs. Private institution earnings analysis

## Technologies Used
- Python (version 3.9.6)
- Pandas for data manipulation and analysis
- Matplotlib for data visualization
- Git/GitHub for version control

## Project Structure
```
college-scorecard-analysis/
├── data/                    # Raw and processed dataset files
├── notebooks/              # Jupyter notebooks with analysis
│   ├── data_cleaning.ipynb     # Data preparation steps
│   ├── earnings_analysis.ipynb # Earnings analysis
│   └── gender_analysis.ipynb   # Gender distribution analysis
├── visualizations/         # Generated plots and figures
├── presentation/          # Presentation materials
└── README.md             # Project documentation
```

## Installation and Usage
1. Clone the repository
```bash
git clone [repository-url]
cd college-scorecard-analysis
```

2. Set up Python environment
```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. Install required packages
```bash
pip install -r requirements.txt
```

4. Run Jupyter notebooks
```bash
jupyter notebook
```

## Analysis Results
[Detailed findings with supporting visualizations to be added]

## Future Analysis Considerations
1. **Longitudinal Analysis**
   - Track changes in earnings patterns over the dataset's time span
   - Analyze the impact of economic events on graduate outcomes

2. **Geographic Analysis**
   - Regional variations in earnings and gender distribution
   - State-by-state comparison of public vs. private institutions

3. **Additional Factors**
   - Student debt correlation with field of study and earnings
   - Impact of institutional resources on graduate outcomes

4. **Methodology Extensions**
   - Implementation of machine learning models for outcome prediction
   - Development of interactive dashboards for data exploration

## Dataset License
The College Scorecard Dataset is provided by the U.S. Department of Education under a public domain license. This allows for free use, modification, and distribution of the data. For more information, visit: https://collegescorecard.ed.gov/data/documentation/

## Team Members and Roles
- William: Initial data preparation, GitHub setup, analysis
- Jill: Documentation, presentation preparation, analysis
- Shared: Data visualization and presentation delivery

## Contributing
This is a collaborative academic project. For questions or suggestions, please contact team members.
[Data Key](https://docs.google.com/spreadsheets/d/1qOUqh_U5ZSih58I9x1BguEX2FoaeCh1HoaEIgbVYcOU/edit?usp=sharing)

[Data Set](https://archive.org/details/most-recent-cohorts-field-of-study_202411)

[filtered_df_earnings_non_male](https://docs.google.com/spreadsheets/d/1UJlhLSv1_BwbkXTTaiu0-Pcme3UU4H_uf7d4ZLmxd3M/edit?usp=drive_link)

[filtered_df_earnings_male](https://docs.google.com/spreadsheets/d/1myPLsD_RZ0d0j9lohTkh5MWeCcj4nXUk14KopAihpg8/edit?usp=drive_link)

[filtered_df_earnings](https://docs.google.com/spreadsheets/d/1uac0fxP8igegvFTCmkjMWa_ujqArWoM7pOA6jsHV7A0/edit?usp=drive_link)

[final_df_earnings_generic_male_non_male](https://docs.google.com/spreadsheets/d/1hkS7fOC8esa7AQA-w5Hoa228HhUcZ7K5EIXFN52fX_4/edit?usp=drive_link)

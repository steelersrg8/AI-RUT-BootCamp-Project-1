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
![Top 20 Mean Earnings For Colleges](/Images/top20meanearnings.png "top20meanearnings")
Primary Focus: Schools with strong Health Sciences and Medical Education programs 
Goal: Training healthcare professionals in various medical fields (e.g., medicine, dentistry, nursing) and advancing medical research through STEM disciplines.
Mean earnings >$150K 5 years from graduation (adjusted)
![Bottom 20 Mean Earnings For Colleges](/Images/bottom20meanearnings.png "bottom20meanearnings")
Primary Focus: Vocational training in cosmetology, barbering, and beauty.
Goal: Equipping students with practical skills for the beauty industry, often reflecting regional and cultural influences.
Mean earnings <$15K 
5 years from graduation (adjusted)
![Top 20 5 Year Earnings](/Images/5YearMalesVsNonMalesTop20FieldOfStudy.png "5YearMalesVsNonMalesTop20FieldOfStudy")
Advanced Dentistry/Oral Sciences graduates earn the most of any field of study 
High Earnings Fields of Study analysis suggests that advanced degrees combined with specialized professional expertise can lead to better career outcomes
![Bottom 20 5 Year Earnings](/Images/5YearMalesVsNonMalesBottom20FieldOfStudy.png "5YearMalesVsNonMalesBottom20FieldOfStudy")
Cosmetology and Related Grooming graduates earn the least of any field of study 
Lowest Earning Fields involve hands-on, vocational training or associate degrees in areas like cosmetology, culinary arts, and healthcare support
![Top 20 Most Popular Field Of Study](/Images/output.png "output")
Most Popular Fields of study (by count) include social sciences and humanities; practical vocations such as criminal justice, accounting, and healthcare clinicians are also popular
Least popular fields included a large list with N=1 (therefore excluded)
![corelationbetween5yearearningsandcounttop20](/Images/corelationbetween5yearearningsandcounttop20.png "corelationbetween5yearearningsandcounttop20")
Highest Earning Fields in the dataset have relatively low numbers of student graduates (<30) with 3 notable exceptions - Medicine (156), Pharmacy (146) and Dentistry(64)
![malevsnonmale](/Images/malevsnonmale.png "malevsnonmale")
![malevsnonmalepie](/Images/malevsnonmalepie.png "malevsnonmalepie")

Despite nearly 50/50 gender distribution,  there is a significant earnings gap between male and female graduates
The gap is pronounced in some, such as the U of Pikeville, where the difference exceeds $100K
![5YearMalesVsNonMalesTop20](/Images/5YearMalesVsNonMalesTop20.png "5YearMalesVsNonMalesTop20")
A Significant Gender Gap Persists in the top earnings Fields…only 3 of the top earnings fields (Medicine, Operations Research and Computer Science) have closed the gender gap.
![5YearMalesVsNonMalesBottom20](/Images/5YearMalesVsNonMalesBottom20.png "5YearMalesVsNonMalesBottom20")
Male graduates earn more than Female graduates in the Bottom earning fields -  with 3 exceptions: Mind Body Therapies, Carpentry, and Drama
![tables.png](/Images/tables.png "tables")

**In the College Scorecard Dataset:**
- Public universities have the highest number of students, but they have the lowest mean 5-year earnings compared to private and foreign institutions. 
- Foreign institutions have the highest mean 5-year earnings, but they have the lowest number of students. 
- Private, non-profit institutions have a moderate number of students and a moderate mean 5-year earnings. 
- Private, for-profit institutions have a significant number of students, but their mean 5-year earnings are lower than private, non-profit institutions and foreign institutions.

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

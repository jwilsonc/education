# Education Project

> The Education Project seeks to understand if there is an underlying relationship between ACT scores, socioeconomic factors, and school type.

---

## Project Overview

The Education Project sought to identify which socioeconomic and educational variables are most strongly associated with ACT scores. The project combined data from the National Center for Education Statistics and EdGap to discern which factor was most predictive of ACT scores. The key finding was that the percentage of students on free or reduced lunch was the strongest predictor.

- **Objective:** The project seeks to determine which variables are most predictive of a change in average ACT score across multiple schools.
- **Domain:** Education
- **Key Techniques:** (e.g., Imputing Missing Values, Multiple Linear Regression, Scaling)

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** https://github.com/brian-fischer/DATA-5100/blob/main/EdGap_data.xlsx (edgap)
- https://www.dropbox.com/scl/fi/fkafjk8902sq8ptxh94r2/ccd_sch_029_1617_w_1a_11212017.csv?rlkey=gucrdz5f6e38bezz2y3yalxbw&dl=0 (school_information)
https://nces.ed.gov/ccd/pubschuniv.asp#:~:text=Flat%20and%20SAS%20File%0A(ZIP%204.4%20MB) (school characteristics)
- **Description:** Each dataset contains numerical and categorical variables for multiple schools during the 2016-2017 school year;
size of edgap dataset: (7986 rows, 7 columns); size of school_information dataset: (102183 rows, 65 columns); size of school_characteristics dataset: (100062 rows, 20 columns)
- **License:** (if applicable)

---

## Analysis

A Jupyter notebook was used to process the data. Each dataset was imported as its own respective Pandas dataframe, before being merged and cleaned into a single dataframe. Exploratory data analysis and statistical modeling were then performed on this clean dataset. The Jupyter notebook containing the code for this project can be found in the 'code' folder.
---

## Results

The results imply some degree of correlation between all of the variables and average ACT score. However, percentage of students on free or reduced-price lunch proved to be the most predictive variable, more so than any other numerical or categorical variable.
---

## Authors

- Your Name - [@jwilsonc](https://github.com/jwilsonc)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: pandas, scikitlearn, patsy, matplotlib
- Tutorials or papers referenced
- Inspiration or collaborators

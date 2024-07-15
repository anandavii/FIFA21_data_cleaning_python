# FIFA21 Dataset Cleaning Project

![Fifa2021Banner](./images/FIFA2021Banner.webp)

## Introduction

This repository documents the data cleaning process for the FIFA21 dataset. The objective was to prepare the dataset for analysis by addressing issues such as missing values, inconsistent formatting, and incorrect data types.

## Dataset Source and Overview

The raw dataset was sourced from Kaggle via web scraping from sofifa.com. It contains comprehensive information about football players, including player names, age, clubs, nationality, wages, positions, performance ratings, height & weight, etc. The initial dataset consisted of 18,979 rows and 77 columns.

## Objectives

The main objective of this data challenge was to improve skills, learn, and build a worthy portfolio project. Specific objectives included ensuring all columns have correct data types suitable for analysis and standardizing numerical formats for further calculations.

## Insights Drawn from Data Cleaning Process

### Data Quality Assessment

The data cleaning process identified several data quality issues, including missing values in columns such as 'Loan Date End' and 'Hits', inconsistent formats across different columns, and incorrect data types. Addressing these issues improved the overall quality and integrity of the dataset.

### Data Consistency and Integrity

By standardizing formats, correcting data types, and handling missing values appropriately, the cleaning process ensured enhanced consistency and integrity of the dataset. This is crucial for reliable analysis and decision-making based on the data.

### Enhanced Analysis Readiness

Specific cleaning operations, such as extracting contract details, standardizing player attributes like height and weight, and converting currency values, enhanced the dataset's readiness for detailed analysis. These steps facilitated deeper insights into player performance, contract dynamics, and other relevant factors.

## Tools Used

For the data cleaning project, the primary tools and libraries used were Python and Pandas. Python provided the framework for data manipulation and cleaning tasks, while Pandas facilitated efficient handling of datasets, including cleaning, transformation, and validation.

## Data Cleaning Process

The data cleaning process involved the following key steps:

1. **Data Understanding**: Thorough examination of the dataset structure and meaning of columns, including creating a data dictionary for reference.
   
2. **Data Exploration**: Conducted exploratory data analysis (EDA) to identify patterns, anomalies, and specific cleaning requirements.
   
3. **Handling Missing Values**: Addressed missing values in columns like 'Loan Date End' and 'Hits' based on contextual understanding and data analysis findings.
   
4. **Standardizing Formatting**: Applied transformations and normalization techniques to resolve inconsistent formatting issues in columns such as 'Height' and 'Weight'.
   
5. **Validation and Quality Checks**: Rigorous validation processes were implemented to ensure data accuracy and integrity post-cleaning.

For detailed information about each cleaning step, refer to the Jupyter notebooks provided in the repository.

## Output

The cleaned dataset resulted in 18,979 rows and 72 columns, ready for further analysis and modeling.

## Tableau Visualization

To provide a visual representation of the cleaned FIFA21 dataset, a Tableau dashboard has been created. This visualization offers insights into player statistics, performance, and other key metrics. You can view the Tableau visualization [here](https://public.tableau.com/views/FIFA2021Analysis/FIFA2021Dashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).
![Fifa2021Vizz](/images/Fifa2021Vizz.png)
## Conclusion

The FIFA21 dataset cleaning project provided a comprehensive end-to-end experience, from data cleaning to visualization. Utilizing Python and Pandas, the dataset was meticulously cleaned, addressing issues such as missing values, inconsistent formatting, and incorrect data types. The cleaned data was then used to create an interactive Tableau dashboard, offering detailed insights into player statistics and performance metrics. This project not only enhanced technical skills in data cleaning and manipulation but also demonstrated the value of combining data preparation with visualization for effective sports analytics.

<div class='tableauPlaceholder' id='viz1721080762341' style='position: relative'><noscript><a href='#'><img alt='FIFA 2021 Dashboard      ⚽️🏃‍ ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FI&#47;FIFA2021Analysis&#47;FIFA2021Dashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='FIFA2021Analysis&#47;FIFA2021Dashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;FI&#47;FIFA2021Analysis&#47;FIFA2021Dashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1721080762341');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1200px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1200px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
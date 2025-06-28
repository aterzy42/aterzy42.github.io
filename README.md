# Data Scientist

- [Technical Skills](#technical-skills)
- [Projects](#projects)
- [Education](#education)
- [Work Experience](#work-experience)

## Technical Skills: 
- **Programming Languages**: Python, SQL, R
- **Data Analysis & Manipulation**: Pandas, NumPy, Excel
- **Machine Learning**: Scikit-learn, Keras, Machine Learning Algorithms (e.g., Regression, Classification, Clustering, etc.)
- **Data Visualization & BI Tools**: Matplotlib, Seaborn, Power BI
- **Computer Vision**: OpenCV, Scikit-Image
- **Statistical Analysis**: A/B Testing, Hypothesis Testing, Statistical Modeling (e.g., Linear Regression, Bootstrap, etc.)
- **Version Control**: Git

## Projects
### FuzzyMerge – Smart Data Cleaning App
[Repo](https://github.com/aterzy42/FuzzyMerge)
[Demo](https://fuzzymerge.streamlit.app/)

FuzzyMerge is a no-code Streamlit app for cleaning and merging messy CSV/XLSX files. It guides users through a visual workflow to:

- Align mismatched columns across files  
- Detect and handle missing values and numeric outliers  
- Apply fuzzy matching to standardize inconsistent text entries  
- Remove duplicate rows  
- Export cleaned data with full change logs  

Built for any soul who regularly deals with inconsistent spreadsheets. Includes sample data for instant demo.
<img src="/assets/fuzzy.png" alt="Blah" width="400" height="332" />
<br>
### Market Returns Based on Economic Conditions Full Stack
[Repo](https://github.com/aterzy42/Stock_Screener)

Built a full-stack web application that analyzes historical stock index returns based on macroeconomic conditions. Financial data is sourced via scheduled ETL pipelines using Airflow from Yahoo Finance and Alpha Vantage, and stored in a PostgreSQL database. The frontend, developed in Streamlit with a FastAPI backend, allows users to filter by economic indicators (e.g., inflation, unemployment) and explore periods where those conditions were met. Users can visualize 3- and 5-year forward returns across major indices, along with interactive line charts showing index performance from selected starting points.

<img src="/assets/git_gif2.gif" alt="Blah" width="500" height="475" />
<img src="/assets/process.png" alt="Blah" width="400" height="332" />

<br>

### An Investigation of Distance-Based Statistical Methods in High Dimensions
[Repo](https://github.com/aterzy42/CurseofDimensionality)

Common statistical tools often become ineffective when dealing with high-dimensional data. This thesis examines the causes of these issues by exploring high-dimensional spaces. We present some counterintuitive mathematical and statistical results from a geometric view. These results are exploited to modify an existing classification method and introduce a new test statistic for the general distribution-free two-sample problem. Other applications are briefly considered.

<img src="/assets/simplex" alt="Blah" width="370" height="290" />

<br>

### Retention Analysis on Cookie Cats Mobile Game: A/B Test with Permutation and Bootstrap Tests
[Repo](https://github.com/aterzy42/Cookie_AB)

We are testing whether changing the first gate in a popular mobile game from level 30 to level 40 has a significant impact on user retention. To do this, we apply Permutation Tests to assess if the observed differences in retention rates are statistically significant, and Bootstrap to calculate confidence intervals for the retention differences. The goal is to understand whether the new feature has a meaningful impact on short-term and long-term user engagement.

<img src="/assets/cookiecat.png" alt="Blah1" width="450" height="250" />
<img src="/assets/bootstrap.png" alt="Blah1" width="425" height="210" />




<br>

### Predicting Clicks On a Real Estate Posting Using Poisson Regression
[Repo](https://github.com/aterzy42/Property_Click)

This project focuses on developing a predictive model to estimate user interactions with real estate listings posted on NoBroker, a popular online platform in India. The assignment, which was posted on StrataScratch, challenges participants to build a model that forecasts how likely users are to interact with various listings on the website. The task involves analyzing rent amount, location, and others factors  that influence interactions.

<img src="/assets/nobroker.png" alt="Blah1" width="477" height="245" />

<br>

### Using Spline Regression
[Repo](https://github.com/aterzy42/Spline)

Spline regression is a method used to model complex, nonlinear relationships between variables by fitting piecewise polynomial functions. It divides the data into segments and fits a low-degree polynomial to each segment, ensuring smooth transitions at the boundaries (called "knots"). This approach allows for flexibility in capturing non-linear trends while avoiding overfitting. The report and beamer presentation includes an implementation of spline regression in R, demonstrating its application for modeling such relationships.

<img src="/assets/spline" alt="Blah" width="300" height="150" />

<br>

### Should I Invest Streamlit Dashboard
[Repo](https://github.com/aterzy42/StockAnalysis)

This project leverages a Random Forest classifier to predict whether a stock will experience a relative price change greater than 1 compared to the S&P 500. The prediction model is deployed through an interactive Streamlit dashboard, where users can customize various valuation metrics to generate stock predictions. Additionally, the dashboard features a dedicated tab that allows users to select a stock by ticker and retrieve company descriptions, as well as data on institutional and insider ownership, which are scraped using BeautifulSoup. The project also includes an exploratory data analysis (EDA) notebook and the complete code for the dashboard implementation.

<img src="/assets/shoudiinvest.png" alt="Blah" width="400" height="250" />

<br>

### Obligatory Projects:

### Simple OCR
[Repo](https://github.com/aterzy42/DigitHighlighter)

This project uses several classical image processing techinques to extract the digits written on a notepad. A classifier is also trained on the MNIST dataset using Keras.

<img src="/assets/phone_number.png" alt="Blah" width = "370" height = "480"/>

<br>

### Spam Filter
[Repo](https://github.com/aterzy42/SpamFilter)

This project uses the UCI SMS Spam Collection dataset to build a model that classifies SMS messages as spam or not. It involves cleaning and transforming the text data through feature engineering (like removing stop words and extracting message length) and applying TF-IDF to highlight important words. Different machine learning models are trained to predict whether a message is spam or not. 

<img src="/assets/spam.png" alt="Blah" width = "300" height = "230"/>

<br>


### Titanic Prediction
[Repo](https://github.com/aterzy42/Titanic)

Can't have a portfolio without the Titanic project! This project is all about predicting survival rates for passengers aboard the Titanic using machine learning. The goal is to build a model that can determine whether a passenger survived or not, based on a set of features like age, sex, class, and fare.

<img src="/assets/titanic.png" alt="Blah" width="800" height="250" />



## Education						       		
- M.S. Applied Mathematics	| California State University Northridge (_August 2020_)	 			        		
- B.S. Mathematics | California State University Northridge (_May 2017_)

## Work Experience
**ANALYTICS MANAGER @ Spotter (_October 2022 - November 2024_)**
- As a Data Analyst supporting underwriting and portfolio analytics teams, estimated future cash flows for unconventional financial products offered to YouTube channels, leveraging retention and cohort analysis to improve forecast accuracy and drive decision-making for creator partnerships.

- Developed a forecasting model using time series techniques in Python, alongside extensive data cleaning and organization with SQL, to predict monetization rates for YouTube videos, reducing manual underwriting time by 50% and improving the precision of creator deal valuations.

- Collaborated with the sales team to create data-driven narratives under tight deadlines, pulling data from Redshift using SQL and organizing it in Excel pivot tables and charts to deliver ad hoc analyses that contributed to securing over $50,000,000 in contracts with global YouTube creators.

- Built and automated ETL-driven dashboards using multiple YouTube API data sources in Excel and Power BI, expediting underperforming deal reviews, enabling faster executive feedback, and saving 3 hours weekly through template creation.


**MACHINE LEARNING SPECIALIST – COMPUTER VISION @ Bluehalo (_September 2019 - October 2022_)**
- Applied computer vision and image processing techniques to satellite imagery for space situational awareness tasks in the aerospace and defense sector, working in an Agile environment with a security clearance.

- Created anomaly detection algorithms in Python to automate region proposal generation and designed a PyQT5-based GUI, reducing annotation time by 50% and speeding up the creation of high-quality training data for object detection models.

- Constructed a state estimation pipeline in OpenCV for post-detection target tracking, utilizing interpolation, centroid estimation, and symmetry detection, achieving low RMSE in velocity and position estimates as part of a successful proof of concept.

- Engineered advanced streak detection techniques to process and analyze large-scale space sensor data, improving object tracking precision and data processing efficiency.

- Regularly presented methodologies to stakeholders, simplifying complex technical concepts, identifying inefficiencies, and leveraging the latest research to drive strategic planning and project prioritization.



**TEACHING ASSOCIATE, MATHEMATICS @ California State University, Northridge (_August 2017 - May 2020_)**
- Delivered engaging lectures and recitations for precalculus and higher-level courses, improving student comprehension and engagement.
  
- Provided personalized tutoring and support during office hours, addressing individual student challenges and improving academic performance.
  
- Led a summer intensive on data science for incoming students, covering coding, statistics, and machine learning, enabling students to complete Kaggle challenges and strengthening their foundational skills for future coursework.

**RESEARCH SCHOLAR - MACHINE LEARNING @ Air Force Research Laboratory (_June 2019 - August 2019_)**
- Completed a summer internship at Kirtland Air Force Base, focusing on leveraging machine learning techniques to expedite high-power microwave simulation analysis and streamline design processes.

- Optimized multiple regression models to analyze simulation results, using random forest techniques to identify key factors, driving design improvements, and enhancing virtual prototyping, while templatizing and documenting code for future research.

- Produced advanced interactive 3D Matplotlib visualizations to transform complex datasets into clear, actionable insights, uncovering hidden patterns and trends that drove hypothesis development and informed critical research decisions.


  









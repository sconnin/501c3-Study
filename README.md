# 501c3 study for state of VT

The aim of this work is to create a cross-sector financial analysis of 501c3 organizations in Vermont based on FORM 990 returns. And to support assessment of leadership, employee structure, projects and contracts at a state level. Also included in the dataset are FORM 990EZ, FORM 990N, and Form 990PF. 

Organizing questions:

1. Can FORM 990 variables be used to predict financial measures (e.g., liability ratio, program expense ratio, viability ratio) within organizations and/or across sectors?
2. What proportion of not-for-profit leadership includes members of under-represented populations? Does the former vary by sector?
3. How can non-profits optimize their organizational structure and investments to minimize year-to-year financial risk?

Data collected for this work were obtained (via. web-scraping) from the Propublica's Nonprofit Explorer portal (https://projects.propublica.org/nonprofits/) and include the following categories: Arts, Culture & Humanities; Education; Environment and Animals, Health, International, Foreign Affairs; Public-Societal Benefit, Region Related.

An initial EDA for tax year 2019 is included in the file, 'EDA.pdf'.

Select data (csv) for each category are included in the folder '990.csv'.

At present, R code is included the following files:

1. Proj501c3_a: webscraping and storage
2. Proj501c_b: data processing and initial EDA


This project is ongoing and future work will focus on: 1) constructing a time-series of 990 returns for each organization, 2) modeling key financial metrics, and 3) text-analyses to identify patterns in leadership (e.g., gender), mission, and contracts.

Results of this work will be relevant to foundations, prospective donors, public agencies, and not-for-profit organizations.

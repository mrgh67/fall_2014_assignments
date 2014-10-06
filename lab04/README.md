## Exploratory Data Analysis
=============================

### Part 1: ([adapted from **Doing Data Science**, Cathy O'Neil and Rachel Schutt, Chapter 2: Statistical Inference, EDA, and Data Science Process](http://shop.oreilly.com/product/0636920028529.do))

1. Get the datasets:

   Write a python script to download datasets nyt1.csv...nyt31.csv from url endpoint: http://stat.columbia.edu/~rachel/datasets/ into your own local directory

   Each files represents a simulated day's worth of ads shown and clicks recorded on the **New York Times** home page in May 2012. Each row represents a single user. There are five columns: age, gender, number of impressions, number of clicks, and signed-in

2. For a single day of data:

  a. Create a new variable (column) in your dataframe that puts users into the following categories: ["<18", "18-24", "25-34", "35-44", "45-54", "55-64", "65+"]
    - hint use the "apply" method

  b. Plot the distributions of the number of impressions and click-through-rate (CTR = clicks/impressions) for these six age categories

  c. Define a new variable (column) to segment or categorize users based on their click behavior

  d. Make visual and quantitative comparisons across user segments/demographics (e.g., <18 year-old males vs. females or logged-in vs not)

  e. Create metrics tha summarize the data. For example: CTR, quantiles, mean, median, variance, min/max. Think about what you would like to track over time-- what will compress the data but still capture user behavior.

3. Now extend the analysis across days. Visualize some metrics and distributions over time. What are some good ways to show day-to-day trends?

#### 

### Part 2:



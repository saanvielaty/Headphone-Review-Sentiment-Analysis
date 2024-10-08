# Beats By Dre-Review-Sentiment-Analysis
This project analyzes Amazon reviews for 10 headphones from different companies in order to gain a better understanding of consumer sentiments.  By integratting the data set with Gemini AI, marketting and production enhancement suggestions for beats by dre headphones are uncoverred to obtain maximum consumer satisfaction.  

**Data Mining:** Found 10 headphones from different companies on amazon with substantial number of reviews, and copied the ASIN number.  Using Oxyl API, the data was scraped, and later downloaded into a JSON file.  This resulted in 10 seperate Excel files that totalled 1000 reviews.

**Data Processing:** Each file was loaded into a python dataframe, and organized into the following categories: review_id	product_id, title,	author, rating, content, timestamp, profile_id, is_verified, helpful_count, and product_attributes.  Each file was then converted and dowloaded into a csv file, and later merged into 1 csv file.  

**Data Cleaning:** Using python libraries NumPy and Pandas, the data was cleaned of missing/null values, duplicates, and outliers. The cleaned data can be accessed using this link: https://1drv.ms/x/s!AuyIJAferW5BkRazTW9I5fZL9Bh5?e=C8T36J

**Exploratory Data Analysis:** Used Python Pandas library to calculate the mean, median, mode, quantiles, variance, and standard deviation of rating and helpful count columns.

**Data Visualization:** Created a bar graph, wordcloud, and facetgrid using Python libraries seaborn, matplotlib,violin plot,and wordcloud to understand trends in the data.  

**Sentiment Analysis:** Grouped the reviews into postive, negative, and neutral sentiments using python libraries pandas and textblob.  Also calculated the percetage distribution for the sentiments.

**Evaluation using Gemini AI:** Integrated the data set with gemini Ai with a unique API key and phrased insightful prompts to gain information on marketting and production enhacements for Beats by Dre.



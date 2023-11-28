# shopping-behavior

The pupose of this project is to explore, transform, and analyze a set of data on shopping behaviors in the U.S.

Methods Used:
-inferential statistics
-Machine Learning
-Data Visualization
-Predictive modeling

Technologies
-Python
-Pandas, Jupyter

## Observations 

In explore we found that the state of California has the most amount of shoppers while Hawaii has the least. The winter season has the largest amount of purchases, snd the preferred payment form are credit cards. Standard shipping is preferred over expedited or 2-day shipping. People between the ages of 26-34 shop the most and we observe a bimodal distribution in Purchase Amount (USD), indicating that there may be two different groups in out dataset. Based off of the box plots the two groups may be those who use Promo codes and those that do not. I proceeded to clean my dataset by removing the "Frequency of Purchases" and "Customer ID" columns since 65% of the data was missing. Then transformed the "Review Rating" columns by splitting the groups into those who leave reviews and those who do not into 'Present' and 'Missing'. Creating a new .csv file in called "shopping-cleaned.csv" in my data/processed folder. In my analysis I found the top 3 clothing colors and the most popular clothing item for each season. By observing out p-value at 0.0 we would reject the null hypothesis and affirm promo-code users spend more than non-promo-code users.Based off of the output for both "High and Low" Review Groups, High rating reviews are more likely to leave a comment. Which makes sense because most people leave reviews because of either amazing or terrible experiences. On the high side most people love to share great experiences vs. terrible ones.


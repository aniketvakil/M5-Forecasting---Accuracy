# M5-Forecasting---Accuracy
Kaggle Project "M5 Forecasting - Accuracy

Link to the competition: https://www.kaggle.com/c/m5-forecasting-accuracy

This was a Kaggle Project held from March to June 30, 2020 by the University of Nicosia. This comeptition is aimed at used hierarchical sales data from Walmart, to forecast daily sales for the next 28 days. The data, covers stores in 3 US states (California, Texas, and Wisconsin) and includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events.

We have created rolling lags, as well as used a custom loss (same as described in the competition) to calculate the loss. Further we have used LightGBM as our algorithm to train the model and predict outputs of sales of each products at each stor for 28 days.

After running multiple models, with different parameters and algorithms, we have selected the 5 best models based on the public score and forked them together by multiplying them by a certain value and outputting it into a .csv file.

Our final, weighted model, ranked 339/5558 teams on the private leaderboard, which was considered for final prizes and rankings. We obtained a bronze medal in this competition.

Sources:
m5dark-magic-model-with-custom-loss-and-evaluation.ipynb forked from "M5 - Three shades of Dark: Darker magic" by Konstantin Yakovlev (https://www.kaggle.com/kyakovlev/m5-three-shades-of-dark-darker-magic)

Team DataSquad_STU:
1) Aniket Vakil
2) Mizanur Rahman
3) David Istrati
4) Mrinal Gosai

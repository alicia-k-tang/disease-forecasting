# disease-forecasting
**This README only offers a brief overview of the assignment. Further analysis containing forecasting graphs and literature review can be found in "Disease Forecasting Analysis" file of this repository.**

## Introduction 
For this assignment assignment, we were given [environmental data](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/) collected by US Federal
Government Agencies. The data included environmental variables surrounding changes in
temperature, precipitation, and vegetation. With this data, we were tasked with predicting the
number of Dengue fever each week for two cities— specifically for the cities of San Juan, Puerto
Rico and Iquitos, Peru. Exploring this problem provides incredibly valuable knowledge and
offers immense benefits to communities as a whole. In particular, having accurate predictions of
disease cases would result in lowering transmission rates and reducing the amount of fatalities.
Knowing the number of cases can aid with controlling outbreaks and reducing the
transmission of Dengue fever. This knowledge inherently leads to taking better preventive action
to mitigate the risk of being infected. In turn, this can increase the spread of awareness which
cotntributes to early detection and earlier treatment— heavily improving the chances of survival.
Preparing for the incoming number of cases creates more research incentive as well. This is
especially important due to the amount of time, money, and effort research requires. Better
research elicits more effective treatment and grants doctors a better understanding of how to
successfully treat their patients. The number of human lives that can be saved from this disease
by predicting the number of total cases make this an important problem to analyze.

Before beginning the modeling process, I had to convert both the San Juan and Iquitos
datasets into time series objects. For San Juan, I chose to only look at predicting 17 weeks since
the last full year that was given was 2007. For simplicity, I wanted to only predict the remaining
weeks after the last full year of data. Likewise for the Iquitos dataset, I decided to predict the
remaining weeks after the last full year of data in 2009. Essentially, these were two different time
frames that the problem required you to predict.

## Concluding Thoughts
I enjoyed participating in this competition because of how applicable this was in
real-world situations, especially since we are still currently suffering through a world pandemic.
If we had known about COVID-19 earlier and foreseen it, I can only imagine how much it would
have helped with preparation on how to handle the situation both government-wise and
community-wise. As always, I learned that there are so many different choices of forecasting
models, and that it is difficult to find the best fit. I was also shocked at how a basic regression
model could outperform the other more advanced models— this makes it important not to
dismiss any type of model and to consider all options when forecasting.

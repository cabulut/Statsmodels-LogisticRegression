# Statsmodels Logistic Regression on Medical Business Dataset


## Getting Started

Pandas, Numpy, Matplotlib and Statsmodels are essentials

## Dataset

Consists of one excel dataset with 5 sheets in it. Each sheet has primary key and they need to be merged before further analysis. Please also note that the whole data is not a real data.


## Summary

Based on analysis **22% of the inquiries and 43% of the bookings** have been completed. There is still scheduled bookings that can be completed and also inquiries that can be booked.

No country would be considered as outlier in terms of the conversion rate, yet the cancellation from **United Kingdom** is lower than other countries. **Marketing** team can be informed about this in order to locate their retargeting campaigns.

There is an increasing trend in the number of Inquiries between April and September. In contrast to Inquiries, Bookings reached to peak in October-November.

It is obvious that users who made inquiry complete the booking later. Between **April and October 2014** we can see that average CPI exceeds the average commission received. However, it should be also noted that there are **710** scheduled bookings and this is almost as high as completed bookings that are **762** right now.


When we look at the profits aggregated in **inquiry date** level it can be seen that in August and September 2014 commission received exceeded CPI so inquiries were more successful in these months. However as inquiries started to decrease after **September 2014** the profit by inquiry date also decreased along with it


In terms of the clinic countries and the treatments we can say that Thailand and Brasil are the most popular countries and Cancer treatment is the most common treatment to inquiry and book.


Inquiries and bookings(including scheduled bookings) have a trend to increase however it is still not very profitable thereby **Logistic Regression** would be a good method to implement here in order to predict the results of inquiries and bookings. However both **Pseudo R-square** of the models are not optimal. Based on **McFadden (1977)** the optimal value would be excellent fit 0.2 to 0.4


Based on the models we can at least state that Inquiries model would indicate a better fit than the Bookings model based on Pseudo R-square. In Bookings model only independent variable with a lower than 0.05 p-value is the **Cancer treatment** thereby it can be stated the users who made the bookings for Cancer treatment is tend to complete their bookings more than any other treatment.


By looking at **Inquiries** we can see a better model fit not for clinic countries but at least for procedures. It can be concluded that users who make inquries for Cancer Treatment and Hip Replacement are less likely to book compared to people who make inquiries in Teeth Whitening and Veneers.


Overall **Cancer Treatment** is the only treatment that has low p-value in both models. We can conclude that Cancer treatment inquries are less likely to be a booking, but once they are booked they are more likely to be completed.


It would be nice to have **how often users sign in, how much time they are spending and their reviews** in order to feed the logistic regression.Furthermore cost to retain (if applicable), post sale support cost, fixed burn-rate for operating expenses (rent, salaries, overhead) would be also nice to have to implement descriptive statistics and calculate KPIs


##### To do(s)
- apply also Scikit-Learn module
- evaluate the model with other metrics


###### Contact

[LinkedIn](https://www.linkedin.com/in/caner-bulut-48a0784a/)
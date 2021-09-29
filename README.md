# Module-14-Challenge
Module-14-Challenge Solutions
Module 14 Challenge Conclusions:

Conclusions about the performance of the baseline trading algorithm (SVC):

![Baseline](https://user-images.githubusercontent.com/85648561/135194911-6db6b6b2-2451-4967-96eb-360fd659a983.png)

I would say the Baseline Trading Algorithm does not perform as favorably as other possible trading algorithms potentially could. As one can see, there are clear advantages and disadvantages. Advantage: This trading algorithm has strategy returns that are much less volatile than actual returns. Also, there are higher strategic returns than actual returns from mid 2015 - early 2016. Disadvantages: the strategy returns are in general much lower than the actual returns.

Tuned Baseline Trading Algorithm:

What impact resulted from increasing or decreasing the training window? 

To adjust the size of the training dataset, I used a different DateOffset value. Instead of the previous three months value, I changed it here to six months.
The impact made the training/testing have a little less data, which seems to have made the model prediction more stable.

What impact resulted from increasing or decreasing either or both of the SMA windows?
From increasing the SMA short value to 50, and the SMA long value to 200, this made the SMA slow and SMA fast values both decrease and have much for “sell” signals than the prior baseline SMA values.

New Model Conclusions:

Did this new model perform better or worse than the provided baseline model? 

I would say that the Baseline model performed better. Both models Strategy returns seem to somewhat replicate their corresponding "Actual Returns", yet to a much lower degree. The baseline model does have better returns than the new model. 

Final conclusions and analysis

For my analysis I used two different machine learning models to compare: SVC and Random Forest. SVC performs better in this case then Random Forest. However, I would continue to look for more machine learning models to do even better than SVC, for the reason that the Strategy returns were substanially lower than the Actual returns. 

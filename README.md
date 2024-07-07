# iis_customer_churn
Infinite Investment Systems Customer Churn Model

### Context
As a person pursuing the field of data analytics (not science), I don't have much experience building machine learning model, so I took this opportunity to further hone my skills. I learned a lot about tree-based algorithms and mitigating overfitting, which are common issues faced in this field. Overall, I thoroughly enjoyed it!

### Challenges Faced
My biggest technical challenge was determining the presence of overfitting and how I used a variety of measures to determine that it was or wasn’t overfitting and give me more confidence that my model was just very accurate. To begin with, after dropping unnecessary columns, imputing missing values, one-hot encoding categorical values, I got a 98% F1-score using a decision tree classifier, which made me very suspicious. Even before training the data, I’ve already used methods to prevent overfitting, like removing nodes with little to no predictive power, getting rid of irrelevant features and balancing the dataset.
But there are other ways for us to further check if the model is overfitting. Namely, cross validation, ensemble methods and hyper parameter tuning and pruning.

### What I learned
Although there is no way to figure out with 100% certainty of overfitting, I learned that there are a variety of sophisticated techniques used to give you almost near-certainty if your model is overfitting or not. And in this case, I can now say with confidence that my model is accurate. And in terms of implementing this in the real world, overfitting is such a common issue, especially given the abundance of data companies now have, I have a variety of skillsets, as mentioned above, to put into my workflow to mitigate the risk of overfitting.

### Resources I used
- https://towardsdatascience.com/3-techniques-to-avoid-overfitting-of-decision-trees-1e7d3d985a09
- https://towardsdatascience.com/churn-prediction-with-machine-learning-ca955d52bd8c

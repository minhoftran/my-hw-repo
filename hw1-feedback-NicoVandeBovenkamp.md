### ***Project 1 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this first assignment! Your answers are clear and well worded. You are definitely picking up on some of the key points and topics that we talk about in the class. Also, I truly appreciate the honest, light-humored answers. Seriously, amazing. Slack me if you have any questions!


**Some Notes**

* *Q.1* You are right that exploratory analysis serves to explore the *quality* of your data (super solid, and key, point you make there), but it also serves to investigate the issues in your data including: missing values, skewed distributions, format errors, etc.
* *Q.2a* Hoping, hah, nice. You are *assuming* that the data is representative, but given we will be using some kind of linear model we are also assuming that the data is approximately normally distributed.
* ***Q.2b and Plotting:*** Awesome, yes! You could plot a histogram. Also, plotting tip for next homework: try using [Seaborn](https://elitedatascience.com/python-seaborn-tutorial). It's a good bit easier to use than matplotlib, and it has some very handy built-in methods!
* *Q.3a/b* You are right that it could negatively impact our analysis, and more. Also, yes, an outlier could indicate something about the underlying distribution. However, it could also be due to some random chance/error/anomaly. In other words, maybe it's out of character for a student to have a GRE of 2... So, we want to deal with them somehow because it will impact our analysis, inference, and subsequently skew our models. Regarding handling them, check out the blog post below!
* *Q.4a/b* Co-linearity isn't quite different variables measuring the *same/similar* information. It is effectively a quality of two covariates to be linearly related. For example, maybe $sales = 2*(TV Ads) + 3*(Digital Ads)$. To estimate how linear a relationship is, you can use correlation. Thus, a correlation matrix! In pandas:

```python
data.corr()
```

**Something to think about**

We touch on this a bit in class, but think about how you can apply statistical tests to your data. There are many handy tests to determine difference of means (very useful), tests to determine assumptions of an underlying distribution, etc. For example, there are specific tests which will estimate how close a given distribution is to a normal distribution.

Also, check out this KDNuggets post for [outlier analysis](https://www.kdnuggets.com/2017/02/removing-outliers-standard-deviation-python.html) in Python!

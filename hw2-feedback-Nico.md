### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this homework! As with the last one, you clearly grasp these concepts well, and you are getting more comfortable with Pandas/Python. As we proceed into the modeling section, try experimenting with taking advantage of Python. Maybe you develop your own methods for dealing with pre-processing, or maybe your own class! Also, let me know if you have any questions on modeling, as this is the next **big** section in our journey!

**Some Notes**

* *Q.10:* I appreciate the "I wouldn't" over a "No." hah
* Regarding your analysis plan, you should probably include what models/modeling techniques you think you should use. Considering we haven't gotten into it yet, this is more than okay to not include. However, typically when you write out your analysis plan, you include data cleaning, data manipulation, some analysis, and then modeling techniques to find, in this case, the relationship between Admission and Prestige!

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html

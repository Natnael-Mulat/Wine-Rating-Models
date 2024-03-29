# Wine Ratings Model
Machine Learning Wine-rating Regression model
---------------------------------------------
Unprecedented  data  analysis  emerges  in  the  era  of  bigdata.  Various forms of online reviews are available throughdata  mining.   These  massive  online  databases  of  reviewsexpose information about reviewer’s criteria based on somefeatures of a product.  Industry professionals are interestedin discovering these criteria,  which can be used to predictthe performance of their products.However,  traditional  analysis  of  online  reviews  focuseson  building  recommending  systems  instead  of  predictingthe rating.  For example, there is an hotel recommendationalgorithm  that  imitates  a  user  that  favors  reviews  writtenwith the same trip intent and from people of similar back-ground (nationality) and with similar preferences for hotelaspect (Levi and Mokryn 2012).Although   similar   to   recommending   systems,   ratingprediction  using  machine  learning  techniques  is  an  areanot actively researched,  except for a few on bonds rating.For  example,  optimal  neural  network  structures  are  usedto predict the risk of some bonds, which affects they creditrating(Utans and Moody 1991).   However,  less researchesare  available  when  it  comes  to  predicting  the  rating  of  aconsumer product using polynomial regression technique
We used the dataset titled ”Wine Quality”, which is publicavailable  for  research  (Cortez  et  al.  2009).    The  datasetconsists  of  two  sub-datasets  created  using  red  and  whitewine   samples   of   the   Portuguese   ”Vinho   Verde”   wine.Our  dataset  contains  1599  samples  of  red  wine  and  4898samples of white wine.   The inputs are features of a winefrom objective tests (e.g.  volatile acidity, alcohol, and PHvalues), while the output is a score of sensory review, takenfrom  the  median  of  at  least  3  evaluations  made  by  wineexperts.   Each  expert  graded  the  wine  quality  between  0(very bad) and 10 (very excellent). There is no missing datain our datasets.
This file contains linear regression model with hyper-parameter tuning with test-train split. We used polynomial regression techniques to predict quality rating of the Portuguese ”Vinho Verde” winebased  on  physio-chemical  features. 
We  tuned  regression models  ranging  from  degree  of  1  to  degrees  of  4  with  either L1 (LASSO) or L2 (RIDGE) regularization based on ourtraining data.  It turns out that polynomial regression models with a degree of 2 gave the 
best prediction based on our testing data. Degree 2 model using L2 regularization performs slightly better according to the adjusted R2 metrics than its L1 counterpart. Our  results  show  that,  the  model  is able to exactly predict 44%
of the true quality ratings. In addition, we also found out that the added features of the polynomial  model  are  important  for  the  prediction  as  the R2 and adjusted R2 are  very  similar,  0.315  and  0.312  respectively. That also means 
that, 31% of the variation in the quality rat-ings of wine is explained by the features our model included.


This file contains linear regression model with hyper-parameter tuning with test-train split. We used polynomial regression techniques to predict quality rating of the Portuguese ”Vinho Verde” winebased  on  physio-chemical  features. 
We  tuned  regression models  ranging  from  degree  of  1  to  degrees  of  4  with  either L1 (LASSO) or L2 (RIDGE) regularization based on ourtraining data.  It turns out that polynomial regression models with a degree of 2 gave the 
best prediction based on our testing data. Degree 2 model using L2 regularization performs slightly better according to the adjusted R2 metrics than its L1 counterpart. Our  results  show  that,  the  model  is able to exactly predict 44%
of the true quality ratings. In addition, we also found out that the added features of the polynomial  model  are  important  for  the  prediction  as  the R2 and adjusted R2 are  very  similar,  0.315  and  0.312  respectively. That also means 
that, 31% of the variation in the quality rat-ings of wine is explained by the features our model included.

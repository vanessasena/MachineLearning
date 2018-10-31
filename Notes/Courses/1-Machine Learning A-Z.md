# Machine Learning A-Z™: Hands-On Python & R In Data Science

ML is the future.
Tones of data is being produced.

![ML is the future](https://github.com/vanessasena/MachineLearning/raw/master/images/MLisfuture.png "ML is the future")

##### Basic models of machine learning
* Regression - anything to predict a real value
* Classification - to predict the category, like doing some customer segmentations
* Clustering

##### Data preprocessing
* In any machine or any model we are going to use some independent variables to predict a dependent variable.
* Categorical data
* Dummy encoding

### Part 2 Regression

* Regression models (both linear and non-linear) are used for predicting a real value, like salary for example. If your independent variable is time, then you are forecasting future values, otherwise your model is predicting present but unknown values. Regression technique vary from Linear Regression to SVR and Random Forests Regression.

#### Simple Linear Regression

<img src="https://latex.codecogs.com/gif.latex?y&space;=&space;b_{0}&space;&plus;&space;b_{1}*&space;x_{1}" title="y = b_{0} + b_{1}* x_{1}" />

* <img src="https://latex.codecogs.com/gif.latex?y" title="y" /> = Dependent variable (DV)
* <img src="https://latex.codecogs.com/gif.latex?x" title="x" /> = Independent variable (IV). In Simple Linear regression there is only one IV.
* <img src="https://latex.codecogs.com/gif.latex?b_{1}" title="b_{1}" /> = Coefficient
* <img src="https://latex.codecogs.com/gif.latex?b_{0}" title="b_{0}" /> = Constant. The point where the line crosses the vertical axis.

**Ordinary Least Squares**
![Ordinary Least Squares](https://github.com/vanessasena/MachineLearning/raw/master/images/OrdinaryLeastSquares.png "Ordinary Least Squares")

#### Multiple Linear Regression

<img src="https://latex.codecogs.com/gif.latex?y&space;=&space;b_{0}&space;&plus;&space;b_{1}*&space;x_{1}&plus;&space;b_{2}*&space;x_{2}&plus;...&plus;&space;b_{n}*&space;x_{n}" title="y = b_{0} + b_{1}* x_{1}" />

**Assumptions of a linear regression**
* Linearity - the regression model is linear in parameters
* Homoscedasticity -  if all random variables in the sequence or vector have the same finite variance. This is also known as homogeneity of variance. 
* Multivariate normality
* Independence of errors
* Lack of multicollinearity

**Categorical Variables**
* In linear regression, create a dummy variable for each categorical variable
* You should always omit one dummy variable

[Building a model - Step by step](https://github.com/vanessasena/MachineLearning/blob/master/Udemy%20-%20Machine%20Learning%20A-Z/Machine%20Learning%20A-Z%20Template%20Folder/Part%202%20-%20Regression/Section%205%20-%20Multiple%20Linear%20Regression/Step-by-step-Blueprints-For-Building-Models.pdf)

---
##### Movies
* iRobot
* Ex Machina

##### Links
* [Ray Kurzweil predictions](https://singularityhub.com/2015/01/26/ray-kurzweils-mind-boggling-predictions-for-the-next-25-years/#sm.0000grmttd178hfr9xcq7kza4ucn0)

##### Videos
* [Jeff Hawkins - Lessons From The Neocortex For AI - Numenta](https://www.youtube.com/watch?v=uOA392B82qs)

##### Podcast
* [Hadelin de Ponteves, Machine Learning Expert and Entrepreneur](https://www.superdatascience.com/sds-002-machine-learning-recommender-systems-and-the-future-of-data-with-hadelin-de-ponteves/)
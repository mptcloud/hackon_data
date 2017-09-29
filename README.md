## Synopsis

This is the project repository for our 2017 HackOn(Data) hackathon project selected for the final presentation. The team members were: Hari, Felipe, and Con. We used the Amazon reviews and Q/A data available [here](http://jmcauley.ucsd.edu/data/amazon/). 

## Our approach

We wanted to predict the (category-wise) sales ranking of a product using all the available data at our disposal, except the image features. Taken as a supervised problem, we used a classification scheme via XGBoost to predict the most likely ranges of sales ranks, as opposed to predicting the sales ranking directly (owing to our relative lack of computing power to perform pairwise comparisons of all the products in a certain category).

## For more information

Our work on the project is summarized in the 'Slides.pdf' file (converted from .ppt), our final presentation slides.

## For the future?

* Look at customer satisfaction on the product review discussion boards using ideas from Liu, Bian, and Agichtein's paper.
* Helpfulness analysis of reviews.
* Incorporate product features (and comparison) via images into prediction model. 

## Contributors

* Con Healy
* Felipe Perez
* Hari Ravindran


# Predicting diamond prices with machine learning-kaggle competition

![Ironhack logo](https://www.fundacionuniversia.net/wp-content/uploads/2017/09/ironhack_logo.jpg)

This project is developed at the scope of Ironhack's Data Analytics Full-time Bootcamp.



## Resume
![Ranking ](src/ranking.jpg)

The aim of this project is to predict as best as possible the price of a dataset by means of machine learning (ML) models. 
The competition is released at https://www.kaggle.com/c/diamonds-datamad0820/overview though it is just a private one.

The evaluation metric chosen for this competition is the RMSE (Root Mean Squared Error):

https://en.wikipedia.org/wiki/Root-mean-square_deviation

In this website, two .cvs files are attached:
--> The one containing the dataset for training the ML model. Its columns are:
    id: only for test & sample submission files, id for prediction sample identification
    price: price in USD
    carat: weight of the diamond
    cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
    color: diamond colour, from J (worst) to D (best)
    clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
    x: length in mm
    y: width in mm
    z: depth in mm
    depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
    table: width of top of diamond relative to widest point (43--95)
--> The one containing the dataset were the model must be applied in order to predict price. Its columns are the same as the previous one, except for the price.



## Structure

1) README.txt: As a resume for the content of the project an its development

2) src: This folder contains every model carried out. These are .ipynb files.
The 4 best fitting models are numbers in their namefile (01,02,03 and 04).
The other ones, are just tests that did not come to a submission to kaggle.




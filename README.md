# Mini-Project-3

#

Tobias Carlsen - cph-tc183@cphbusiness.dk

Christian Kortsen - cph-cc283@cphbusiness.dk

Daniel Trelborg - cph-dh216@cphbusiness.dk

Simone Toft Hansen - cph-sh575@cphbusiness.dk

In the Mini Project 3, we had to explore some data about houses, and then we had to train some models using different Regressions.
We started off by reading the Data we recieved from the Teacher into our Program. Then we cleaned it, by dropping some columns, after chekcing Correlations. 
We checked that there was no null data, and we converted Square feet into Square Meters, to make it more relevant for our use.
After that we exlpored the data with different graphs, we used a Histogram, a heatmap, a box plot and more. We also plottet some of the houses into a real map to show where the houses were located more visually.
we then concluded that the biggest correletion between price and anything else was with sqm_living. we therefore trained a model using linear regression between thoose two
we then tried with more attributes and trained a model with multiple linear regression, we used sqm_living, bedrooms, bathrooms and grade.
then we tried using a polynominal regression between price and sqm_living.

In the end we concluded that the polynominal regression gave os the best R2 score

# Link to NBViewer to see our notebook:
https://nbviewer.org/github/Toebzy/Mini-Project-3/blob/main/Mp3/mp3.ipynb

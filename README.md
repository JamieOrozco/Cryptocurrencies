# Cryptocurrencies

## Overview of Project
This is an analysis for your clients who are preparing to get into the cryptocurrency market.

Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

## Deliverable 1: Preprocessing the Data for PCA

Removed columns and rows and then created a new dataframe after preprocessing. 

<img width="279" alt="image" src="https://user-images.githubusercontent.com/95591222/163689979-a374cad9-7381-42c2-9ae6-98aadc3cdd7c.png">


## Deliverable 2: Reducing Data Dimensions Using PCA

Applied the Principal Component Analysis (PCA) algorithm, reduced the dimensions of the X DataFrame to three principal components and placed these dimensions in a new DataFrame.

<img width="313" alt="image" src="https://user-images.githubusercontent.com/95591222/163690015-1771d314-8533-4d4d-aa78-3503e199defc.png">

## Deliverable 3: Clustering Cryptocurrencies Using K-means

Created an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

<img width="290" alt="image" src="https://user-images.githubusercontent.com/95591222/163690030-fa282663-d37b-449d-8b90-26c479f5783c.png">
<img width="448" alt="image" src="https://user-images.githubusercontent.com/95591222/163690077-4d78742e-87b8-4a29-a5bc-8931d706b2db.png">


## Deliverable 4: Visualizing Cryptocurrencies Results Summary

Created a scatter plots with Plotly Express and hvplot to visualize the distinct groups that correspond to the three principal components created in Deliverable 2. Created a table with all the currently tradable cryptocurrencies using the hvplot.table() function. A scatter plot is created using hvplot.scatter, to present the clustered data about cryptocurrencies having x="TotalCoinsMined" and y="TotalCoinSupply" to contrast the number of available coins versus the total number of mined coins.

<img width="535" alt="image" src="https://user-images.githubusercontent.com/95591222/163690131-7e4aa787-f074-4d6c-b700-896848d4a9cd.png">


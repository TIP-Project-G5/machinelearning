DESCRIPTION:
Python Jupyter notebook with demonstration/test machine learning for flood prediction using Chennai test data, 'area6_depot64.csv'.

The test notebook:
1) uploads the data and processes for prediction.
2) Uses Prophet to forecast the predictors 7 days ahead from the end of the data.
3) Appends the forecast data to the end of the historical data.
4) Uses DBSCAN clustering algorithm to detect anomalies in the data.
5) Days with anomalies are identified as flood events. 

Any days in the forecast period will also be identified as flood events if anomalous.

Note: This is a test/demonstration file, which has been successfully tested based on knowledge of previous flood events at the specific depot (Area 6, Depot 64). Address: "Kalidass St,Jeyaram Nagar, Kolathur, Ch-99" in Chennai. 

The 'area6_depot64.csv' has also been uploaded for confirmation of testing.

Code may need further testing for other depots for optimising hyperparameters in DBSCAN.

Visualizations in the notebook are purely for testing purposes and will be removed before deploying.

Code will be further adapted to the specific needs of the project as other dependent aspects of the project are completed, and finally converted into a .py file.

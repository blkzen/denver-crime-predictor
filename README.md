## Denver Crime Prediction
Using up-to-date data of crimes in Denver , I will create models that predict future crime.

**Process: O.S.E.M.N.**

### [O]btain:
I used an updated Kaggle dataset from Paul Mooney, Peijen Lin, and Timo Bozsolik. The dataset contains a list of all crimes in Denver dating back several years. 

Each entry includes type of crime, address, coordiantes, crime code, incident time, etc.

The dataset can be accesed here: https://www.kaggle.com/paultimothymooney/denver-crime-data?select=crime.csv

### [S]crub:
After importing the appropriate libraries and data, I removed unnecessary columns and reassigned datatypes such as datetime for the dataset.

### [E]xplore:
The dataset was sorted to only include data from this year. A heatmap over an OpenEarth map was created. The top crimes in Denver for the year of 2020 were all vehicular crimes.

![The Heatmap of Crime](https://media.giphy.com/media/j32Xn0BdIzkLx1mvb4/giphy.gif)

### [M]odel:
I predicted crimes based off of 2020 crime data using several models and boosters. That includes K-Nearest Neighbor, Random Forest, Gradient Boost, XGBoost, and GridSearchCV. The highest yielding accuracy, precision, recall, and f-1 score came from KNN(K-Nearest Neighbor).

![Report with Class](https://i.ibb.co/jWtFXgW/Flatiron-Capstone-KNN-class-rep.png)

### i[N]terpret:
Using the insight and KNN model, we can see where crimes are happening and predict where an incident of crime will occur in Denver. This insight allows for the Denver government to better allocate resources to areas with higher likelihoods for crime to occur.
The K-Nearest Neighbor model yielded the highest overall results.

## Conclusion
Using our dataset, the OSEMN process, machine learning, and visualization, geospatially savvy models were generated. With this information, opportunity arises. The analysis and predictive models within this project support the initiative of lowering crime in Denver. The best part is that this project's method of crime analysis and prediction can be used to minimze crime in other cities.

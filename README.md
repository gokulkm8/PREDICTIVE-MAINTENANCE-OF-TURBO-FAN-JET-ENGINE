# PREDICTIVE-MAINTENANCE-OF-TURBO-FAN-JET-ENGINE

### DESCRIPTION

Prognostics and health management is an important topic in industry for predicting state of assets to avoid downtime and failures. This data set includes Run-to-Failure simulated data from turbo fan jet engines.

Engine degradation simulation was carried out using C-MAPSS to simulate different combinations of operational conditions and fault modes. Records several sensor channels to characterize fault evolution

### EXPERIMENTAL SCENARIO

Data sets consists of multiple multivariate time series. Each data set is further divided into training and test subsets. Each time series is from a different engine i.e., the data can be considered to be from a fleet of engines of the same type. Each engine starts with different degrees of initial wear and manufacturing variation which is unknown to the user. This wear and variation is considered normal, i.e., it is not considered a fault condition. There are three operational settings that have a substantial effect on engine performance. These settings are also included in the data. The data is contaminated with sensor noise.

The engine is operating normally at the start of each time series, and develops a fault at some point during the series. In the training set, the fault grows in magnitude until system failure. In the test set, the time series ends some time prior to system failure. The objective of the competition is to predict the number of remaining operational cycles before failure in the test set, i.e., the number of operational cycles after the last cycle that the engine will continue to operate. Also provided a vector of true Remaining Useful Life (RUL) values for the test data.

Each row is a snapshot of data taken during a single operational cycle, each column is a different variable. The columns correspond to:
1) unit number<br>
2) time, in cycles<br>
3) operational setting 1<br>
4) operational setting 2<br>
5) operational setting 3<br>
6) sensor measurement 1<br>
7) sensor measurement 2<br>
…<br>
28) sensor measurement 23

### OBJECTIVE

This machine learning project will be directed to provide a framework for predicting the aircraft’s Remaining Useful Life (RUL) based on the entire life cycle data in order to provide the necessary maintenance behavior.

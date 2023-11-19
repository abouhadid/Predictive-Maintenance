# Predictive-Maintenance

-------------------------------------------------
Predictive Maintenance methods are employed to evaluate the status of equipment, enabling proactive maintenance or addressing potential failures before they occur. This proves highly advantageous in minimizing the costs associated with equipment downtime.

In this project, I construct an LSTM network to forecast the remaining useful life (RUL) or time to failure of aircraft engines. Using simulated aircraft sensor data, the network predicts the future occurrence of engine failures, facilitating proactive maintenance planning. 

This problem is further divided into two closely related questions, each addressed by distinct machine learning models:
1. **Binary classification**: Determining whether the engine is likely to fail within the next N cycles.
2. **Regression models**: Estimating the remaining number of cycles an in-service engine will endure before failure.
3. 
----------------------------------------------------

**DATA**:
The dataset comprises multiple multivariate time series, with each time series representing a distinct engine. Essentially, the data can be viewed as originating from a fleet of engines of the same type.
At the onset of each time series, the engine operates under normal conditions but develops a fault at some point during the series. In the training set, the fault intensifies over time until system failure. Conversely, in the test set, the time series concludes some time before system failure.
The training set encompasses operational data from 100 different engines, featuring varying run lengths ranging from a minimum of 128 cycles to a maximum of 356 cycles. Similarly, the testing set includes operational data from a distinct set of 100 engines, entirely different from those in the training dataset.

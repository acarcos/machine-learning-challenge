## Reporting

The machine learning models to compare were Decision Trees, Random Forest and Neural Networks. The database and the training features were the same. The features were selected according to measurements in luminosity and period since it is known that these parameters help to find exoplanets. The splitting data method used was the same for all models.

In general, despite Random Forest is a model based on Decision Trees, it did not predicted better compare to Decision Trees. The evaluation in both models were similar. Also, the models were not very good at predicting exoplanets, the accuracy was a bit low (80%). To consider a good predicting model, the accuracy should be near the 90%. 

For Neural Networks, the accuracy was similar, around 80%. Some tests were done changing the number of neurons in the hidden layer and epochs. These changes did not make the model improve, sometimes it reached 81% of accuracy, but it is not something significant to make better predictions.

A way to improve the models is to use methods to analize the features that have more impact in the prediction model. Sometimes, to know the theory behind the data is not enough to select the best features. To find these features, methods like Principal Component Analysys (PCA), Random Forest, Extra Trees, which can be found on sklearn library, could help to analize all the features in the database and help to choose the best ones to improve the predictions. 

In the case of Neural Networks, the method also could be improve by adding more layers to the model. In some cases, this is not the best option since this method is complex and too good that could lead to an overfitting model (which is like the network memorizing the data). But, other parameters could change too, such as the optimizer, the activation function, epochs or adding noisy data.

Finally, it should be considered that in some predicting models, the best way to find a better accuracy is by testing different options and have an idea what is happening behind the scenes to make those changes. There is not a "perfect" method. Most of the time it depends on your data and find out which method could work best. 

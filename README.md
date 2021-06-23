# ML_End_to_End_project_forestCover
Full stack ML project with end to end pipeline. 

Problem Statement													
To build a classification methodology to predict the type of forest cover based on the given training data. 													

KNN 	kneed import KneeLocator
Models	XGBoost and Naïve Bayes with Var Smoothing with HyperParameter tuming trained for each cluster and best model with best parameters are choosen for each cluster 
	
	
	
	
	
	Feature Engineering
Scaling	Standard Scaler
Encoding	data['target'].map({target1: 0, target2: 1…..})
handle ImbalanceDataset	"sample = SMOTE()
sample.fit_resample(X, y)"
	
	
	Training Model Stack
Kmeans	Cluster the data
Models	Train each group of models for each cluster and save the best performing model for each cluster
	
	Prediction Model Stack
Kmeans	Cluster the data
Model	Use the respective best saved model for each cluster to predict

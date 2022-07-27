# CreditRisk
Overview of Project
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

Deliverables:
This new assignment consists of three technical analysis deliverables and a written report.

Deliverable 1: Use Resampling Models to Predict Credit Risk
Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Deliverable 4: A Written Report on the Credit Risk Analysis README.md


RESULTS:

Smooteenn:
![smoteenn](https://user-images.githubusercontent.com/99819387/181139465-65069ec7-e9f8-4416-9547-c5b193caf48c.png)

Smote:
![smote](https://user-images.githubusercontent.com/99819387/181139500-851d0403-6aef-4d18-8981-25b780a4f462.png)

random oversampling:
![randomoversample](https://user-images.githubusercontent.com/99819387/181139561-a0585499-f35d-45bc-855a-924e6cc37161.png)

cluster:
![clustercentroids](https://user-images.githubusercontent.com/99819387/181139599-67e64a46-653a-425e-ae84-c49c73b45e9e.png)

easy esemble:
![easyensemble](https://user-images.githubusercontent.com/99819387/181139644-62e651f5-7719-41cf-9cf7-96f5dd28b1ec.png)

balnced:
![balancedrandom](https://user-images.githubusercontent.com/99819387/181139687-09ae8c13-0f6c-43da-a137-365da10a6669.png)

SUMMARY
For all models, using EasyEnsembleClassifier is the most effective. it gives the highest Score for all Risk loans. The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing EasyEnsembleClassifier will perform a High-Risk loan precision as a great value for the overall analysis.




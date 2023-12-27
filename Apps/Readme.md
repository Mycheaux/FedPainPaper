This folder contains the apps which can be run in testbed dierctly. On the other hand if one is willing to run the same feature cloud apps across multiple device the link of the same and instructions for those are given below.

To Run Feature cloud apps you would requier a featurecloud account, find the apps in appstore of feature cloud :  . After this you can follow the following video to run the apps : 
A. Simple Beta sharing Linear Regression (low communication cost) : 
B. Logistic regression :
C. Random Forest regression : 

To Run the apps in testbed follow the following instructions:
1. Clone this repo,
2. go to peritcular app's folder eg. FedPainPaper/Apps/Logistic_Regression , add your train and test files of each client in Apps/Logistic_Regression/app/data/client_i
3. you should have docker and python installed, now install featurecloud using 'pip install featurecloud'
4. then while inside the app folder do 'featurecloud controller start'this starts the docker
5. then do 'featurecloud app build .', this build the docker image
6. go to featurecloud.ai > for developer > test
7. chose the appname, right number of client and their path and start the app

   

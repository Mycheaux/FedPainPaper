This folder contains the apps which can be run in the testbed directly. On the other hand, if one is willing to run the same feature cloud apps across multiple devices the link of the same and instructions for those are given below.

To Run Feature Cloud apps, you would require a feature cloud account; find the apps in the app store of Feature Cloud: After this, you can follow the following video to run the apps : [https://featurecloud.ai/researchers](url)
A. Simple Beta sharing Linear Regression (low communication cost) : 
B. Logistic regression : [https://featurecloud.ai/app/logistic-regression](url)
C. Random Forest regression : [https://featurecloud.ai/app/random-forest](url)

To Run the apps in the testbed, follow the following instructions:
1. Clone this repo,
2. go to a particular app's folder e.g. FedPainPaper/Apps/Logistic_Regression, and add your train and test files of each client in Apps/Logistic_Regression/app/data/client_i
3. you should have docker and python installed now install feature cloud using 'pip install feature cloud'
4. then, while inside the app folder, do 'feature cloud controller start'
5. then do 'feature cloud app build .' this builds the docker image
6. go to featurecloud.ai > for developer > test
7. chose the app name, the right number of client, and their path and start the app

   
** Here you can find another version of linear regression [https://featurecloud.ai/app/linear-regression](url) which shares XT.X and XT.Y. However,For our paper, we used the beta-sharing linear regression, which only shares the betas (slope and intercepts). 

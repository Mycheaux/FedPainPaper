This folder contains the repository links to the apps which can be run in the testbed directly. On the other hand, if one is willing to run the same feature cloud apps across multiple devices the link of the same and instructions for those are given below.
## Repo link:
A. Simple Beta sharing Linear Regression (low communication cost) : [https://github.com/FeatureCloud](url)
B. Logistic regression : [https://github.com/FeatureCloud/fc-logistic-regression](url)
C. Random Forest regression : [https://github.com/FeatureCloud/fc-random-forest
](URL)
Same repo link can be found in app description of each featurecloud apps also.


To Run Featurecloud apps, you would require a featurecloud account; find the apps in the app store of Featurecloud: After this, you can follow the following video to run the apps : [https://featurecloud.ai/researchers](url)
## App link:
A. Simple Beta sharing Linear Regression (low communication cost) : [https://featurecloud.ai/app/beta-sharing-fed-linear-regression](url)
B. Logistic regression : [https://featurecloud.ai/app/logistic-regression](url)
C. Random Forest regression : [https://featurecloud.ai/app/random-forest](url)

To Run the apps in the testbed, follow the following instructions:
1. Go to the repo of a particular app
2. Clone that repo
3. you should have docker and python installed. Now install feature cloud using 'pip install featurecloud'.
4. then, while inside the app folder, do 'featurecloud controller start'.
5. then do 'feature cloud app build .' this builds the docker image
6. go to featurecloud.ai > for developer > test
7. chose the app name, the right number of client, and their path and start the app

   
** Here you can find another version of linear regression [https://featurecloud.ai/app/linear-regression](url) which shares XT.X and XT.Y. However,For our paper, we used the beta-sharing linear regression, which only shares the betas (slope and intercepts). 

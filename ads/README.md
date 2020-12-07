To use the Watson ML predictive models in ADS we need to do a bit of configuration to 
connect ADS to the Watson ML Deployment Space we created earlier.

First we need to create a new machine learning provider, her is the configuration screen:

![](images/ml_config.jpg) 

We need the following details :
1. An API key
2. The deployment space ID
3. The URL for the Watson ML instance
4. The authentication URL (pre-filled)

Naturally, none of these things are in the same place. The API key is defined at your 
account level. The space ID can be found in the settings tab of the deployment space and the 
URL for Watson ML depends on where your Watson instance lives.

You can watch me setup this configuration on YouTube here: https://youtu.be/_25IEOPitgM




Here is a list of Watson URL's : https://cloud.ibm.com/apidocs/machine-learning#endpoint-url 


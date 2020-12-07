This repository contains assets for a simple IBM ADS demo that uses rules and ML to determine 
the best drug to offer a patient.

The best way to understand the material here is review it in the following order:
1. The data
2. The use of machine learning
3. Instructions for using ML in ADS


The data directory has an explanation of the data, it's design and how it was generated.

Machine learning has an example Jupyter notebook that uses an Sklearn decision tree to 
predict drug types using the data described above. This model isn't used in the demo, 
but it does have a useful visualisation of a decision tree. 
Watson Auto AI is used to train & deploy the models used in the demo and there is a 
YouTube video showing how to use Auto AI to train a drug predicton model.

The ADS directory contains notes and video showing how to integrate the models from 
Watson Auto AI into ADS. 

Finally, the Drug Prediction v2 directory contains the ADS decision solution I used in the demo. 
To import this into ADS clone this repo then zip the Drug Prediction v2 directory. This 
zipped directory can be imported into your ADS project. 

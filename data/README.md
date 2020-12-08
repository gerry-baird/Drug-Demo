The demo uses generated data. There's a few hundred rows of data that contain Age, 
Gender, Blood Pressure, BMI and Drug. This data will be used to train and ML model to 
predict the value of the Drug column from the other values.

The data looks like this :

![](images/data_preview.jpg)

The dataset was designed to have the following partitions.These are the details that the ML model will try and learn.

![](images/data_design.jpg) 

In a real dataset real partitions will exist, these will be based on characteristics that cannot
be easily determined, hence the use of an ML model to discover them. 

Next, I generated 100 rows of data for each partition using the specification above. The 
online version of the tool I'm using is limited to 100 rows at a time. It's called
generate data and you can find it [here](https://www.generatedata.com).


![](images/generate_data.jpg)

In this example I'm generating the data for Drug A. Seelct the prompt for download option which I've highlighted.


The last partition I create is for noise. They have similar characteristics to the group on row 4 that receive Drug C, 
but they are younger (72-75) and they have a slightly lower BMI (25-30). The addition of noise to the data makes 
the ML models a bit less accurate and makes the data more realistic.

Using the data generator I created 100 rows at a time using the characteristics described above. First I setup the tool
to generate the data for Drug A, and called this file A.csv. Then I repeated the exercise for 
B,C,D,E. Finally, I created noise.csv

Once all the files were created I combined them into a single csv and shuffled it. The output from all this 
is DrugV2Combined.csv which is provided in this folder.   

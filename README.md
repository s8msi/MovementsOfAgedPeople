# MovementsOfAgedPeople
This is a Python Data Analysis Project that was done on Google Colaboratory. The Dataset is on a motion sensor that is installed in the homes of senior citizens in London.
----
The Dataset is based on a motion sensor that is installed on the homes of the senior citizens in London. This Motion Sensor captures any movement in the homes of the senior citizens. This is a huge data with a lot of columns. Therefore, we go through the data and take the columns we require for our analysis. The description of the columns are given in the Jupyter Notebook as well.

First, we try to see if there are any missing values in the dataset. We see that the location is null in many columns. Since this dataset is based on Motion Sensors in London, we can assure that all the locations should be London.

Then we see that the date column is not clean and not in the proper type. Therefore we clean the columnn and change the datatype to datetime. 

Now, we step into the EDA of this Dataset. We try and figure out a pattern in the number of times the Motion Sensor is triggered in different locations. So. let's try and figure out when the maximum of the population sleeps. After a few Visualization we see that the majority of the population sleeps between 10 PM and 6 AM.

And finally, we see that between the Motion Sensor has been triggered out of location between 9 AM and 5 PM a lot. So, to find where this location is. We need to set up a camera in their homes to find out this location.

Thank you!

# Reccomender-System

Callobrative filtering one of the Recommender method. MovieLens data sets used to derive like matrices ( theta.txt) of each user. The derived rating in the theta file is between 0 to 5 float numbers.

I downloaddd the data sets from the web page mentioned in the algorith and prenprocessed by numpy and panda to transform to easier form to directly use them. 

For recommendation I thought that If each user age, location etc. are given as what they are, could have been better createn specific cluster for them to classified users. 

Theta is the Callobrave filter result respect to give parameter( the results are float numbers between 0 to 5). 

I would dreamed to get better matching, it should be obtained if:

- each user age and related informations are known
- cluste respect to the information given of users are created 
- relationship of movie publishing time and user age related.

Than, for any user to find recommendation:
- find responsible cluster of the user
- find a user, whos like matrix is closest the user matrix 

# Recommender-System

Callobrative filtering one of the Advanced Recommender method ( where the attributes are not known or almost not known), however, I use more simpler method Content Based Filtering to determine attributes (theta.txt) of each of the user respect to MovieLens data set . The derived rating in the theta file is between 0 to 5 float numbers.

I downloaddd the data sets from the web page mentioned in the algorith and preprocessed by numpy and panda to transform to easier form to directly use them. 

For recommendation I thought that If each user age, location etc. are given as what they are, could have been better createn specific cluster for them to classified users. 

Theta is the Content Based filtering result respect to give parameter( the results are float numbers between 0 to 5). 

I would dreamed to get better matching, it should be obtained if:

- each user age and related informations are known ( to use cortelation function)
- cluster respect to the information given of users are created
- relationship of movie publishing time and user age relation
-...

Than, for any user to find recommendation:
- find responsible cluster of the user
- find a user ( in same cluster), whos attribute matrix is closest the user matrix.

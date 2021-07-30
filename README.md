# Titanic
Study of the titanic data set.

This is my approach on learning from the disaster. In this study I show multiple approaches to how one should approach the data and which models I use. My submission got a 76.5% accuracy. I found that the Random Forest is the best approach to solve the issue.

During my study of the data I found multiple things. First, the "kids and women" rule applies. Since most of the survivors are women. I also found that the wealthy had a higher chance of survival. One can clearly see that the first class had a better chance of survival.

A brilliant idea I found while searching in some of the writeups, is to use age and class to compute a new columm age\*class. This new column ranges from 0 to 9. Since we changed age from 0 to 3 and class ranges from 1 to 3. The higher the value in this column the lower the chance of survival. A 9 is an person that boarded with a third class ticket and is above 64 years old.

I also am showing the following plot since it is my favorite in the bunch. It shows 4 different parameters at the same time. The baording, the survival, the class and sex. We can see that no matter where you board, if you are a woman and in first class you are most likely to survive.

![Point Plot](https://www.kaggleusercontent.com/kf/69389017/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..LH95TL6oBBqmUtUeD03a8Q.GmFy3w8VBU--LnXssuzTnocZ6wVgGq1UvWWJ8CFNC4XMvwRWzvWXuu-Fut4Fl1wyNpNcNOz5yDkw4oRDOf6TI2peyAOpDXopH-ej5mkp03f7n6XR6DhsVOYCIacR4c0EYYUWbZwFkQS0Vr2VYgLvbU0fYobQ0GTQchNAJNiVkKrtlXKaeQgwvEdNGtPHDogs9cxa2EWs3E0VWnsEgG-ACsmmdTyWjntPSF3_tmnD6XBnoiu9mdiL6D_S-OLT4Xt0Ra8Nv6UfR_l2iDXmKemsRYLlkvti_eMJIxqjdQMq_cc9mR-URwnzNlXQL-XWciOMVUjhs39c1TPs5WdBHxYTqB6LouggLhIaJTZz2BN6IUhCa-DeYfhpJlgJ5sgx5MYtWv7FUE2sSMV_v9svCo6yGxd_C8xe8eoxwT2iXE3i-4zxCz1cqj1479USCClbeHDGl2mZjf0Q1Itv-Lk_OgWOejP5gb4ol3ctiuJUlDCdrDs_-8kTHN02cG0oF2xH36xljk0cuFNyDpbcT-ZragtZhSgAh-TX6C7WSOlLG37DpertZqydV_fxCI5xgUq73sC18vNIHFn80UUnk007MxJx5OFZDO_QJ4QiposCmdkqU8Tke6PqqCUH7nOCyy7Iym2P5n_5e47x00nV3Pl0qiNkK4x1MLwup6bxlh4ZrR4sCsY.svVRibnQZvLXhzNO3FGV9Q/__results___files/__results___62_2.png) 

Finally I display the models and compare them to one another to see which ones gives us the best results. I choose Random Forest over Decision Tree even though they have the same percentage. Due to Decision Tree sometimes overfitting the data.

I hope someone can find this useful.

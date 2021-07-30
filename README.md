# Titanic
Study of the titanic data set.

This is my approach on learning from the disaster. In this study I show multiple approaches to how one should approach the data and which models I use. My submission got a 76.5% accuracy. I found that the Random Forest is the best approach to solve the issue.

During my study of the data I found multiple things. First, the "kids and women" rule applies. Since most of the survivors are women. I also found that the wealthy had a higher chance of survival. One can clearly see that the first class had a better chance of survival.

A brilliant idea I found while searching in some of the writeups, is to use age and class to compute a new columm age\*class. This new column ranges from 0 to 9. Since we changed age from 0 to 3 and class ranges from 1 to 3. The higher the value in this column the lower the chance of survival. A 9 is an person that boarded with a third class ticket and is above 64 years old.

I also am showing the [following plot](https://github.com/farhatbassel/Titanic/blob/main/PointPlot.png), since it is my favorite in the bunch. It shows 4 different parameters at the same time. The baording, the survival, the class and sex. We can see that no matter where you board, if you are a woman and in first class you are most likely to survive.

Finally I display the models and compare them to one another to see which ones gives us the best results. I choose Random Forest over Decision Tree even though they have the same percentage. Due to Decision Tree sometimes overfitting the data.

I hope someone can find this useful.

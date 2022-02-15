# Algorithmic_Trading
In this project we used Sklearn and pandas to test different aproaches to algorithmic trading.

This was our baseline model with a training length of 3 months:
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_3month.png)

In increasing the training set we were able to increase the cumulative returns from our strategy. Pictured below are 6 and 9 month, respectively:
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_6month.png)
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_9month.png)

In adjusting the SMA length used in our techncial analysis we saw various different results:
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_SMA1.png)
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_SMA2.png)
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/SVM_SMA3.png)
Ultimately the best returns came from using SMAs of 3 and 200 days.

Lastly we had hoped to integrate a different model for this project. The logistical regression model had not been very effective as seen below:
![alt text](https://github.com/apeyton2/Algorithmic_Trading/blob/main/Resources/LR.png)

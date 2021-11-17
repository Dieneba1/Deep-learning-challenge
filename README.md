# DeDeep Learning Challenge Report

1.the purpose of this analysis was to find out how successful an organization might be at getting a loan by using the charity dataset to predict that outcome. 

2. 
•	The targets variables of the model are the y variables: 'IS_SUCCESSFUL' column below.


•	The features variables are my input X variables. Those variables include everything in our DataFrame except our target variables and the other 2 variables (EIN & NAME) we dropped. 

•	The variables that we removed from our input data are EIN and Name as they don t have an impact on our target outcome
•	In my first attempt, I used 3 layers with 80, 30 and 1 neurons respectively. in terms of activation, I used ‘relu’ on my 1st and 2nd layers and sigmoid on my output later.


By doing so I achieved an accuracy of 72.99% as seen below:


•	I was not able to achieve the target model performance of 75%. I did a second attempt to improve my model performance by adding another hidden layer with a "relu” activation while maintaining the number of nodes about the same but was only able to achieve 73% accuracy(see screenshot below)  which is not that different from the result on the 1st attempt.



•	Since I still wasn’t able to achieve 75% accuracy, I tried a 3rd time to optimize my model under a new notebook called “AlphabetSoupCharity_Optimzation” where I added another layer to my already optimized model. With 5 layers now and changing slightly my activation function of 2 of my layers, I still wasn’t able to achieve 75% accuracy but still stayed. around 73%. 


Since I already made 3 attempts at optimizing my data for this homework, I will keep making some changes on my own an

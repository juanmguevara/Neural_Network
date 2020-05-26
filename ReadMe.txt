# How many neurons and layers did you select for your neural network model? Why?

I considered to have 7 features; therefore, I used 14 neurons double my number of features.
I also used 2 hidden layers, since my first layer had 14 neurons I had 12 neurons for the second hidden layer.

# Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

I was able to achieve my target model performance I reached a 99% accuracy, this must mean that my model was overfitted to the data and might not be great to use to predict future outcomes.
This outcome is due to the model that I picked "sigmoid"

# If you were to implement a different model to solve this classification problem, which would you choose? Why?

I ran the analysis again this time with a different model "relu" and using 8 neurons and the results were terrible, for the accuracy which gave me a 7.77e-04 and a loss of 15.23. 
For this model I would stay with the sigmoid analysis with one change. I would remove a hidden layer since it is not neccessary in this situation given the high accuarcy.

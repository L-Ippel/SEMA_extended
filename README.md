# SEMA_extended

In this project we extended the original SEMA algorithm to fit more models than just the random intercept model. It is still ungoing work and I am aware that the function is not very user friendly, but we are working on it. One file (SEMA Functions) contains all the code the SEMA algorithm needs to fit the multilevel model. 

The function requires the data and the current state of parameters. Whenever a new individual enters, a lists is created containing all required objects. At the start of the data stream, a global list is created which contains the current state of the parameters. 

So far, the function only fits multilevel models for continuous outcomes. Note that for categorical predictors, the user should create dummy variables him/herself. 

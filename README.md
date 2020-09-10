# Transformers_Finance
Transformer model for stock evolution prediction 

This project was done in collaboration with David Chakroun for the course MTI830 of the ETS. It is a student project for educative and learning purposes. 
The choices in the architecture and data are purely personal and not based upon an extensive research. The model and data set can be improved. 

In this project, we use a slightly modified version of the state of the art Transformer model (Vaswani & al, 2017) to predict the evolution of stock prices. Our model can process the temporal data of several sequences (stocks) simultaneously using Attention. Our goal was to use the Attention mechanism to learn the complex relations between stocks and better predict their evolutions.
In short, it did not work. Although we were able to create a model able to compare the stocks against each others, the predictions of the model were not satisfying.

You can find our code in the notebook as well as our report regarding this project. In the report, we explain our model architecture and the improvements that could be made. We also give insights on what is limiting our current model and how to eventually adress it. Note that this is not a peer reviewed article but a student project, the opinions we express are our own. Please refer to the sources in the report for more reliable peer reviewed information.  

The notebooks 'data_loader' and 'data_analyser' are used to generate the 3D data for our model. The notebook 'model' contains the model itself as well as the training procedure.
We used the historical data available on Yahoo Finance for 476 equities/ETF/spots over 15 years and several PyTorch modules for the implementation. 

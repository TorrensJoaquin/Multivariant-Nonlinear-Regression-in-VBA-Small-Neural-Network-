# Multivariant-Nonlinear-Regression-in-VBA-Small-Neural-Network-
Despite the big boom in Neural Networks. The common worker is still outside of his/her capabilities.
The idea of the proyect is to give an easy tool for small neural networks (something around 6 layers and 80 neurons maybe).
It has to be run without any other software than Microsoft Excel.
This work is inspired in Emanuele Bonura's Blog "A Neural Network in 11 lines…of VBA!" and Carlos Ruiz from UTN FRRo.
You will need a sheet called DATA. Were you can put the data. (x's in the left, y's in the right, 1 row of header) An Empty sheet called Result. Were the code of the formula is going to be generated.
A Learning Ratio Range Taste is also included.
Tuning of the following parameters in the modules is required:
n_hid_layer = 'Number of hidden layers
x_features = 'Number of x features
y_features = 'Number of y features
n_neurons_hid_layer(x) = 'Number of neurons in the hidden layer x (change the x for as many layers you have set)
SizeOfDataBase = 'The size of the database
UploadOldModel = 'Train more an existing model.
ChangeArquitecture = 'It's common, and recommended, start with a shallow neural network and start increasing/decreasing neurons/layers. If it's true, will recycle old weights and initialize new ones.
SamplesInBatch = 'Maximun of 1024
Comming Soon:
A diagnosis tool.
Training/Test división.
During this work Softplus, Sigmoid, Tanh and Relu Function were implemented. Relu is in the stable versión. (Yes, we all look at relu at first and say, No Way!, but today is the right choice)
Please. Have the inmediate window visible. Data will be shown

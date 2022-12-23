# Fashion-MNIST
## Dataset Description
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

Each training and test example is assigned to one of the following labels:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## Project Phases
### Data Preparations
In this project, you will use the Fashion-MNIST dataset using a CNN neural network architecture.

1. First, download the data file, load it, and 
   - Describe the data
   - Clean the data 
   - Check the data for missing values or duplicates and carry out proper correction methods
   - Visualize the data using proper visualization methods. 
   - Draw some of the images 
   - Carry out required correlation analysis
2. Carry out any required preprocessing operations on the data 
3. Encode the labels

### Training a CNN neural network
We will implement a LeNet-5 network to recognize the Fashion MNIST digits.

- Modify hyperparameters to get to the best performance you can achieve. 
- Evaluate the model using 5-fold cross-validation.
- In the report, provide a plot of accuracy improvement using the previously mentioned techniques. Also plot the convergence curve for LeNet-5. 
- Comment on why you think LeNet-5 further improves the accuracy if any at all. And if it doesn't, why not? 
- Note that this is an open-ended problem. So, there could be very good solutions.
- Try to use other two CNN models (using transfer learning) and compare the results with the full trained LeNet-5

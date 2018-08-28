# Neural-net-from-scratch

## Goal: 
Implement a 2-layer neural network from scratch in (1) Pytorch, (2) Numpy, (3) No libraries.



## Data:
Boston housing dataset from the UCI archive was used.

This dataset is concerned with the housing prices in the suburbs of Boston. It consisted of 505 samples with 13 features like “average number of rooms per dwelling”, “pupil-teacher ratio by town”, etc and the target feature was median value of owner-occupied homes in $1000's”. 70:30 train-test split was used. Test and validation sets were considered same in this case for simplicity.



## Models:
2-layer neural network models were implemented from scratch in
(1) Vanilla Pytorch, just for gpu computation, without using its ‘autograd’ and ‘optim’ modules.
(2) Pure Numpy.
(3) No libraries.



## Results:
MSE was used as loss and metric. Its value for different approaches was obtained as follows:
(1) Pytorch (CPU): 42.99, Pytorch (GPU): 36.82
(2) Numpy: 43.13
(3) No libraries: 57.87

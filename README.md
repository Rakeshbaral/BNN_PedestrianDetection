# BNN_PedestrianDetection
We introduce a method to train Binarized Neural Networks (BNNs) - neural networks with binary weights and activations at run-time. At
training-time the binary weights and activations
are used for computing the parameters gradients. During the forward pass, BNNs drastically
reduce memory size and accesses, and replace
most arithmetic operations with bit-wise operations, which is expected to substantially improve
power-efficiency.

Implementing the DenseNet over INRIA dataset gives below plot while training the model. Here the Adam optimizer is used to train.


<img width="305" alt="Capture" src="https://user-images.githubusercontent.com/16417735/135139891-428aad50-d950-43b7-b435-5063a9d1ac59.PNG">

Working on the results and accuracy details in application to the INRIA and Caltech Datset, will be updated soon.

## Team #20, 2022, hackathon-korea

Our team developed two qnn assisted machine learning models (Quantum calculator and Quantum machine learning based image classifier).

Pytorch/qiskit packages are required for running the codes.

### Quantum calculator

- We designed the addition calculator using quantum machine learning.
- To generate an input data, two random floating numbers (one pair) within [0,1] were generated.
- A target data was obtained from summation of the input data.


### Quantum machine learning based image classifier 
- We designed the image classifier using quantum machine learning.
- input/target data were obtained from fashion-MNIST.
- The data with label 0(T-shirt/top) and 1(Trouser) was only used for this code.

Reference: qiskit tutorials (https://qiskit.org/documentation/machine-learning/tutorials/05_torch_connector.html)

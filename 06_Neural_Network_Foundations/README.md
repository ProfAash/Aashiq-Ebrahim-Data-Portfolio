**Project Overview**
This project explores the fundamental building blocks of Deep Learning by manually implementing a neural network to model logical operations. While most modern AI uses high-level libraries, this task demonstrates a deep understanding of how weights, biases, and activation functions interact to process information.

Technical Workflow
Mathematical Implementation: Utilized NumPy to perform matrix multiplications representing the flow of data through neural layers.

Activation Function: Implemented the Sigmoid Function to introduce non-linearity into the system, allowing the model to make probabilistic predictions.

Perceptron Logic: Successfully modeled fundamental logic gates including AND and OR by manually adjusting weight and bias parameters.

Multi-Layer Architecture: Designed a hidden layer structure to solve the XOR Gate problem, which is mathematically impossible for a single-layer perceptron to solve (the "Linear Separability" problem).

Strategic Insights
The XOR Paradox: The project highlights the necessity of Hidden Layers. By adding depth to the network, the model learned to create non-linear decision boundaries, a prerequisite for complex tasks like image recognition or natural language processing.

Weight Sensitivity: Through manual parameter tuning, I gained insight into how small changes in weights can drastically shift model output, reinforcing the importance of optimization algorithms like Gradient Descent.

Repository Contents
Neural_Network_Logic_Gates.ipynb: The complete Python notebook featuring class-based implementations of layers and networks.

Key Components:

Neuron class logic.

Sigmoid activation implementation.

Multi-layer network for XOR computation.

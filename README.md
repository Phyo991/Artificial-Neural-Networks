# Artificial-Neural-Networks

This exercise is from coursera that practice Forward Propagation to understand neural network and how they work even better. 

Neural network makes predictions through the forward propagation process. Forward propagation is the process through wich data passes through layers from the input layer all the way to the output layers. 

Based on the neural networks in our brain, we have dendrites, which are the arms of the large network. The soma, or the cell body, is central and connects to the axon. The axon, a slender projection, extends outwards from the soma.

![DALL·E 2024-01-28 16 09 47 - An illustration depicting the basic structure of a neuron in the human brain  The image should clearly show dendrites, which are the branching structu](https://github.com/Phyo991/Artificial-Neural-Networks/assets/142148113/2e348ee7-5f83-4e39-be62-eaee130e7fd4)

This exercise is from coursera that practice Forward Propagation to understand neural network and how they work even better. 

Neural network makes predictions through the forward propagation process. Forward propagation is the process through wich data passes through layers from the input layer all the way to the output layers. 

Based on the neural networks in our brain, we have dendrites, which are the arms of the large network. The soma, or the cell body, is central and connects to the axon. The axon, a slender projection, extends outwards from the soma.
![IMG_9366](https://github.com/Phyo991/Artificial-Neural-Networks/assets/142148113/6eeef9eb-80f0-4cb9-bff3-2869474cd82c)

When describing a neural network, you would typically refer to the first layer as the 'input layer,' which is responsible for receiving the signals. The final layer is known as the 'output layer,' and it's where the network produces its results, based on the learned patterns. Between these two, there are multiple 'hidden layers.' These hidden layers are where the network processes the inputs through a series of computations and transformations, learning to detect complex patterns and make decisions.
![IMG_9367](https://github.com/Phyo991/Artificial-Neural-Networks/assets/142148113/1e298ede-b04d-4f46-8dcf-2fda38500956)

In a neural network, each connection between nodes is assigned a specific weight, which plays a crucial role in processing information. Let's consider two inputs, x1 and x2. These inputs can be integers or floating-point numbers. As they pass through their respective connections, their values are adjusted based on the weights of these connections, denoted as w1 and w2.

The process works as follows: each input value is multiplied by its corresponding weight. For x1, the value is multiplied by w1, and for x2, it is multiplied by w2. This operation scales the input values, effectively determining the importance or influence of each input in the network's decision-making process. The weighted inputs are then summed together, forming a part of the equation:

z = x1 . w1 + x2 . w2

However, this equation also includes an additional term, b1, known as the bias. The bias b1 is a constant value added to the sum. It serves as an adjustable offset, ensuring that even when all inputs are zero, the neuron can still output a non-zero value if necessary. This addition of bias makes the neural model more flexible and capable of fitting a wider range of data patterns.

Thus, the complete equation becomes:

z = x1 . w1 + x2 . w2 + b1

In this equation, z represents the linear combination of the inputs, which is a crucial step in the neural network's information processing. The weights (w1, w2) and the bias (b1) are parameters that the network learns during training, allowing it to make accurate predictions or decisions based on its inputs.

![IMG_9368](https://github.com/Phyo991/Artificial-Neural-Networks/assets/142148113/c9b5a54e-3f1e-4d1c-952f-e3d36c12c1da)

To enhance the processing capabilities of a neural network, we often apply a function like the sigmoid function to the output of each neuron. The sigmoid function transforms the linear combination of inputs (z) into a non-linear output, which is crucial for the network to learn and represent more complex patterns. The sigmoid function is expressed as:

![436DC2F5-71F6-4D33-BA6E-080764891FD6_1_201_a](https://github.com/Phyo991/Artificial-Neural-Networks/assets/142148113/e1a565ff-e3e2-43ac-b55c-8ac96d0639eb)



This function converts the value of z into a value between 0 and 1, effectively normalizing the output. This is particularly useful in scenarios like binary classification, where the output is interpreted as a probability.

1. **Non-linearity:** It helps the network learn complex patterns, which linear functions can't handle.
2. **Differentiable:** This property is crucial for training the network effectively.
3. **Output Range:** It squashes the output to a range ideal for probability interpretation, like in classification tasks.

In a neural network, if the weighted sum of inputs (the sum after applying weights to each input) is a large positive number, the output of the neuron, after applying the sigmoid activation function, will be close to 1. Conversely, if this weighted sum is a large negative number, the output will be close to 0.

The sigmoid function, often called an activation function, determines whether the neuron should be 'activated' or not. In simple terms, it decides if the neuron should pass its information forward or not. This concept of 'activation' helps the network make decisions, like whether to process or ignore certain data. If a neural network doesn't use a sigmoid or any other non-linear activation function, this neural network is just a linear regression model. 

# You can find the practical exercises in the file named 'Forward_Propagation.ipynb







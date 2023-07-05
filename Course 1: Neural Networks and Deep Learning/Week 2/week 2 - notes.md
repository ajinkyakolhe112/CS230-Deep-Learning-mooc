Week 2 Lecture Notes: 1 Neuron NN from Scratch Directly

1. Logistic Regression as NN
   1. **NEW**: NN as Neuron -> Layer -> Multi layers: Data -> Weights -> Activation -> Error -> Error wrt Weights Gradient -> Weight Update in Direction of Error Reduction. (Simple one at a time Gradient Descent, not a fancy name)
      1. All innovation, improvements, are on this basic structure
         1. Data -> Transfer Learning & Image Augmentation
         2. Transform Operation -> Dot Product or CNN or 
         3. Activation Function -> 1 + e^x to relu
         4. Error Function -> Multi Error Function
         5. Better Weight Update -> momentum, adaptive learning rate, 
         6. Understanding architecture & understanding the problem: Architecture innovation graph
         7. **Number of Parameters(memory) & Learning Quality(learning rate) & Operations for Learning(cpu) & Anything else**
      2. Fundamentals with Pytorch
         1. Image Data, Channels. Filter/Kernel & Convolution. Or regression problem
         2. Multiplication or Dot Product (with Weights)
         3. Parameter investigation (Memory)
         4. Activation Function
         5. Error
         6. Error wrt Weights Gradient Calculation
         7. Weight Update
   2. Binary Classification for Cat or Not Cat
      1. Changes
         1. Use image as 2d, instead of vector. 
         2. Use image dimentions with channels
         3. Write example dimention in latex
         4. Write kernel filter as table for better visibility
         5. Show tizn package of neural network
         6. Build interactable neural network viewer for fundamentals of the network
         7. Tensorflow Playground

### Week 2 - Analysis
- Aim of week 2
  - Learn DL concepts
  - Learn Maths of the concepts
  - Learn implementation of concepts - directly with Numpy
  - Working model of Simple NN - but directly with Numpy
- Great, Good, Nitpicky, Bad, Ugly Commentary
  - Bad: Lectures don't have hands on sections to understand them better. Latex & Pytorch code of thing to play around will reinforce assignment
  - Nitpicky: Notebook variable names, better diagrams
  - Nitpicky: Problem importance & business contex not setup. Directly jumping to solving cat vs not cat.
  - Good: Assignment has assert & testing codes
  - Bad: Code should be modular and in script format too for easy reading of source code. Notebook & Script both have their uses
  - Assignment: (Comparitively simpler than lectures)
    - Micro code completion to be done
    - Rest of the code is implementation of topics in lecture
    - Doesn't have diagrams of Data in latex. (data could be visualized as fbox or table)
- Conclusion
  - Too many new concepts
  - Too heavy on maths
  - Hands on programming delayed
  - Hands on programming from scratch directly. Not easing into it


Assignment 1 & 2: NN are brute force experimental way of learning (universal approximation theoram)
- Working keras code to analyse & execute beforehand
- (combination of tf playground + keras + wnb)
- problem: approximating any complex function with simple small line
  - few equations... y = e^x. We give values of many y & x, and let the neural network learn to approximate that function.

**Changes**
 1. Use image as 2d, instead of vector
 2. Use markdown latex instead of handwritten slides
    1. Use image dimentions with channels
    2. Write example dimention values in latex instead of handwriting
    3. Write kernel filter as table for better visibility
    4. Show tizn package of neural network
 3. Compliment markdown with code snippets for hands on. Keras, Pytorch both
 4. Build interactable neural network viewer for fundamentals of the network. (in javascript like cnn viewer or lenet or tf playground)
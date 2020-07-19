# A-Deep-Neural-Network-from-Scratch
It is a common exercise to build a deep neural network (if not shallow) from scratch. This repository contains a notebook which aims to do so, without using any specialized packages.
By their rigorous nature, NNs tend to be highly recursive. To overcome this issue, we build functions that perform: 
- Initialization of parameters. 
- Forward propagation 
- Computing costs
- Back propagation
- Updating parameters from gradients (gradient descent) 

We will commonly refer to these functions as "helper functions". While they use of for loops in inevitable in gradient descent and multi-layered propagation,
the code is written in a way that uses the minimal amount of for loops. 

Upon building the helper functions, we test the model using the "Cats Vs No Cats" dataset and we find reasonable accuracy results. 
The libraries used are simply: 
- <code> numpy </code> 
- <code> matplotlib </code> 
- <code> h5py </code> which mainly used to encode the dataset of images. 

It is important to remark that this is mainly motivated from Andrew Ng's course on Deep learning on Coursera. Moreover, there might be some disruptions on the mark up text within the code. 
This is mainly an issue from GitHub. To better see the markup text and the notebook, click  <a href="https://nbviewer.jupyter.org/github/Hashemalsabi/A-Deep-Neural-Netwrok-from-Scratch/blob/master/A%20Deep%20NN%20from%20scratch.ipynb"> here. </a>. 


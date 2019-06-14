# Spiral
PyTorch DataLoader demo.  Trains a neural network to fit spiral data.

This notebook is a demonstration of workflow for big-data handling in PyTorch.

The PyTorch DataLoader class is a mechanism to serve batches of data to a machine learning agent. It can be arranged to work with data already in memory but also to serve data from disk on-the-fly.

When a sizeable data set will not fit into RAM the DataLoader class offers a solution by drawing manageable batches from disk. This is accomplished in parallel by multiple workers thereby keeping a demanding GPU supplied with mini-batches of data.

What follows is a small-data exercise using big-data techniques.

[Open in Google Colab](https://colab.research.google.com/github/Formulator/Spiral/blob/master/PyTorch_Spiral_DataLoader.ipynb)

[View on GitHub](https://github.com/Formulator/Spiral/blob/master/PyTorch_Spiral_DataLoader.ipynb)

![Sample output](https://github.com/Formulator/spiral/blob/master/spiral.png)

# Cat-Vs-Dog-Classifier
Implemented Cat vs Dog Classifier using CNNs.
# Dataset
I took the data set from kaggle website where this challenge is posted.
https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data



![](https://www.kaggleusercontent.com/kf/10169792/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..r1SHJOENGkkcrjTgm875UA.RanrP2Mom5NqWx_0rQ3QgNzYujOcMREQscZWzEYt-XHI4ESwFxDK107Y6wbc2iqDO2Vi0r-eYQQjDS1iIjRz_l2fJlYFRdPCexlh3cDm4mQj9-JQ3jCyVK3SyRXRWB8jtixMbJR2xBSMP3MKF6VZ38CJvAc1SopwmlhtM3To11Y.5fTXkYTiST9bf0MnFB6kkw/__results___files/__results___4_0.png)


# Model

MY model had two convolution and maxpooling layers followed by one denser layer and then finally softmax layer.
The optimizer used is adam optimizer. The loss is binary crossentropy .
`Epochs=10`
`Batch Size=32`


# Training-

Train Accuracy= 95
Validation Accuracy=78







[image1]: ./images/sample1.png "Sample Output"
[image2]: ./images/sample2.png "Sample Human Output"

## Project Overview

This is a project I worked on as a part of my Udacity Deep Learning Nanodegree. Given an image, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. Used CNN models for classification.

### Output for a dog

![Sample Output][image1]

### Output for a human

![Sample Human Output][image2]

## Project Instructions

Dog image dataset can be found [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)

Human image dataset can be found [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

Bottleneck features to run this code in your local computer can be found [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz)

Navigate to the root folder and use the following commands to get started.

For __Mac/OSX__:
```
	conda env create -f requirements/dog-mac.yml
	source activate dog-project
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
        python -m ipykernel install --user --name dog-project --display-name "dog-project"
        jupyter notebook dog_app.ipynb
```

For __Linux__:
```
	conda env create -f requirements/dog-linux.yml
	source activate dog-project
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
        python -m ipykernel install --user --name dog-project --display-name "dog-project"
        jupyter notebook dog_app.ipynb
```

For __Windows__:
```
	conda env create -f requirements/dog-windows.yml
	activate dog-project
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
        python -m ipykernel install --user --name dog-project --display-name "dog-project"
        jupyter notebook dog_app.ipynb
```

### Useful Links

1. Andrej Karpathy's [CS231n Stanford course](http://cs231n.github.io/) on Convolutional Neural Networks.
2. [Michael Nielsen's book on Deep Learning](http://neuralnetworksanddeeplearning.com/)
3. [Transfer Learning](http://cs231n.github.io/transfer-learning/)
4. [Awesome Deep Learning Papers](https://github.com/terryum/awesome-deep-learning-papers)
5. [Summary of Deep Models for Face Recognition](http://cs.wellesley.edu/~vision/slides/Qianli_summary_deep_face_models.pdf)
6. [Systematic evaluation of CNN advances on the ImageNet](https://arxiv.org/abs/1606.02228)
7. [Gradient Based Learning Applied to Document Recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf)
8. [ImageNet Classification with Deep Convolutional Neural Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
9. [VERY DEEP CONVOLUTIONAL NETWORKS FOR LARGE-SCALE IMAGE RECOGNITION](https://arxiv.org/pdf/1409.1556.pdf)
10. [Going Deeper with Convolutions](https://www.cs.unc.edu/~wliu/papers/GoogLeNet.pdf)
11. [Deep Learning with depthwise separable Convolutions](https://arxiv.org/pdf/1610.02357.pdf)
12. [Sebastian Thrun's cancer detecting CNN](https://www.nature.com/articles/nature21056.epdf?referrer_access_token=_snzJ5POVSgpHutcNN4lEtRgN0jAjWel9jnR3ZoTv0NXpMHRAJy8Qn10ys2O4tuP9jVts1q2g1KBbk3Pd3AelZ36FalmvJLxw1ypYW0UxU7iShiMp86DmQ5Sh3wOBhXDm9idRXzicpVoBBhnUsXHzVUdYCPiVV0Slqf-Q25Ntb1SX_HAv3aFVSRgPbogozIHYQE3zSkyIghcAppAjrIkw1HtSwMvZ1PXrt6fVYXt-dvwXKEtdCN8qEHg0vbfl4_m&tracking_referrer=edition.cnn.com)
13. [Goodfellow, Bengio and Courville's advanced book on Deep Learning](https://www.deeplearningbook.org/)


	
	


[image1]: ./images/sample1.png "Sample Output"
[image2]: ./images/sample2.png "Sample Human Output"

## Project Overview

This is a project I worked on as a part of my Udacity Deep Learning Nanodegree. Given an image, the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed. Used CNN models for classification.

Output for a dog

![Sample Output][image1]

Output for a human

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

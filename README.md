## CNNs  Finetuning Resnet18 model (from torchvision)


 -  Download the CIFAR 10 dataset (original data can be found [here](http://www.cs.toronto.edu/~kriz/cifar.html), and here is a link to the  pickled [python version](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz). 
	
 -  Use the pretrained Resnet18 model (from trochvision) to extract features. Use the features as inputs in a new multi-class logistic regression model (use nn.Linear/ nn.Module to define your model)
	 -(a) Describe any choices made and report test performance.
	 -(b) Display the top 5 correct predictions and the top 5 incorrect predictions in each class (show the images and the prediction labels) compactly.
 -  Finetune the Resnet18 model's parameters suitably and repeat parts (a) and (b) from above. Compare the performance of finetuning versus using extracted features.

This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 
course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes
and is not intended to be used for clinical purposes.


<h3> Data Set </h3>

Link: https://drive.google.com/open?id=1-HQQciKYfwAO3oH7ci6zhg45DduvkpnK


<h2> VGG-16 </h2>
Training parameters are as follows:

BATCH SIZE	128
EPOCH	10
LR	0.001
MOMENTUM	0.9

Training Last Iteration:

Train Epoch: 9 [8928/12000 (99%)]	Loss: 0.246135: : 94it [05:09,  3.29s/it]

Validation Last Iteration:

Valid Epoch: 9 [1012/1500 (92%)]	Loss: 0.090385: : 12it [00:34,  2.89s/it]

Save model named as ‘vgg16_FC_Only.pth’

Testing

Accuracy of the network on the 1500 test images: 97 %

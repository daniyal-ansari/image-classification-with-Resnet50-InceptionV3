# image-classification-with-Resnet50-InceptionV3
classify retinal diseases with pre-trained models ResNet50 and InceptionV3. we freeze all the feature extractor layers and use our individual classifier.
first we implement InceptionV3 for the classification then in the second stage we use ResNet50 as another network have pre-trained weights on ImageNet.
results denoted that Inception has far better performance on our dataset with our individual classifier.
after that we unfreeze 2 last layer of these networks and train them with our dataset. results show impressive progress for ResNet50 and for InceptionV3 we have improvement too and its metrics(recall,precision
,f1score) show %99 of success.
after that we examine unfreezing 6 last layer and train their parameter and with this change we see progress for ResNet50 again(up to %88) and Inception save amount of %99.


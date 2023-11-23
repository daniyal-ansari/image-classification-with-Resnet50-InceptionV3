# image-classification-with-Resnet50-InceptionV3
classify retinal diseases with pre-trained models ResNet50 and InceptionV3. we freeze all the feature extractor layers and use our individual classifier.
first we implement InceptionV3 for the classification then in the second stage we use ResNet50 as another network have pre-trained weights on ImageNet.
results denoted that Inception has far better performance on our dataset with our individual classifier.

# ComputerVision_10MonkeyBreeds_Classification

We had images of 10 different breeds of images and the requirement was to build a model to classify them.
The total number images received was about a 1000 for training with each breed of monkey constituting 100 images each.

We had an additional 300 images which we kept aside to use for testing and validation of the classifier we intended to build.

When a CNN model was trained from the scratch the accuracy achieved was very less ~ 60%. Leveraging transfer learning using ResNet model trained on imagenet data accuracy
of 95% was achieved without any finetuning. Accuracy improved to more than 96% with addition and subsequent finetuning of just 2 custom dense layers after the ResNet base layer.

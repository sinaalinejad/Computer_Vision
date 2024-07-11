## Semantic Segmentation of Solar Panels using U-Net (ss_notebook.ipynb)
3 main steps:
- Preparing the dataset which contains images and the ground truth mask in which white color means the presence of solar panels, while black indicates absence.
- Using MobileNetV2 as encoder part of U-Net
- adding a decoder part. This is done using upsampling by the Conv2DTranspose layer in Keras
- Using dice loss as the loss function during optimization. This loss function uses the intersection and union of predicted and true regions
- Training the model for 30 epochs


## Classification of CIFAR10 Dataset (Q3.ipynb)
Multiple experiments were done:
- Using just a simple CNN
- Adding Data Augmentation before training the previous CNN (techniques like rotation and flip for data augmentation)
- Using pretrained Resnet50 on ImageNet as backbone



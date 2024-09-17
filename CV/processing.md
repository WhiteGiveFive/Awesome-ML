## Image Preprocessing Before Training

- [Image Processing in Python with Pillow](https://auth0.com/blog/image-processing-in-python-with-pillow/)


### loading the images from folders
I would prefer using OpenCV or PIL to load images from a folder. This is because I have more freedom later to split the dataset and customise the labels. Basicly, I want to build a class similar to the torch function that loads CIFAR-10, controlled by a argument to output training/valid/test sets.

- [OpenCV Vs PIL](https://www.geeksforgeeks.org/image-processing-opencv-vs-pil/)
- Using the torchvision.ImageFolder method
  - [How to load png using dta loader](https://discuss.pytorch.org/t/how-to-load-png-using-dataloader/17079)
  - [Intro-to-PyTorch: Loading Image Data](https://www.kaggle.com/code/leifuer/intro-to-pytorch-loading-image-data)
  - [Beginner’s Guide to Loading Image Data with PyTorch](https://towardsdatascience.com/beginners-guide-to-loading-image-data-with-pytorch-289c60b7afec)
- Using pyimagesearch package, [Image Data Loaders in PyToch](https://pyimagesearch.com/2021/10/04/image-data-loaders-in-pytorch/)

### split the train/valid/test
Stratified
K-fold
Stratified K-fold

### Some advanced image augmentation techniques

[YOLO10 Explanation](https://medium.com/@saiwadotai/yolov10-explanation-features-and-implementation-c67b49e44120)

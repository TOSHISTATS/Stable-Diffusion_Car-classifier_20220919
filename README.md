# Stable-Diffusion_Car-classifier_20220919
car-classifier based on synthetic car-images by Stable Diffusion

There are two classes in it. 0.GTR, 1.Porsche. There are 100 images for each class. Therefore total 200 images for training. The images are synthetic car-images by Stable Diffusion. Then let us classify them into one of the classes automatically by deep learning. It is a classification problem "one out of two". As there is a little data which is available, we need transfer-learnig. In TensorFlow, EfficientNet is available for feature extraction. Based on the model, we achieve higher accracy which is 80% for test data of real images. Each class has 20 images for the test


![Screenshot 2022-09-19 13 56 48](https://user-images.githubusercontent.com/28681557/190952191-1f44c92b-8864-47c4-907f-c0381e26168a.png)

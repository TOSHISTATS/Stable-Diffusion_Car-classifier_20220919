# Stable-Diffusion_Car-classifier_20220921 
car-classifier based on synthetic car-images by Stable Diffusion

There are four classes in it. 0.GTR, 1.Porsche, 2.Lexus, 3.Lamborghini. There are 1000 images for each class. Therefore total 4000 images for training. The images are synthetic car-images by Stable Diffusion. Then let us classify them into one of the classes automatically by deep learning. It is a classification problem "one out of four". As there is a little data which is available, we need transfer-learnig. In TensorFlow, EfficientNet is available for feature extraction. Based on the model, we achieve higher accracy which is 90% for test data of real images. Each class has 100 images for the test. The images below are examples of synthetic car-images by Stable Diffusion

![Screenshot 2022-09-19 14 01 48](https://user-images.githubusercontent.com/28681557/190952582-09560455-83d9-4ced-91cc-9eb9c55a5d7b.png)
![Screenshot 2022-09-19 14 02 07](https://user-images.githubusercontent.com/28681557/190952591-26fc2214-b314-46ca-adde-1c184886be41.png)







![Screenshot 2022-09-21 19 17 10](https://user-images.githubusercontent.com/28681557/191479864-09c6b04c-f766-4315-a3e2-a848221db2a6.png)



"Stable Diffusion" is being released under a Creative ML OpenRAIL-M license by Stability AI
https://huggingface.co/spaces/CompVis/stable-diffusion-license


This code is solely for educational purpose. The code cannot be used for investments or busineeses in practice. Toshi Stats Co.,Ltd. and I do not accept any responsibility or liability for loss or damage occasioned to any person or property through using materials, instructions, methods, algorithm or ideas contained herein, or acting or refraining from acting as a result of such use. Toshi Stats Co.,Ltd. and I expressly disclaim all implied warranties, including merchantability or fitness for any particular purpose. There will be no duty on Toshi Stats Co.,Ltd. and me to correct any errors or defects in the codes and the software.

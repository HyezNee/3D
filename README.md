# 3D: Diffusion Deception Detector

Project for DATA302, Basic Computer Vision and Applications.

We aim to find the best model structure to distinguish diffusion-generated fake images from real ones.

[report](https://github.com/HyezNee/3D/blob/main/report.pdf)

![img](https://github.com/HyezNee/3D/blob/main/figure1.png)



---


🎆 v1. 3d_project.ipynb: code for testing pretrained models. no fine-tuning. [convnext]

🥔 v2. potato_soup.ipynb: code for fine-tuning pretrained models and testing. [convnext]
* modify `MY_DIR` in 'Get Dataset'
* add models name, input_size, classifier_in_feature in 'Env'. **DO NOT ERASE any model's info**
* save your best model and the result. 

v3. trainandtest.ipynb: code with training and testing code with real images and fake images. [convnext]
* modify `MY_DIR` in 'Get Dataset'
* add models name, input_size, classifier_in_feature in 'Env'. **DO NOT ERASE any model's info**
* save your best model and the result. 
* wandb

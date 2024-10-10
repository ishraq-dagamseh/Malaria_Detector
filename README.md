# Malaria_Detector

In this project, we built a robust classifier that able to identify the malaria disease from medical images. I used image dataset to malaria disease, this images belong to two classes: parasitized and uninfected classes.  parasitized-> images contains malaria disease, while uninfrcted -> images with no malaria ( healthy images)

Many steps applied in this project: 
1. imported required libraries.
2. uploaded data.
3. read data
4. visualized some samples of images.
  and this some of them: A. paratisized images:
![image](https://github.com/user-attachments/assets/1fb655f4-c93e-4f95-bbde-5d3ee0dcaab2)
 And this is from uninfected class:
![image](https://github.com/user-attachments/assets/18fb3fbb-db62-4657-a579-8603453db7ef)

As we noticed, the difference between two images the dark color in the pink part of image, that represent the disease in the medical images.
6. explored the data
   in this step we noticed that we had balanced data, as we see in the next images:
   ![image](https://github.com/user-attachments/assets/10d5f0fc-8a70-488d-aba3-dddb0546a5ff)
7.  pre-process data using data augmentation
8. built Custome CNN model
9. compiled and optimized the model
10. fit the model with data
11. evaluate the performance of the model
12. plot the performance.

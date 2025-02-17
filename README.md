# Malaria_Detector

In this project, I built a robust classifier that able to identify the malaria disease from medical images. I used image dataset to malaria disease, this images belong to two classes: parasitized and uninfected classes.  parasitized-> images contains malaria disease, while uninfrcted -> images with no malaria ( healthy images).
train dats included ( 12480) images for two classes, while the test data included ( 1300) images for each class.


Many steps applied in this project: 
1. imported required libraries.
2. uploaded data.
3. read data
4. visualized some samples of images.
# And this some of them: A. paratisized images:

![image](https://github.com/user-attachments/assets/1fb655f4-c93e-4f95-bbde-5d3ee0dcaab2)

# And this is from uninfected class:
 
![image](https://github.com/user-attachments/assets/18fb3fbb-db62-4657-a579-8603453db7ef)

As we noticed, the difference between two images the dark color in the pink part of image, that represent the disease in the medical images.

5. explored the data
In this step we noticed that we had balanced data, as we see in the next images:
   
  ![image](https://github.com/user-attachments/assets/10d5f0fc-8a70-488d-aba3-dddb0546a5ff)
  
6.  pre-process data using data augmentation
7. built Custome CNN model
8. compiled and optimized the model
9. fit the model with data
10. evaluated the performance of the model
11. plot the performance.


# I used kaggle notebook because it offer accelerators, and I used GPU T4X2, to accelarate training process.
# python version 3, tensorflow library to build model

# libraries used in this project were:
1. numpy
2. pandas
3. seaborn.
4. matplotlib.
5. os
6.  glob
7.  tensorflow
8.  sklearn

# Results:

Best results were accuracy 95%, with training in 30 epochs, the next image show how the model performance was during the training and testing stages. i think its a good trial but we can make more improvements.

![image](https://github.com/user-attachments/assets/f77d9550-8f0b-400a-8364-32b7a6ea8413)



#Deploymant using gradio on HuggingFace
![image](https://github.com/user-attachments/assets/870ddd76-c56c-494d-831a-30a0f43d2a50)


you can try it from this Link: [IshraqTariq92/Malaria_Detector](https://huggingface.co/spaces/IshraqTariq92/Malaria_Detector)






# Weather Image Recognition using Deep Learning

**Project team members:**

Member1 Name: Dheeraj Sannidhi

Member1 Email: dsbck@umsystem.edu

Member2 Name: Navya Gujjarlapudi

Member2 Email: ng4xv@umsystem.edu

Member3 Name: Nishitha Reddy Boyapati

Member3 Email: nbhcr@umsystem.edu

Member4 Name: Nikhileshwar Reddy Papagiri

Member4 Email: npwmx@umsystem.edu


**Video Link:**  https://umsystem.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=578756e7-dc00-4b4a-af37-ae90004c485c

**Project Highlights:**

1. In this project,we have built a convolutional neural network(CNN) model on a database containing 6862 images of 11 different weather conditions to  classify the image into its correct weather phenomena.

2. We have used the following dataset: https://drive.google.com/drive/folders/1gRZDAJguRdsmXZiK9s-JYIY8fh8q4Wi7?usp=sharing from the source: https://www.kaggle.com/datasets/fceb22ab5e1d5288200c0f3016ccd626276983ca1fe8705ae2c32f7064d719de?msclkid=933bcf6acf2111ec8c7fc588f5d612bd

3. We have build the model by following the architecture:[[Conv2D->relu]*2 -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Out

4. The accuracy and loss of the model is 72 % and 1.14 respectively.

5. The summary of the model can be seen below:

![image](https://user-images.githubusercontent.com/98193330/167321127-da81abd4-ebe2-40c6-afcf-8e05a802d1f3.png)

6. We have used gradio libraries for integrating GUI (https://gradio.app/image_classification_in_tensorflow/)
7. The below image displays the predicated output of the given image.
![image](https://user-images.githubusercontent.com/98193330/167321574-ae3191f5-3454-4990-a19f-7928531b9496.png)


The application is hosted on the gradio provided servers which will expire in 72 hours. We will be updating the link before the presentation if expired.
Application hosted at: https://42777.gradio.app/



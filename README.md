# Gender-and-Age
Use Video Camera and identify people in the feed there age and gender

Description: The program would compare the images from a video camera with a model and predict the faces with the corresponding gender and age. The model is a work-in-progress and been trained with mostly American images, so it isn’t the most accurate model for people.

Important: This program isn’t the most accurate program because of the lack of understanding and time trying to improve the program along with the inaccuracy of the model itself. This was originally planned to use for the model of facial measurement to add another column for gender but with the inaccuracy, the idea was scrapped from the main program. 

Program Flow:
The program would begin with declaring the models that would be used, age_net and gender_net. But you would need two for each, a prototxt and caffemodel for each individual type of model. The second method would use the webcam similarity towards the facial recognition, it would capture the image using the cascade classifier, convert the images to gray scale and detect the faces. Once the faces has been detected, boxes would be drawn for the faces with the matching image and gender base on the model. A text would appear with the writing for the age and gender. Tge main method would set the video capture dimension and the age list and gender, to categorize the faces with. 

NOTE: This program us some existing Models that I did not create. Also this program is not 100% accurate and does not tell age/gender 100% accurately. This program was also ran on a Macbook wtih a webcam. There are also 2 model titled "age_net.caffemodel" and "gender_net.caffemodel" were two big in file size and not be able to be uploaded into this repository. 

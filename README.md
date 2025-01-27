# COVID-19-Chest-X-ray-Image-Classification

Coronavirus, also known as COVID-19 is an illness which is caused by a virus that can spread from person to person. The symptoms can range from mild to severe illness. COVID-19 has resulted in countless numbers of lives lost, ruining multiple businesses all over the world and disrupting the global economy.

Challenges

•	We had our dataset in 2 different files (csv and image folder).
•	Csv had two columns: image id and label (whether the person is COVID positive or not)
•	The Image folder had images with id
•	With the help of macro in excel, we segregated COVID images from the ones that do not have COVID.


Explanation and Prediction
•	With the help of image processing tools, we read all the images and put them in an array. According to the challenge listed above, we separated the COVID positive images from the negative ones.
•	We reshaped the images.
•	After reshaping, we processed the images and analysed them. Since the images were three-dimensional (3D), we converted it into a two-dimensional (2D) array by flattening it.
•	We then resized it to 200 pixels.


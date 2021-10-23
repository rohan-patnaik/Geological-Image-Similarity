# Geological-Image-Similarity
An ML based solution to identify the k most similar images to a particular image of a stone.


The notebook is briefly divided into roughly 3 parts. (The 1st part is kinda not needed for the problem statement. Will update this part later.)

The first part is ML model building and applying it to the dataset after importing libraries and doing some train-test split.

The second part is to create images into vectors and feature selection for the said images.

Moving onto the third part. After this is done a chosen image is matched to all the images we have to find the "K" most similar images to it.

And after all this is done we try to display these closest images in our notebook.

Since there are no train and test datasets with 6 classes of data consisting approximately 30000 images we try to include every image in one dataset first of all


![image](https://user-images.githubusercontent.com/22250758/138548345-e5c15240-109a-4f83-98b7-caa8db0db430.png)



![image](https://user-images.githubusercontent.com/22250758/138548326-33b70d02-e807-4ce9-9121-99054637bdde.png)


Here we see the distribution of the data plotted below :

![image](https://user-images.githubusercontent.com/22250758/138548419-de24d592-4109-4370-b7c1-5efc3cf458b4.png)

For demo purposes we can start by displaying a tes image and then displayin the image most similar to it.

We do this by creating a similarity label in our dataset and extracting the best value by sorting it by measuring the cosin similarity for the test image to that of the whole dataset.

![image](https://user-images.githubusercontent.com/22250758/138550134-53f9df87-1550-42b8-bf35-b69e2c71bad7.png)


![image](https://user-images.githubusercontent.com/22250758/138550073-c6ea3aa7-3d19-40cc-ac4a-c1032f63a177.png)

![image](https://user-images.githubusercontent.com/22250758/138550089-db084e0c-997e-4b5f-b0ef-7554f5a93d6c.png)


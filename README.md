# LeedsButterfly

<h3>Create a model for LeedsButterfly Dataset.</h3>

   Hello everyone. My name is Ali Can SARIBOĞA. I would like to add this repository as the one I applied in the data science course I took in the 4th grade, I think it will be useful.
First, I would like to add the data set used in this project here.

<h5>Data Set</h5>
   You can access the original data set to which I used <a href="https://www.josiahwang.com/dataset/leedsbutterfly/" style="color: black; text-decoration: underline;text-decoration-style: dotted;">here</a>.
   You can access the original data set to which I used <a href="https://www.kaggle.com/datasets/veeralakrishna/butterfly-dataset" style="color: black; text-decoration: underline;text-decoration-style: dotted;">here</a>.

<h5>About The Data Set File System</h5>
   This data set consists of 10 classes and 832 images. There are descriptions, images, and segmentations folders in the data set. All images are under the images folder. In the Segmentations folder, patterns of butterfly images were used. I did not use segmentation in this project, but it can be used to increase the accuracy value.
 I modify some changes to the file system in this project. First, I merged the ".txt" files in the descriptions folder into a ".csv" file named classesNames.
   Secondly, I made changes in the Images folder. Here; I divided the images into test, train, and valid. In each folder I separated, I combined pictures from different classes in different folders and used the "COMMON NAME" names in the CSV file as the file name. This way, it was easier for me to introduce classes to the model.

<h5>Drive Links</h5>
   You can access the data set to which I applied the changes <a href="https://drive.google.com/drive/folders/1eUjSSjrQXpmCZ0UWqO70x1aOzzfXbvya?usp=sharing" style="color: black; text-decoration: underline;text-decoration-style: dotted;">here</a>.
   You can access the model I created <a href="https://drive.google.com/drive/folders/18G8E5PGQmD2qZqXZsEFoer-jFZdESqqz?usp=sharing" style="color: black; text-decoration: underline;text-decoration-style: dotted;">here</a>.

   I added the relevant codes to this repository. Since the work here was done with Google Colab, the relevant import operations and read operations were written accordingly. You can easily make changes according to your work. I wish everyone good luck.

You can contact and connect with me [here](https://www.linkedin.com/in/alicansariboga/).

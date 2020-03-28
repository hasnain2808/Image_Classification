# Image_Classification
All the code is available in the CV.ipynb file<br>
The pretrained model is by the name "model" ("note there is no extension to the name")
<br>
<br>
The initial a look at the dataset showed that the images are available in a folder and files having the names as links
<br>
The data set was loded in memory using numpy and pandas and resized to size (64,64,3)
<br>
The data generator uses data augmentation which helps increase the size of the dataset.<br>
The train set also includes labels of test images which was filtered out<br>
<br>
<br>
These two dictionaries are used to convert from labels to id and vice versa<br>

label_to_id = {'Food':0, 'Attire':1, 'Decorationandsignage':2, 'misc':3}<br>

id_to_label = {0: 'Food', 1:'Attire',2: 'Decorationandsignage',3: 'misc'}<br>

<br>
Various models were tried out starting with a simple one layer cnn and one fully connected layer that showed very high bias<<br>

The final four models  are showed in the notebook
<br>

The model 2 was used to generate the submission.csv

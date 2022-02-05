# Collection of Natural Language Processing Projects
Work in progreess of some personal projects in NLP - for learning process and implementation of the concepts learned in the University. 

## 1. Image Caption Generator
Here I have downloaded Flicker Dataset from: <a href="https://github.com/goodwillyoga/Flickr8k_dataset">https://github.com/goodwillyoga/Flickr8k_dataset</a> <br>
In the data folder, there are 2 subfolders: One containing all the images(testing + training images). Another folder contains text files with training images ids *[Flickr_8k.trainImages.txt]*, testing images ids *[Flickr_8k.testImages.txt]* and descriptions (i.e captions) of training images *[Flickr8k.token.txt]*.
**Steps take for implementation:**<br>
1. First clean and format image-ids with captions data *[Flickr8k.token.txt]* in key value pairs. Key = Image-Id and Values = Generated Captions array.
2. Create a vocabulary of words from the above generated captions array.
3. Then load training image ids from *[Flickr_8k.trainImages.txt]* and seperate images from the whole dataset into just training images.
4. Then load testing image ids from *[Flickr_8k.testImages.txt]* and seperate images from the whole dataset into just testing images.
5. Add respective captions to the training set of respective images. And, also add **'startseq'** and **'endseq'** tokens on stat and end of captions for each image.
6. Further project is in progress...

## 2. Text Summarization
To be implemented....
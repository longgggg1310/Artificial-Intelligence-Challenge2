# Artificial-Intelligence-Challenge2
![12](https://user-images.githubusercontent.com/74718176/148668997-7c22a42f-d092-4f5f-9179-c99f7a6c6552.png)

We will make a union design to keep the picture out of the RNN/LSTM and consequently have the option to prepare the piece of the neural organization that handles pictures and the part that handles language independently, utilizing pictures and sentences from isolated preparing sets. </br >
To encode our picture highlights we will utilize move learning. There are a ton of models that we can utilize like VGG-16, InceptionV3, ResNet, and so forth
We will utilize the inceptionV3 model which has the most un-number of preparing boundaries in contrast with the others and furthermore beats them.We will make use of the inceptionV3 model which has the least number of training parameters in comparison to the others and also outperforms them (CNN as encoder and RNN as a decoder). </br >
Glove model will be used to increase the accuracy because it uses Word embedding - a in the method of the most common variable variable of the words of the top from the head to for the learning model. It helps us easily to train the model.This mapping will be done in a separate layer after the input layer called the embedding layer. </br >

Greedy Search will be used to choose the best words to accurately define the image. </br >

For training our LSTM model, we predefine our label and target text. For example, if the caption is “a man in a black shirt is standing in front of a crowd.”, our label and target would be as follows –

Label – [ , A,  man,  in,  a, black,  shirt, is ,standing, in ,front, of, a, crowd  . ] </br >
Target – [A,  man,  in,  a, black,  shirt, is ,standing, in ,front, of, a, crowd,  ., ]


## About the dataset
Various datasets are utilized for preparing, testing, and assessment of the picture subtitling strategies. The datasets contrast in different viewpoints, for example, the quantity of pictures, the quantity of subtitles per picture, organization of the inscriptions, and picture size. Three datasets: Flickr8k, Flickr30k, and MS COCO Dataset are prominently utilized. </br >

In the Flickr8k dataset, each picture is related with five unique inscriptions that portray the elements and occasions portrayed in the picture that were gathered. By partner each picture with numerous, autonomously created sentences, the dataset catches a portion of the phonetic assortment that can be utilized to depict a similar picture.


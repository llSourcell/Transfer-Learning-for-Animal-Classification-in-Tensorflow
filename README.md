<hr>
# Transfer Learning for Animal Classification in Tensorflow

The code in this notebook is in response to Siraj's Image classifier Challenge which can be found [here](https://www.youtube.com/watch?v=cAICT4Al5Ow).

We intend to perform image classification on the Animals on the Web dataset. The dataset contains images of 10 different classes of animals. However we would  perform a binary classification task to classify Leopard and Giraffe images using Transfer Learning in Tensorflow.

The images of these 2 classes of animals are stored in the sub-folders Leopard and Giraffe inside the folder Animals_data.

The accuracy obtained via transfer learning using Google's Inception-v3 model was 96%.


## Dataset

Reference :<br>
[Animals on the Web](http://tamaraberg.com/papers/berg_animals.pdf) <br>
[Tamara L. Berg](http://tamaraberg.com/), [David A. Forsyth](http://luthuli.cs.uiuc.edu/~daf) <br> 
*Computer Vision and Pattern Recognition (CVPR), 2006* <br>

I've already included the preprocessed dataset in the Github repository.  But if you want to use other animal images for classification, here's how I did it : 

Leopard and Giraffe images can be found in the [**Animals on the Web**](http://tamaraberg.com/animalDataset/index.html) Dataset. You can download the Giraffe images (size : 38 MB) from [here](http://tamaraberg.com/animalDataset/tarfiles/giraffe.tar.gz) and the Leopard images (size : 49 MB) from [here](http://tamaraberg.com/animalDataset/tarfiles/leopard.tar.gz). I used only the positive samples of these images which can be saved using the `possamples.html` file. Just extract the two tar files in a folder. Then open the `possamples.html` for giraffe and leopard in the browser, right click anywhere in the browser window and choose *Save as*. Save the webpage and automatically all the positive samples of the giraffe and leopard images would be stored in the directory you specified.


##Requirements

* Tensorflow
* PIL (for preprocessing the dataset)

##Usage 

Just run and follow the Ipython Notebook which contains the documented code.

<hr>


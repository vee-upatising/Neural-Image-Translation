# Neural Image Translation
Using [Cycle GANs](https://arxiv.org/abs/1703.10593) to perform Unpaired Image to Image Translation with Tensorflow


![results](https://i.imgur.com/ASDqrJH.jpeg)

* ## Requirements
  * Python 3
  * Keras
  * Tensorflow == ```2.5.0```
  * Sklearn
  * Skimage
  * Numpy
  * Matplotlib
  * PIL

* ## Documentation
  * ## [Cycle GAN Training](https://nbviewer.org/github/vee-upatising/Neural-Image-Translation/blob/main/Cycle%20GAN%20Training.ipynb)
      * This script is used to define the Cycle GAN class, train the two Generative Adversarial Networks, generate samples, and save the model at every epoch interval.

      * ### User Specified Parameters:

* ## Generated Training Sample
![Training](https://i.imgur.com/GsIg9wx.png)

* ## Results
  *  ### [Horse to Zebra](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_ganhorse2zebra)
 ![horse2zebra](https://i.imgur.com/GBeZUsT.jpg)
   *  ### [Zebra to Horse](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_ganhorse2zebra)
 ![zebra2horse](https://i.imgur.com/AAKS1zL.jpg)
   *  ### [Winter to Summer](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_gansummer2winter_yosemite)
 ![winter2summer](https://i.imgur.com/idCqJuL.png)
   *  ### [Summer to Winter](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_gansummer2winter_yosemite)
 ![summer2winter](https://i.imgur.com/daww4kv.jpg)
   *  ### [Map to Satelite](https://www.tensorflow.org/datasets/catalog/cycle_gan#cycle_ganmaps)
 ![map2satelite](https://i.imgur.com/0LiLVeH.jpg)

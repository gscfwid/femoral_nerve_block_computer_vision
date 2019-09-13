# femoral_nerve_block_computer_vision
The dataset and scripts of the paper--Doi: 10.21037/atm.2019.08.61

We applied the U-NET framework on segmentation of ultrasound guided femoral nerve block images. The area on the image to inject local anesthetic was marked by anesthesiologists. With supervised learning, the model can automatically recognize the interest area.

We held the codes on the [google colabratory](https://colab.research.google.com/drive/1rkGuUPwE1pC7evUMiq8WrgDY0sr13Nx6). Don't forget to turn on the GPU acceleration when running it. Our dataset of ultrasonic IMAGEs was uploaded in this repository.

The data flow pipeline was compiled by Keras with backend of Tensorflow. All processings were coded by python 3.6 with necessary modules.

We refered to [Åmdal-Sævik's codes](https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277) and here we express our gratitude.

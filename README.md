# Digikala-color-classification
This repository is dedicated for a presentation Tensorflow data pipelines which can be found 
[here](TF_data_piplines_slides.pdf).
The original code repo can be found [here](https://www.kaggle.com/masouduut94/digikala-products-color-classification)

# Dataset

![image](images/data.jpg)
The dataset can be found in [this](https://www.kaggle.com/masouduut94/digikala-color-classification) kaggle repository.

I recommend you take a look at [slides](TF_data_piplines_slides.pdf) to follow up with latest awesome tools that 
tensorflow has provided to boost up the performance in the training and evaluation pipeline. 

![slides](images/1.PNG)

This code implements these tools in tensorflow:
- Extract hsv histogram, use it as features and train sklearn classifiers.
- Use tf.data as data generator and practice some of useful methods.
- Use Tensorboard to track metrics like accuracy, precision, loss, auc-roc curve and etc.
- Save confusion matrix plot and GradCam output (using tf-explain) in tensorboard images to get better insights about models.
- How to apply numpy operations on tf.data using tf.py_function.
- Use albumentations for more strong and professional augmentations.


We will add the following tools soon:
- Custom loop
- tf.snapshot
- tf.data.distribute
- tf.function
- XLA
- Mixed Precision
- Synchronous Training

If you like the content, please consider supporting it in these ways:
- Upvote the code in [kaggle](https://www.kaggle.com/masouduut94/digikala-products-color-classification)
- Upvote this github repo.

Refrences:

- [Many thanks to Alireza Akhavanpour and his insightful slides](https://github.com/Alireza-Akhavan/tf2-tutorial)
- [A survey on Image Data Augmentation for Deep Learning](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-019-0197-0)
- [Albumentation github repository](https://github.com/albumentations-team/albumentations)
- [imgaug github repository](https://github.com/aleju/imgaug)
- [How to apply keras ImageDataGenerator into segmentation task?](https://github.com/zhixuhao/unet/blob/master/data.py)
- [Keras how to generate data on the fly](https://stanford.edu/~shervine/blog/keras-how-to-generate-data-on-the-fly)
- [Violence detection and classification on kaggle violence dataset (use case of keras.utils.sequence)](https://www.kaggle.com/masouduut94/violence-detection-and-classification)
- [Stackoverflow question: tf.data vs keras.utils.sequence performance](https://stackoverflow.com/a/59492947/6118987)
- [Inside TensorFlow: tf.data + tf.distribute](https://www.youtube.com/watch?v=ZnukSLKEw34)
- [Scaling Tensorflow data processing with tf.data (TF Dev Summit '20)](https://www.youtube.com/watch?v=n7byMbl2VUQ)
- [Kaggle code for image classification on Digikala products (Use case of tf.data)](https://www.kaggle.com/masouduut94/digikala-products-color-classification)
- [Tensorflow docs | tf.function tutorial](https://www.tensorflow.org/guide/function)
- [TowardsDataScience: Eager Execution vs. Graph Execution in TensorFlow: Which is Better?](https://towardsdatascience.com/eager-execution-vs-graph-execution-which-is-better-38162ea4dbf6)
- [Tensorflow docs for XLA](https://www.tensorflow.org/xla)
- [Youtube tensorflow XLA tutorial](https://www.youtube.com/watch?v=kAOanJczHA0)
- [Tensorflow docs | Mixed Precision and how to apply it in custom loop.](https://www.tensorflow.org/guide/keras/mixed_precision)
- [NVIDIA Developer How To Series: Mixed-Precision Training](https://www.youtube.com/watch?v=i1fIBtdhjIg)
- [Icons from:  https://www.flaticon.com/authors/linector](https://www.flaticon.com/authors/linector)


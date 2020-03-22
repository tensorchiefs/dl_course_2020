
# Deep Learning (CAS machine intelligence, 2020) 

This course in deep learning focuses on practical aspects of deep learning. We therefore provide jupyter notebooks ([complete overview of all notebooks](https://github.com/tensorchiefs/dl_course_2020/tree/master/notebooks) used in the course).

For doing the hands-on part on your own computer you can either install anaconda ([details and installation instruction](anaconda.md)) or use the provided a docker container ([details and installation instruction](docker.md)).

To easily follow the course please make sure that you are familiar with the some [basic math and python skills](prerequistites.md). 

## Info for the projects
You can join together in small groups and choose a topic for your DL project. You should prepare a poster and a spotlight talk (5 minutes) which you will present on the last course day. To get some hints how to create a good poster you can check out the links that are provided in <a href="https://www.dropbox.com/s/u1f6mqk4pc3uhxe/poster-guidelines.pdf?dl=1">poster_guidelines.pdf</a> 

If you need free GPU resources, we might want to follow the [instructions how to use google colab](co.md). Help for preparing a hdf5 file from your images you can be found in the <a href="https://github.com/tensorchiefs/dl_course_2018/blob/master/notebooks/data_prep.ipynb"> example Notebook.</a> 

Examples for projects from the DL course 2018 and 2019 can be found [here](projects.md).

**Fill in the Title and the Topic of your Projects until 24.03.2020 [here](https://docs.google.com/spreadsheets/d/18VFrPbKq3YSOg8Ebc1q1wGgkfgaWl7IkcCClGEDGj6Q/edit#gid=0)**

## Other resources 
We took inspiration (and sometimes slides / figures) from the following resources.

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is by the tensorchiefs and covers the increasingly popular probabilistic approach to deep learning .

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course.

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).

* More TensorFlow examples can be found at [dl_tutorial](https://github.com/oduerr/dl_tutorial/tree/master/tensorflow/) 

* Another applied course in DL: [TensorFlow and Deep Learning without a PhD](https://cloud.google.com/blog/big-data/2017/01/learn-tensorflow-and-deep-learning-without-a-phd)

## Dates 
The course is split in 8 sessions, each 4 lectures long. 

| Day  |      Date    |      Time    |
|:--------:|:--------------|:---------------|
| 1        | 18.02.2020|13:30-17:00
| 2        | 25.02.2020|13:30-17:00
| 3        | 03.03.2020|13:30-17:00
| 4        | 10.03.2020|13:30-17:00
| 5        | 17.03.2020|13:30-17:00
| 6        | 24.03.2020|09:00-12:30
| 7        | 31.03.2020|13:30-17:00
| 8        | 07.04.2020|09:00-12:30

## Syllabus (might change during course)

| Day  |      Topic and Slides    |      Additional Material    |		Exercises and homework  |
|:----------------:|:-----------------------|:----------------------------|:--------------------------------------|
| 1        | Introduction, Fully Connected Networks, Keras [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/01_Introduction.pdf) |[Network Playground](https://playground.tensorflow.org/) |[01_simple_forward_pass](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/01_simple_forward_pass.ipynb)<br>[02_fcnn_with_banknote](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/02_fcnn_with_banknote.ipynb)
| 2        |Looking back at fcNN, working with loss curves, convolutional neural networks [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/02_CNN.pdf) |[Understanding convolution](https://towardsdatascience.com/intuitively-understanding-convolutions-for-deep-learning-1f6f42faee1)|[03_fcnn_mnist](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/03_fcnn_mnist.ipynb)<br>[04_fcnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/04_fcnn_mnist_shuffled.ipynb)<br>[05_cnn_edge_lover](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/05_cnn_edge_lover.ipynb)<br>[06_cnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/06_cnn_mnist_shuffled.ipynb)<br>[07_cifar10_norm](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/07_cifar10_norm.ipynb)
| 3        |Tricks of the trade in CNNs [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/03_CNN.pdf)|[Understanding CNNs](http://cs231n.github.io/understanding-cnn)|[08_cifar10_tricks](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/08_cifar10_tricks.ipynb)<br>[09_1DConv](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/09_1DConv.ipynb)
| 4        |Details: Backpropagation in DL, MaxLike-Principle [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/04_Details.pdf)|TODO|[10_linreg_tensorflow](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/10_linreg_tensorflow.ipynb)<br>[11_backpropagation](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/11_backpropagation.ipynb)<br>[maxlik](https://github.com/tensorchiefs/dl_book/blob/master/chapter_04/nb_ch04_01.ipynb)
|**no lecture due to corona crisis**         |**no lecture due to corona crisis**|**no lecture due to corona crisis**|**no lecture due to corona crisis**
|6     |Probabilistic Models [slides Part 1] (https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/05_Probabilistic_Modeling_part1.pdf)|TODO|TODO
| 7        |TODO|TODO|TODO
| 8        |TODO|TODO|TODO

Tensorchiefs are Oliver Dürr, Beate Sick and Elvis Murina.

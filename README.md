# Human Action Recognition and Ergonomic Risk Assessment 

This is a step by step implementation of the method we used for human action recognition and ergonomic risk assessement in "Toward Ergonomic Risk Prediction via Segmentation of Indoor Object Manipulation Actions Using Spatiotemporal Convolutional Networks" paper that is accepted to the [CASE conference 2019](https://www.ieee-ras.org/component/rseventspro/event/1488-case-2019-international-conference-on-automation-science-and-engineering) and the IEEE Robotics and Automation Letter.

### Dataset

The UW-IOM dataset can be found [here](https://data.mendeley.com/datasets/xwzzkxtf9s/draft?a=c81c8954-6cad-4888-9bec-6e7e09782a01).

The TUM Kitchen dataset can be found [here](https://ias.in.tum.de/dokuwiki/software/kitchen-activity-data).

### Requirements

This code has been tested on a workstation running Windows 10 operating system, equipped with a 3.7GHz 8 Core Intel Xeon W-2145 CPU, GPU ZOTAC GeForce GTX 1080 Ti, and 64 GB RA

* TensorFlow, Keras (1.1.2+)

* Tested on Python 3.6

### File structure

If you creat a directory for this project and copy the code in the "Code" folder and the UW-IOM dataset in the "data" folder the rest of the required directories will be generated automatically. 

```
.\Code
.\Data
```

## Acknowledgments

* The TCN code was built on the code by [Colin Lea](https://github.com/colincsl/TemporalConvolutionalNetworks) presented in the [Temporal Convolutional Networks for Action Segmentation and Detection](https://arxiv.org/abs/1611.05267).

## Citation
Please cite the following article if you found the code and UW-IOM dataset useful:

"Parsa et al. “Toward Ergonomic Risk Prediction via Segmentation of Indoor Object Manipulation Actions Using Spatiotemporal Convolutional Networks”, IEEE Robotics and Automation Letter, 2019"
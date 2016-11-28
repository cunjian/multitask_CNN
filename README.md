### Introduction

A project that applies CNN to simultaneously predict facial attributes, including gender and age. This can be extended to more attributes.

This multitask CNN has been trained on scratch from Celebrity dataset released by CUHK.  After 500000 iterations, it reaches 84.21\% for age classification and 95.47\% for gender classification.

### Evaluation Results


![alt text](hhttps://github.com/cunjian/multitask_CNN/blob/master/evaluate/demo_result.jpg "Logo Title Text 1")

![alt text](https://github.com/cunjian/multitask_CNN/blob/master/evaluate/041_result.jpg "Logo Title Text 1")

### Usage

Install caffe and dlib, run the following command

python predict_vanilla_fd_attribute.py ../train_multitask/model/_iter_500000.caffemodel family3.jpg

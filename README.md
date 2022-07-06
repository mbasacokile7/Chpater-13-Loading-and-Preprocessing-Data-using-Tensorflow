# Chpater-13-Loading-and-Preprocessing-Data-using-Tensorflow
Summary of Chapter 13 from "Hands On Machine Learning with Scikit Learn and Tensorflow" by Geron Aurilien

This chapter focused on how to preprocess data using Tensorflow, buidling efficient data preprocessing pipelines and also how to use the Data API as well as other Tensorflow services like TF.Tranform.

The notebook in the REPO coverd the following sections

## The Data API

Tensorflow has a great DATA API that allows users to first create `tf.datasets` and also to build use multiple transformations on these datasets. Thus, one can build efficient data preprocessing pipelines, that can improve performance and reduce training time. In addition, methods of fully utilising hardware are covered, such as the number of threads to use on your CPU, as well as prefetching the data, to fully utilise the GPU.

## TFREcords

The textbook goes in depth on TFRecords. But for the personal purposes, I did not cover this section.Again the book is an excellent resource to understand TFRecords and also to get your hands dirty working with thme.

## Preprocessing Input Features

In any ML Project, the data you are dealing with will probably have categorical feaetures or text or something along those lines. Thus standard num,erical operations to preprocess this type of data cannot work. That being said, there is a need to for preprocessing techniques that are tailored for type of features we are faced with.

The notebook covers:

### Encoding Categorical Features using One-Hot Encoding

### Encoding Categorical Features using Embeddings

### Using Keras Preprocessing Layers

Finally, there is a brief discussion on other Tensorflow projects like

## Tensorflow Transform (TF.TRansform)

## Tensorflow Datasets (TFDS Project)




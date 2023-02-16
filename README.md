# In-sensor reservoir computing for language learning via two-dimensional memristors

<p align="center">
  <img width="500" alt="Fig3A" src="https://user-images.githubusercontent.com/68064510/219300996-4da2ce3d-18a6-4590-adeb-956fe1de8602.png">

This repository is an implementation of the readout layer in this [paper](https://www.science.org/doi/10.1126/sciadv.abg1455). 

<p align="center">
  <img width="500" alt="Fig5" src="https://www.science.org/cms/10.1126/sciadv.abg1455/asset/649efb24-511e-492c-9abc-e92a18b37592/assets/graphic/abg1455-f5.jpeg">
</p>

## Requirements

To install requirements:

```
pip install -r requirements.txt
```

## A. Data preprocessing
In 'Data_preprocessing.ipynb', you can model neuron output currents with Gaussian distributions of varying standard deviations. 

We don't share the data of neuron output currents.

## B. Linear classification
You can simulate the linear classification in 'Linear_classification.ipynb'.
Supervised learning models like single-layer perceptron, support vector machine, and logistic regression were used for the readout layer.

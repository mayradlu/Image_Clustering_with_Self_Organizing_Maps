# Image Clustering with Self-Organizing Maps (SOMs)

## Project Overview
This project explores the application of Self-Organizing Maps (SOMs) for clustering images across three distinct datasets. SOMs are a type of unsupervised neural network used for dimensionality reduction and data visualization. By organizing data into a topological map, SOMs help identify intrinsic relationships and latent patterns within complex visual datasets

## Data Description 
**Fashion-MNIST**
* Size: 70,000 images (60,000 for training and 10,000 for testing).
* Description: Grayscale images, 28x28 pixels, representing 10 classes of clothing items (shirt, pants, sweater, dress, coat, shoes, t-shirt, sneakers, bag, boots).
<p align="center">
  <img src="https://github.com/user-attachments/assets/f801ae74-6ee1-4a98-aac2-e505870d0db4" alt="imagen" width="400">
</p>


**Satellite Images of Mexico**
* Size: 1,636 images.
* Description: High-quality satellite photos showing environments such as Water, Forest, City, Crops, Desert, and Mountain.
* [Database](https://drive.google.com/drive/folders/1yGcbQ6B4GoTHrbmBPHRFVF1dMFafQrpN?usp=sharing) 
<p align="center">
  <img src="https://github.com/user-attachments/assets/154c0dd6-7cc9-415d-a874-cdf7d1d93952" alt="imagen" width="400">
</p>


**Custom Images**
* Size: 2,500 images (500 per class).
* Description: Images captured from different angles and lighting conditions, showing a shoe, a cap, a cellphone, a pencil, and a book.
* [Database](https://drive.google.com/drive/folders/11RqS3AW_XcmWsf4wpP2AmGoQ8Ce1bNPo?usp=sharing)
<p align="center">
  <img src="https://github.com/user-attachments/assets/034ae7ba-14ab-4c45-b3ba-87d16ada8db5" alt="imagen" width="400">
</p>

## Theorical Framework
**Self-Organizing Maps** (SOMs) are an unsupervised learning algorithm developed by Teuvo Kohonen. SOMs map high-dimensional data onto a low-dimensional grid, preserving the topological structure of the input data. This means similar data points are placed closer together on the map, making SOMs effective for visualizing and clustering complex datasets.

**Key Concepts**
* Dimensionality Reduction: SOMs reduce the dimensionality of input data while maintaining their inherent relationships.
* Topological Mapping: The grid structure of SOMs reflects the similarities between data points, with neighboring neurons representing similar data.
* Adaptation: Neurons in the SOM adjust their weights based on input data, with the "winning" neuron and its neighbors updating their weights to better match the input.

## Results
**Fashion M-NIST** Efficient clustering was observed, with most neurons storing data from a single category. Similar classes, such as Sneakers and Ankle Boots, were grouped closely together


<p align="center">
  <img src="https://github.com/user-attachments/assets/d97dea2a-a60d-4c58-800c-2f61f88c7f48" width="200" />
  <img src="https://github.com/user-attachments/assets/c164f9b4-2f13-4811-b5d6-1c27fe8fa3d9" height=216 width="210" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e5d04073-1d42-4fff-a64e-a5bbf0d3eb90" width="200" />
  <img src="https://github.com/user-attachments/assets/e20297d0-2fcd-4daf-9010-7d340f44c56c" width="200" />
</p>


**Satellite Images of Mexico** Despite the higher complexity and fewer images, the SOM was able to group some classes effectively, although there was more overlap between categories compared to Fashion-MNIST.
<p align="center">
  <img src="https://github.com/user-attachments/assets/7c7059e3-91ff-4a7e-b7f7-6b738585b1f0" width="200" />
  <img src="https://github.com/user-attachments/assets/a5c4315a-5eed-4be5-9a2a-be3ae2df3faa" height=216 width="200" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/a5e20840-38ec-4763-87a1-b7e20e99a601" width="200" />
  <img src="https://github.com/user-attachments/assets/b54189bf-9837-42ff-a10e-bc4595373247" height=220 width="200" />
</p>



**Custom Images** The dataset's simplicity and smaller size allowed for effective clustering. However, the "Shoe" class showed some dispersion, likely due to the diversity of shoes in the images.
<p align="center">
  <img src="https://github.com/user-attachments/assets/08e44df7-1e0c-4460-bcc3-53d09e317554" width="200" />
  <img src="https://github.com/user-attachments/assets/b2b8347e-3efe-4b2c-8548-22c6d3f895ba" height=216 width="200" />
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/9e6c2222-1e26-4f61-992e-7052f786d8b9" width="200" />
  <img src="https://github.com/user-attachments/assets/2e64d8c9-9a1e-458c-93a2-1e9b36ddab85" height=220 width="200" />
</p>







    

# Image Caption Generator

The objective of the project is to predict the captions for the input image. The dataset consists of 8k images and 
5 captions for each image. The features are extracted from both the image and the text captions for input. The features 
will be concatenated to predict the next word of the caption. CNN is used for image and LSTM is used for text. BLEU Score 
is used as a metric to evaluate the performance of the trained model.

## Data Source
We use the dataset available at https://www.kaggle.com/datasets/adityajn105/flickr8k

## Neural Network

- VGG16 Network
- CNN-LSTM Network

## Model Architecture

Here's, the visual representation of the model architecture, including the input and output shapes of each layer.

![architecture](https://github.com/prernasingh05/CodeClause_Image_Caption_Generator/assets/98377151/cc9e69f7-858b-430d-bf5c-d58ac7dc7eab)

## Generating Captions Example

### Example - 1

![img predict 1](https://github.com/prernasingh05/CodeClause_Image_Caption_Generator/assets/98377151/b4b2bacb-6e27-40d2-a588-872c3570df0d)

### Example - 2

![img predict 2](https://github.com/prernasingh05/CodeClause_Image_Caption_Generator/assets/98377151/b1f9fbdb-2f32-4607-8fc4-9eb2d7b88f20)


### Evaluation

**BLEU-1 Score :** 0.544

**BLEU-2 Score :** 0.319

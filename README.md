# image-caption-generator-using-PyTorch

Built an image caption generator from scratch using CNN and LSTMs. Dataset used in this project is famous Common Objects in Context (COCO) dataset which is a
large scale object detection, segmentation and captioning dataset.

## Project Objective:

To generate captions for the unseen samples of images. Here we have combined CNN and LSTM model in am encoder-decoder framework, trained them jointly and used the model
trained to generate captions for an image. 

## Flow:

1. Download the dataset
2. Wrote our own custom pytorch dataset loader
3. Built a vocabulary based on the caption text dataset
4. Resized images, applied transformations such as reshaping, normalizing, random cropping, and horizontal flipping.
5. Defined CNN-LSTM model architecture along with loss function and optimization schedule.
6. Ran the training loop for 3 hrs for 3 epochs on Colab T4 GPU.
7. Ran the inference on the trained model.

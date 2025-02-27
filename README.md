# Capture Matching Project

## 1. Introduction
This project aims to analyze tree images to identify similar images of the same tree over different periods. The notebook focuses on finding the k most-similar neighbors for each image.

## 2. Current Notebook Contents
- **Data Preprocessing**: Processes the dataset by loading image URLs and metadata, and saving the images locally.
- **Image Embedding**: Each image is converted into an embedding vector using a pre-trained ResNet model.
- **Similarity Calculation**: Cosine similarity and geospatial distance are calculated between the images to find how similar they are based on both visual and spatial features.
- **K Neighbors (K-NN)**: The notebook then finds the k-nearest neighbors for each image, helping to group similar tree sapling images together.

## 3. Task Objectives
- More preprocess and clean the image dataset.
- Cluster similar images together(using K-means/hierarchical/etc. clustering).
- Visualize images in the same cluster to make sure they are similar.

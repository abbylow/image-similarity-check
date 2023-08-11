# Find similar images and calculate the similarity

## Step 1: Use input image to find similar images from Google 
`lens-image-search.ipynb` 
Given a folder of input images that you intend to search, run this script to download all the similar images in the first page of searched result.

## Step 2: Calculate the similarity score between the input image and google search returned images 
`image-similarity.ipynb` 

Reference: https://huggingface.co/blog/image-similarity

Pre-processing: resize and crop the images to 224x224 -> convert to Tensors and normalize

Embeddings: use Transformer to encode the images and get embeddings

Compute similarity: use cosine similarity to calculate the scores


### Note that a majority of images found through Google and on the Internet are copyright protected. 

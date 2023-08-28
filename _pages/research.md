---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from: 
  - /research
  - /research.md
---

{% include base_path %}

Currently, my research focus on the application of data science, statistics and machine learning methods in solving real-world problems. Below are the details of my research experience.

## Research Experience

* **Effect of Fumigation on Microbiomes in Soil** , Jan 2023 - Present
  * This is my first research project. The project is about analyzing the effect of a toxic fumigant (Methyl Bromide) on the microbiome communities in the soil through various statistical inference and microbiome network inference techniques. The dataset is a high-dimensional, sparse and large dataset. The goal is to identify if there is change in microbiome communities caused by the fumigation.
  * The following analysis were performed:
  * Data Visualization using Non-metric Multidimensional Scaling (NMDS) and Heatmap with agglomerative clustering to identify the patterns between fumigated and non-fumigated samples.
  * Using permutational multivariate analysis of variance (PERMANOVA) to test the hypothesis if there is difference between fumigated and non-fumigated samples.
  * Constructed linear model to identify the relationship between alpha diversity (Shannon index and Inverse Simpson Index) with several predictors (fumigation, treatment, etc). 
  * Build microbial networks using Glasso, Correlation and Dissimilarity matrix, CARlasso algorithm and conducted network inference to identify the relationship between OTUs and response variables.
  * Advisor: [Claudia Solís-Lemus](https://crsl4.github.io/pages/about.html), PhD student Evan Gorstein.
  * [Github Link](https://github.com/evangorstein/fumigation_study)
  * Paper and further analysis in progress

* **Wildlife Sound Identification**, July 2023 - Present
  * The project is about identifying wildlife species based on their sound. The sound data is collected by soundscape in tropical rainforest. The goal is to develop a pipeline to be able to identify where the sound is, and to be able to identify the species. 
  * Developed a pipeline to process the sound data and their labels (bounding boxes and classes). Used librosa to perform fast fourier transform on the sound data into spectrogram. 
  * Currently developing a Faster R-CNN model to identify the bounding boxes of the sound from the spectrogram data.
  * Advisor: [Claudia Solís-Lemus](https://crsl4.github.io/pages/about.html).
  * [Github Link](https://github.com/tianyi0216/Soundscape_Project) (Most work is still in progress)

* **Deep Learning for Medical Image Classification** , Feb 2023 - May 2023
  * This is my second research project. The project is about identify aggressive tumor features in Renal cell carcinoma using learning-based CV techniques. The previous group has extracted image slices with most learnable features (non-zeros on the image matrix). My job is to build and imporve a deep CNN to classify the images (high risk or low risk). 
  * Developed, and optimized a convolutional neural network using PyTorch for feature extraction from images. The original CNN and training process provided by the previous group has a testing accuracy of 60% and issue with overfitting. I have improved the CNN by adding more layers and dropout layers to prevent overfitting. I also optimized the training process and used batch normalization. The testing accuracy has been improved to 90-95%.
  * Evaluated the CNN performance using various techniques including compare against a random model, permutation tests, evaluate the performance on different datasets, confusion matrix, etc.
  * Advisor: [Dane Morgan](https://directory.engr.wisc.edu/mse/Faculty/Morgan_Dane/), collaborated with Yuqing Wang and Ankit Joju
  * Full Project Description: [link](https://skunkworks.engr.wisc.edu/projects/) (You might need to scroll down to see the project description for this specific project I am working on.)


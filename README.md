# Handwritten Music Symbol Recognition

## Overview
This repository contains the implementation and findings of a project focused on handwritten music symbol recognition. The project explores various datasets, introduces and implements Convolutional Neural Networks (CNNs), applies transfer learning, and evaluates an ensemble model inspired by the paper "An ensemble of deep transfer learning models for handwritten music symbol recognition" by Paul et al. The primary goal is to enhance the accuracy of symbol classification in musical notations.

## Project Structure

1. **Introduction**
   - Overview of the OMR problem and its significance.
  
2. **OMR Datasets**
   - Examination of datasets, with a focus on symbol classification.
   - Generation of 2D images from raw handwritten music symbol data.

3. **Applying a CNN**
   - Implementation of a baseline CNN model for symbol classification.
   - Data augmentation techniques to enhance model performance.

4. **Transfer Learning**
   - Exploration of transfer learning using pre-trained models (DenseNet161, GoogleNet, ResNet50).
   - Fine-tuning and evaluation of transfer learning models.
   
5. **Simulating the Paper**
   - Replication of the ensemble model proposed in the paper by Paul et al.
   - Evaluation of ensemble accuracy and comparison with the paper's reported results.

6. **Enhancing the Presented Method**
   - Exploration of alternative ensemble methods to improve accuracy.
   - Introduction of a two-level hierarchy ensemble approach.
   - Comparative analysis of ensemble methods.

7. **Discussion**
   - Summary and discussion of model performances.
   - Comparison of achieved accuracies with the proposed method in the paper.



## Results
The project introduces and evaluates various models, demonstrating advancements in accuracy compared to the baseline and the paper's proposed method.

Three models exceeded the accuracy of the proposed model in the paper, showcasing the effectiveness of the introduced approaches.

## References
The project draws inspiration from and acknowledges the following sources:
- [Paper on Ensemble Transfer Learning](https://link.springer.com/article/10.1007/s00521-022-06741-3)
- [OMR Datasets](https://apacha.github.io/OMR-Datasets/)
- Additional references provided for background and context.

Feel free to explore the detailed findings and implementations in the respective sections of the repository!

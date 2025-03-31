# Text Recognition using Optical Character Recognition (OCR) Libraries

## Introduction
The goal of our project is to utilize multiple different OCR libraries, and compare these libraries using a handwritten [Kaggle Dataset](https://www.kaggle.com/datasets/naderabdalghani/iam-handwritten-forms-dataset/data) that contains hundreds of directories with a typed paragraph, followed by their handwritten version (each handwritten version is different). These libraries will then be compared based on different benchmarks for the recognition abilities to see which is superior.

### Libraries Used:
- PyTesseract
- Keras-OCR
- EasyOCR

### Benchmarks Compared Upon:
- Accuracy percentage of each libraries recoginition when compared to the ground truth output of the paragraph
- Time cost for each library to process and read each of the handwritten texts

## Further Study
The Keras-OCR library was proven to be the least efficient and accurate for our dataset, so we further trained the pre-trained model to improve the recognition of both the typed and handwritten text, to improve the overall comparison.
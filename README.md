# Animal Recognition with Custom CNN

## Introduction
This project aims to provide a deeper understanding of Convolutional Neural Networks (CNNs) while building an animal recognition system. It addresses common challenges faced by those dealing with image data, such as organizing data into train and test sets. The implementation uses TensorFlow, a popular deep learning library.

## Getting Started
If you're running this code on a Kaggle Notebook, make sure to adjust the accelerator to GPU or TPU for faster processing. Follow these steps:
1. Click on Runtime
2. Select Change Runtime Type
3. Change it to GPU or TPU

## Steps of Model Creation
1. **Environment Setup**: Includes data download and unzipping.
2. **Importing Libraries**: Necessary libraries are imported, including TensorFlow for deep learning tasks.
3. **Understanding Data Structure**: The notebook explores the folder structure of the image dataset.
4. **Data Preparation**: Images are read, resized, and transformed into dataframes.
5. **Model Building**: A custom CNN model is constructed using TensorFlow's Keras API.
6. **Compilation**: The model is compiled with appropriate loss and optimization functions.
7. **Model Fitting and Evaluation**: The model is trained on the prepared data, and its performance is evaluated.
8. **Conclusion**: The notebook concludes with insights gained from model training and suggestions for further improvements.

## Libraries Used
The project utilizes various Python libraries for data processing, data pipeline creation, prediction, and deep learning tasks. Some notable libraries include:
- TensorFlow (2.3.1)
- Matplotlib
- NumPy
- Pandas
- OpenCV
- Scikit-learn

## Conclusion
The project demonstrates the importance of kernel size in CNNs and provides insights into building an effective animal recognition model. It highlights the impact of different kernel sizes on model performance and recommends using a kernel size of (3,3) for optimal results.

Feel free to explore the code and adjust parameters for further experimentation. Don't forget to upvote the kernel if you find it useful!

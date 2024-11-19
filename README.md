# CNN-Based Cat and Dog Image Classifier  

This project demonstrates the development of a binary image classifier to distinguish between cats and dogs using Convolutional Neural Networks (CNN). Leveraging a dataset comprising 20,000 training images and 5,000 validation images, two models were built and evaluated for performance.  

![image](https://github.com/shivamratti13/cat-dog-classification/blob/main/Report/cat%20with%20pretrained.png)
![image](https://github.com/shivamratti13/cat-dog-classification/blob/main/Report/dog%20with%20pretrained.png)

## Project Overview  

1. **Custom CNN Architecture**:  
   - Designed and implemented a CNN model from scratch using the Keras library.  
   - Included convolutional layers, pooling layers, and fully connected layers with ReLU activation.  
   - Employed dropout layers to prevent overfitting.  
   - Achieved a classification accuracy of **77.8%**, showcasing effective model design for a from-scratch approach.  

2. **Pretrained Xception Model**:  
   - Fine-tuned the pretrained Xception model from Keras, leveraging transfer learning.  
   - Replaced the top layers to suit binary classification.  
   - Achieved a remarkable accuracy of **99.05%**, demonstrating the power of transfer learning in image classification.  

## Key Highlights  

- **Data Preprocessing**: Images were resized, normalized, and augmented with techniques such as rotation and flipping to enhance model generalization.  
- **Evaluation Metrics**: Models were assessed using accuracy, loss values, and confusion matrices.  
- **Comparison of Approaches**: Showcased the performance difference between a custom-built CNN and a state-of-the-art pretrained model.  

This project exemplifies the application of both custom CNN design and transfer learning for efficient image classification. It serves as a foundation for building scalable and high-performing deep learning models.  


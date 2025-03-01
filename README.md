# Blood-Cell-Classification-with-Deep-Learning
This project analyzes and trains neural networks for blood cell image classification using the Breast Histopathology Images dataset from Kaggle. Four models were implemented: three CNN architectures and one VGG-based model. Performance was evaluated based on accuracy and loss, optimizing image size, batch size, and epochs for better convergence.

# Breast Histopathology Images - Neural Network Analysis for Blood Cell Classification  

## Authors  
- **Alexandra Perdomo López**  
- **Angie Paola Giraldo Ramírez**  

## Project Description  
This project analyzes and trains different neural network architectures for the classification of blood cell images using the **Breast Histopathology Images** dataset from Kaggle. The goal is to compare the performance of different Convolutional Neural Network (CNN) models and the VGG architecture in terms of accuracy and loss function.  

## Implemented Models  
Four neural network models were developed and trained as follows:  

### **Model 1: CNN Architecture**  
- **2 convolutional layers** with **32 filters** each  
- **Accuracy:** 25%  
- **Loss function value:** 1.38  

### **Model 2: CNN Architecture**  
- **4 convolutional layers** with **64 filters** each  
- **Accuracy:** 67%  
- **Loss function value:** 0.7  

### **Model 3: CNN Architecture**  
- **4 convolutional layers** with **32 filters** each  
- **Accuracy:** 68%  
- **Loss function value:** 0.67  

### **Model 4: VGG Architecture**  
- **3 convolutional blocks**, each containing **two convolutional layers**  
- **Filters per block:** 32, 64, and 128  
- **Accuracy:** 25%  

## Key Findings  
- Increasing the number of convolutional layers to **4 layers** improved model accuracy.  
- The best-performing model was **Model 3**, which used **4 layers of 32 filters**, achieving **68% accuracy** while reducing the loss function value to **0.67**.  
- **Fully Connected layers (Dense layers)** played a crucial role in performance improvement.  
  - Model 2 used **256 units** in the last Dense layer.  
  - Model 3 used **64 units with ReLU activation**, improving accuracy.  
- **CNN architectures** performed better than **VGG** for blood cell classification.  

## Optimization Strategies  
- **Image resizing** was applied to optimize training time.  
- **Batch size variations** were tested to improve model fitting for each architecture.  
- **Increased number of epochs** was used to achieve an optimal convergence value for the loss function and accuracy.  

## Conclusion  
The results suggest that increasing the number of convolutional layers and adjusting filter sizes can significantly improve model accuracy while reducing loss. Additionally, CNN-based architectures showed superior performance compared to the VGG model in this specific classification task.  



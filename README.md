# A Deep Learning Approach for Monkeypox and Other Skin Lesion Classification

## Name of Authors
- **Kazi Shaharair Sharif**  
  Department of Computer Science  
  University of South Dakota  
  [kazi.sharif@coyotes.usd.edu](mailto:kazi.sharif@coyotes.usd.edu)  
  GitHub: [KSharif](https://github.com/KSharif)

- **Mohammad Navid Nayyem**  
  Department of Computer Science  
  University of South Dakota  
  [mohammadnavid.nayyem@coyotes.usd.edu](mailto:mohammadnavid.nayyem@coyotes.usd.edu)  
  GitHub: [navidnayyem](https://github.com/navidnayyem)

- **Jahirul Islam**  
  Department of Computer Science  
  University of South Dakota  
  [jahirul.islam@coyotes.usd.edu](mailto:jahirul.islam@coyotes.usd.edu)  
  GitHub: [imjahir](https://github.com/imjahir)
## Authors Contribution
- **Kazi Shaharair Sharif** - Data Preprocessing, Literature Review, Methodology, Results Analysis
- **Mohammad Navid Nayyem** - Advanced Preprocessing, Validation, Statistical Analysis, Visualization
- **Jahirul Islam** - Model Training, Data Collection, Formal Analysis, Workflow Diagrams

## Introduction
Monkeypox is a zoonotic disease with increasing prevalence, and its skin lesions closely resemble those of conditions like chickenpox and cowpox, making accurate diagnosis challenging. This project presents an AI-driven framework for classifying monkeypox and related skin lesions using advanced deep learning techniques.

## Features
- Utilizes the **Mpox Skin Lesion Dataset Version 2.0**
- Implements **8 deep learning models**: EfficientNetB5, ResNet50, ResNet101, MobileNet, Xception, DenseNet121, NasNetMobile, and InceptionV3
- **5-fold cross-validation** for robust performance evaluation
- **Extensive data augmentation** to enhance model generalization
- Optimized for **resource-constrained environments**
- Achieves over **90% accuracy and F1 scores** with EfficientNetB5 and MobileNet

## Dataset
- **Source**: Mpox Skin Lesion Dataset Version 2.0 ([Kaggle](https://www.kaggle.com/datasets/joydippaul/mpox-skin-lesion-dataset-version-20-msld-v20))
- **Categories**:
  - Mpox
  - Chickenpox
  - Measles
  - Cowpox
  - Hand-foot-mouth disease
  - Healthy skin
- **Data Augmentation**:
  - Random rotation
  - Scaling
  - Cropping
  - Brightness/contrast adjustment
  - Gaussian noise
  
## Model Implementation
### Pre-trained Deep Learning Models Used:
1. **EfficientNetB5** - High accuracy with computational efficiency
2. **ResNet50 & ResNet101** - Residual connections for deep feature extraction
3. **MobileNet** - Lightweight and suitable for mobile devices
4. **Xception** - Depthwise separable convolutions for feature learning
5. **DenseNet121** - Enhanced gradient flow and feature reuse
6. **NasNetMobile** - Optimized through neural architecture search
7. **InceptionV3** - Factorized convolutions for improved efficiency

### Training Details
- **Optimizer**: Adam (learning rate: 0.001, dynamic scheduler)
- **Loss Function**: Categorical Cross-Entropy
- **Batch Size**: 16
- **Epochs**: 50 (early stopping applied)

## Performance Evaluation
**Evaluation Metrics**:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Visualization
- **Model Accuracy vs. Loss Curves**
- **Confusion Matrix** for each model
- **T-statistic & P-values** analysis for model comparisons

## Clinical Relevance
- Enables **automated dermatological diagnostics**
- Suitable for **low-resource environments** due to lightweight models
- Can aid **early detection and disease prevention**
- Helps clinicians make **informed decisions** efficiently

## Future Work
- Address **class imbalance** with advanced augmentation
- **Ensemble methods** for improved classification
- **Integration with clinical metadata** for enhanced decision-making
- **Deployment on mobile & edge devices** for real-world use

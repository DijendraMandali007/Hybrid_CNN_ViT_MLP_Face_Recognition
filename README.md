# Hybrid CNN-ViT-MLP Face Recognition

A hybrid deep learning model combining CNN (ResNet-50), Vision Transformers (ViT), and MLP to enhance facial recognition performance in terms of accuracy, robustness, and efficiency.

## Features
- Local feature extraction using CNN (ResNet-50)
- Global context via Vision Transformers
- Final classification using MLP
- Improved recognition under occlusion and lighting variation

## Model Architecture
1. **CNN Backbone**: Extracts spatial facial features.
2. **Vision Transformer**: Captures long-range dependencies.
3. **MLP Classifier**: Performs identity classification.

## Dataset and Evaluation
- Trained and evaluated on large-scale facial datasets.
- Outperforms standalone models like FaceNet, ResNet-50, and pure ViTs.

## How to Use
Upload the notebook to your Colab environment or run it locally with the required dependencies (`torch`, `transformers`, `tensorflow`, etc.).

## Contact
**Dijendra Sai Sri Bharath Mandali**  
📧 dijendramandali@gmail.com  

## Citation
If you use this code or refer to this project, please cite:

Mandali Dijendra Sai Sri Bharath, Menthem Poornesh Reddy,  
*"Advancing Face Recognition with Hybrid CNN-ViT-MLP: A Comparative Study"*,  
**International Journal for Research in Applied Science & Engineering Technology (IJRASET)**, Volume 13, Issue III, March 2025.  
DOI: [10.22214/ijraset.2025.67487](https://doi.org/10.22214/ijraset.2025.67487)

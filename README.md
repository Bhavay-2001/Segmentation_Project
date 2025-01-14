
# Segmentation Project: Human Figure Segmentation

This project focuses on image segmentation using deep learning techniques in PyTorch. The objective was to develop a model capable of accurately segmenting human figures from the background in images. 

## Key Components

### 1. Dataset
- **Source**: The dataset, specifically designed for human segmentation, was obtained from [here](https://github.com/parth1620/Human-Segmentation-Dataset-master.git).
- **Description**: The dataset includes images and corresponding segmentation masks. The masks identify regions of interest, such as humans versus the background.

### 2. Model Architecture
- **Approach**: A deep learning architecture (U-Net) suitable for segmentation tasks was employed.

### 3. Preprocessing and Data Augmentation
- **Techniques**: Data preprocessing and augmentation were critical to the project’s success.
- **Tools**: Libraries such as Albumentations were used to apply transformations like:
  - Scaling
  - Rotations
  - Flips
- **Benefits**: These techniques increased the dataset's effective size and improved the model's robustness to variability in image conditions.

### 4. Training
- **Framework**: PyTorch was used to handle deep learning tasks efficiently.
- **Hardware**: The model was trained on a GPU to speed up computation.
- **Loss Function**: Cross-Entropy Loss and Dice Loss were utilized to optimize the model’s performance.
- **Optimizer**: The Adam optimizer was employed for its adaptive learning rate capabilities.

### 5. Evaluation
- **Metrics**:
  - Intersection over Union (IoU)
- **Purpose**: These metrics were used to assess the model’s performance in segmenting human figures from backgrounds.

### 6. Results
- **Performance**: The model demonstrated satisfactory results on the test set.
- **Visualization**: Predictions were visualized alongside ground truth masks to highlight the model’s effectiveness.

## Challenges and Learnings

### Challenges
1. Variability in the dataset, such as differences in lighting conditions and human poses.
2. Limited dataset size, which required augmentation to improve generalization.

### Learnings
- Enhanced understanding of convolutional neural networks (CNNs) and their application in image segmentation tasks.
- Improved skills in optimizing models for better performance and generalization.




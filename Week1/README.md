# Week 1 - Garbage Classification Project

## Summary

- Added dataset for 6 garbage classes (~1000+ images per class)
- Dataset is currently imbalanced — will handle in future weeks
- Added initial Jupyter Notebook (`week1.ipynb`) for model development

## Libraries Used

- `numpy`: Array and numerical operations
- `matplotlib`, `seaborn`: Visualizations and plotting
- `tensorflow`, `keras`: Deep learning model building
    - Used **EfficientNetV2B2** for transfer learning
- `sklearn.utils.compute_class_weight`: Handling class imbalance
- `sklearn.metrics`: Evaluation metrics (confusion matrix, classification report)
- `gradio`: Interactive web interface for model testing

## Current Status

- Dataset uploaded locally (excluded from GitHub for size)
- Model notebook in progress
- Gradio interface planned after initial model training

## Next Steps

- Address class imbalance (augmentation / class weights)
- Train model and evaluate accuracy
- Build Gradio interface for demo


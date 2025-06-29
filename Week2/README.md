# Week 2 - Garbage Classification Project

## ✅ Summary of Work

- Loaded dataset from Kaggle into train, validation, and test sets using `image_dataset_from_directory`
- Visualized class distributions and calculated the percentage representation of each class
- Computed class weights to handle imbalance using `compute_class_weight` from `sklearn`
- Applied data augmentation using `RandomFlip`, `RandomRotation`, `RandomZoom`, and `RandomContrast`
- Built a custom CNN model using **EfficientNetV2B2** as a base with frozen early layers
- Compiled the model using Adam optimizer and added **EarlyStopping** to prevent overfitting
- Trained the model for 15 epochs and visualized training vs validation accuracy/loss
- Printed model summaries and performance plots

## 📊 Libraries Used

- `TensorFlow`, `Keras` for model building
- `EfficientNetV2B2` for transfer learning
- `sklearn` for class weighting and evaluation
- `matplotlib` for visualizing performance and class distribution
- `Gradio` (installed, integration to be done next week)

## 📝 Next Steps

- Evaluate the model on the test set with confusion matrix and classification report
- Export and integrate the trained model with Gradio for interactive predictions
- Optimize hyperparameters and explore regularization techniques

# SCT_ML_3
1. Data Preprocessing:

Loaded and processed cat and dog images from the Kaggle dataset.
Extracted HOG features and created a structured dataframe with labels for model training.
2. Model Training and Evaluation:

Built an SVM model using scikit-learn, employing a linear kernel for initial training.
Split the data into training and testing sets, evaluated the model using accuracy, precision, and recall metrics.
3. Parameter Optimization:

Utilized grid search to find optimal parameters, including the percentage of principal components and the choice of SVM kernel (linear, RBF, poly, sigmoid).
Identified the best-performing configuration: 90% of principal components and the RBF kernel, achieving an accuracy of approximately 67.57%.
4. Visualization and Interpretation:

Visualized model performance using a confusion matrix, providing insights into true positive and true negative predictions.
Concluded the project, emphasizing the significance of parameter tuning and feature selection for enhancing classification accuracy.
Project Outcome:

Accuracy: ~67.57%
Best Parameters: PCA (90% components), SVM Kernel (RBF)
Conclusion: The optimized SVM model effectively classified cats and dogs images, showcasing the importance of fine-tuning parameters. This achievement sets the stage for future advancements in image recognition and computer vision applications.

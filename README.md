# Feature Selection for predicting diabetes using Particle swarm optimization

This project implements a machine learning model for predicting **diabetes mellitus** using advanced feature selection techniques. We utilize **Particle Swarm Optimization (PSO)**, **Improved PSO (IPSO)**, and **PSO with Local Search (PSO-LS)** to optimize feature selection, aiming to enhance the accuracy of the model and reduce computational complexity.

### Key Features:
- **PSO, IPSO, and PSO-LS** for efficient and optimized feature selection
- **Random Forest** and **XGBoost** classifiers for prediction
- Performance evaluation against standard models, showing accuracy improvements
- Use of the **Pima Indians Diabetes Dataset** for training and testing

### Objective:
The primary objective of this project is to demonstrate how optimization algorithms (PSO variants) can be applied to improve the performance of machine learning models in predicting diabetes, particularly by reducing the number of features without compromising accuracy.

### Dataset:
The project uses the **Pima Indians Diabetes Dataset**, a widely used dataset in medical machine learning tasks that includes features like **pregnancies**, **glucose levels**, **blood pressure**, and more to predict the presence of diabetes.

### Classification Models:
We employ Random Forest and XGBoost classifiers to predict diabetes, both of which are popular and powerful machine learning algorithms known for their accuracy and robustness. The models are optimized by selecting the most relevant features using PSO, IPSO, and PSO-LS, resulting in improved performance over standard feature selection methods.

This project enhances the traditional PSO by introducing IPSO, which integrates genetic algorithm parameters for more efficient local search and improved feature selection. Additionally, the PSO-LS approach refines the global search of PSO with a local search technique, making the feature selection process even more effective in identifying the best subset of features.


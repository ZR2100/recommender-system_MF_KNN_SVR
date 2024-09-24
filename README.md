
# Recommender System Project

This project implements various recommender system algorithms, including KNN, SVM, Decision Tree, and Matrix Factorization. The main focus is on Matrix Factorization for providing personalized movie recommendations.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Algorithms Implemented](#algorithms-implemented)
- [Matrix Factorization](#matrix-factorization)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project explores different algorithms for building a recommender system. The primary goal is to compare the performance of various methods and highlight the effectiveness of Matrix Factorization.

## Dataset
The project uses the [MovieLens dataset](https://www.kaggle.com/datasets/shubhammehta21/movie-lens-small-latest-dataset) for training and evaluating the recommender system.

## Algorithms Implemented
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree**
- **Matrix Factorization**

## Matrix Factorization
Matrix Factorization is the main focus of this project. It involves decomposing the user-item interaction matrix into lower-dimensional matrices representing latent factors of users and items.

### Key Steps:
1. **Data Preparation**: Encoding user and movie IDs, creating the rating matrix.
2. **Normalization**: Centering ratings around the mean for each movie.
3. **Model Training**: Using TensorFlow to optimize the cost function.
4. **Evaluation**: Assessing the model using RMSE, MSE, MAE, R2 score, and relative MAE.

## Evaluation Metrics
- **Root Mean Squared Error (RMSE)**
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R2 Score**
- **Relative MAE**

## Results
The results section should include a summary of the performance of each algorithm, with a focus on the Matrix Factorization model. Include plots of training and validation losses, and a comparison of evaluation metrics.
Results Table
 MAE	   RMAE     MSE	   RMSE	 Algorithm
0.2554	0.8965	1.2781	1.1305	KNN
0.3224	1.1316	2.1155	1.4545	DT
0.2405	0.8444	1.1382	1.0669	SVR
0.0642	0.0963	0.0078	0.08855	MF
![image](https://github.com/user-attachments/assets/c4dda873-67bb-4958-9c43-e1155dad565d)

## Installation
To run this project, you need to have Python and the following libraries installed:
- numpy
- pandas
- scikit-learn
- tensorflow
- matplotlib

You can install the required libraries using:
```bash
pip install numpy pandas scikit-learn tensorflow matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/recommender-system-project.git
```
2. Navigate to the project directory:
```bash
cd recommender-system-project
```
3. Run the main script:
```bash
python main.py
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


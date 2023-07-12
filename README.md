# Heart Disease Prediction Using K-Nearest Neighbors (KNN) Approach

This repository hosts a machine learning-based classification model for heart disease prediction. The model uses the K-Nearest Neighbors (KNN) algorithm, a popular and effective method in medical diagnosis for its simplicity and precision. This project varies the K value between 1 and 21 to determine the optimum K for the highest accuracy.

## Repository Contents

- `HeartDiseasePrediction.ipynb`: This Jupyter notebook contains all the code used in this project. It details the process from initial data preprocessing, exploratory data analysis, model building, hyperparameter tuning, to final prediction.

- `heart_disease_dataset.csv`: This CSV file is the primary dataset used for the project. It includes 14 medical and demographic features related to heart disease.

## Dataset Description

The dataset contains 14 parameters which include:

1. Age: age in years
2. Sex: 1 = male; 0 = female
3. Chest pain type: 0, 1, 2, 3
4. Resting blood pressure: in mm Hg on admission to the hospital
5. Serum cholesterol: in mg/dl
6. Fasting blood sugar: > 120 mg/dl, 1 = true; 0 = false
7. Resting ECG results: 0, 1, 2
8. Maximum heart rate achieved
9. Exercise-induced angina: 1 = yes; 0 = no
10. ST depression induced by exercise relative to rest
11. Peak exercise ST segment: 1 = upsloping; 2 = flat; 3 = downsloping
12. Number of major vessels: 0-3 colored by fluoroscopy
13. Thalassemia: 3 = normal; 6 = fixed defect; 7 = reversible defect
14. Target: 1 or 0 

## How to Use

1. Clone this repository to your local machine.
2. Ensure that you have the necessary Python libraries installed (as mentioned in the Jupyter notebook).
3. Open the `HeartDiseasePrediction.ipynb` notebook using Jupyter and run the cells sequentially to reproduce the analysis and the model.
   
## Requirements

- Python 3.7+
- Jupyter Notebook
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, scikit-learn

**Note**: This project is intended for educational and informational purposes. While it aims to provide a high-accuracy classification model for heart disease prediction, it should not be used as a definitive medical diagnostic tool. Always consult with healthcare professionals for medical advice.

## Contributions

Contributions, issues, and feature requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Ritabrata Chakraborty-- ritabrata04@gmail.com

Project Link: https://github.com/[Your GitHub Username]/Heart-Disease-Prediction-Using-KNN-Approach

Feel free to contact me if you have any questions, or if you need further information about the project.

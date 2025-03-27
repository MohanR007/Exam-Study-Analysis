# Exam Study Analysis

This project analyzes the relationship between study hours, previous exam scores, and the likelihood of passing an exam. It uses a logistic regression model to predict whether a student will pass or fail based on their study hours and previous exam scores. Additionally, a Gradio interface is provided for easy interaction with the model.

## Features
- Data visualization of study hours and exam scores.
- Logistic regression model for prediction.
- Interactive Gradio interface for user input and prediction.

## Requirements
To run this project, you need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`
- `gradio`

You can install the required libraries using:
```bash
pip install numpy pandas matplotlib scikit-learn gradio
```

## Usage
1. Clone the repository or download the project files.
2. Ensure the dataset `student_exam_data.csv` is in the same directory as the notebook.
3. Open the `Exam_Study_Analysis.ipynb` notebook in Jupyter Notebook or Google Colab.
4. Run all cells to train the model and visualize the data.
5. Use the Gradio interface to input study hours and previous exam scores to predict the result.

## Gradio Interface
The Gradio interface allows you to input:
- **Study Hours**: Number of hours the student studied.
- **Previous Exam Score**: The score the student achieved in the previous exam.

The output will be either "Pass" or "Fail" based on the prediction.

## Example
To predict if a student who studied for 7 hours and scored 80 in the previous exam will pass:
1. Enter `7` for Study Hours.
2. Enter `80` for Previous Exam Score.
3. The interface will display the result as "Pass" or "Fail".

## License
This project is licensed under the MIT License.
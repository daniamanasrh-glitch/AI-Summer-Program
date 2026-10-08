# AI-Summer-Program
A 10-week journey to learn Artificial Intelligence through practical projects, machine learning, deep learning, and real-world applications.
About This Project:
This repository documents my progress throughout the 10-week AI Summer Program, including the concepts I learned, practical exercises, and projects I built along the way.
Weeks:
* Week 1: Data analysis with Pandas
* Week 2: Machine learning fundamentals
* Week 3: Neural networks
* Week 4: PyTorch and image classification
* Week 5: Machine learning with Kaggle
* Week 6: Transformers and Large Language Models
* Week 7: Project scoping and planning
* Week 8: Improving a machine learning model
* Week 9: Project documentation and presentation
* Week 10: Reflection and future planning
Capstone Project — UniPulse:
UniPulse — AI Student Voice is an AI project that analyzes student feedback and identifies the sentiment expressed in students’ comments.
The project uses Natural Language Processing (NLP) and Machine Learning to classify feedback as Positive, Neutral, or Negative.
Dataset:
The project uses a publicly available Student Feedback dataset containing 1,086 student comments and their sentiment labels.
The dataset contains two main columns:
* comments — the student’s feedback text.
* sentiments — the sentiment label.
Technologies:
* Python
* Pandas
* Scikit-learn
* TF-IDF
* Logistic Regression
* Matplotlib
* Seaborn
Method:
The project follows these main steps:
1. Split the dataset into training and validation sets using an 80/20 split.
2. Convert the text comments into numerical features using TF-IDF.
3. Train a Logistic Regression model on the training data.
4. Use the validation data to evaluate the model.
5. Apply class_weight="balanced" to give more attention to the underrepresented sentiment class.
6. Analyze the model using accuracy and a confusion matrix.
Results:
The Logistic Regression model achieved an accuracy of 69% on the validation set.
The model performed best on the Positive class, while the Neutral class was more challenging because it was underrepresented in the dataset.
After using class_weight="balanced", the model improved its ability to identify Neutral comments, while the overall accuracy remained at 69%.
Confusion Matrix:
The confusion matrix shows how the model classified the validation comments:
Actual	Negative	Positive	Neutral
Negative	64	21	6
Positive	18	75	10
Neutral	6	5	13
The model correctly classified 64 Negative, 75 Positive, and 13 Neutral comments in the validation set.
Example Prediction:
Input:
The teacher explains everything clearly and helps students.
Prediction:
Positive
Limitations:
* The dataset contains sentiment labels but does not include topic or issue categories.
* The Neutral class is underrepresented compared with the Positive and Negative classes.
* The current model achieves 69% validation accuracy and can be improved with further experimentation and data preprocessing.
Future Improvements:
* Improve the model’s accuracy.
* Add topic classification.
* Build an interactive dashboard.
Conclusion:
This project helped me apply AI and Machine Learning concepts to a real-world student feedback problem.

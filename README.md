# Text Warden
Comparison of Multiple Classification algorithms for detecting Toxic or HateFull Comment

## Problem Statement
The rampant occurrence of toxic comments on social media poses a serious issue, leading to cyberbullying and mental health concerns. Addressing this, this project aims to develop an machine learning solution for precise detection of hateful texts. By deploying multiple machine learning models and evaluating their performance, we seek to create a robust system that can be seamlessly integrated across diverse technologies to combat the escalating problem of online toxicity

## Challenge
In the context of a project aimed at developing a hate speech detection web application, I encountered a complex challenge involving the amalgamation and processing of multiple datasets. These datasets, originating from diverse sources, required careful integration to form a cohesive and representative dataset suitable for training a hate speech detection model.

## Task
My main tasks included merging diverse datasets with meticulous attention to ensure homogeneity. Subsequently, I applied rigorous data cleaning procedures to eliminate noise, correct errors, and remove irrelevant information. Additionally, I addressed class imbalance through upsampling, striving for a balanced distribution of hate speech and non-hate speech instances. I performed one-hot encoding on labels for categorical conversion, and conducted exploratory data analysis (EDA) to gain insights into the dataset's distribution, guiding subsequent decisions.

## Action
After the initial preparations, the project transitioned to model training using diverse algorithms like Random Forest, KNN, Naive Bayes, Logistic Regression, and Decision Tree. Each algorithm contributed to exploring solutions for hate speech detection. The pivotal moment arrived with the meticulous selection of the most effective model, gauged through metrics like accuracy, precision, recall, and F1-score. With the model in tow, attention shifted to crafting a web application, choosing Streamlit for its interactive and user-friendly interface. The implementation of the selected hate speech detection model within the web app aimed to provide users with a seamless and accessible experience.

## Result
The project wrapped up with a win – a hate speech detection model smoothly integrated into a user-friendly web app. Among our lineup of models, Random Forest stood out, rocking a solid 98% accuracy and a 97% F1 score. This performance sealed the deal for real-world reliability. We kept things user-friendly using Streamlit for the web app, making it easy to navigate. Choosing the Random Forest model turned out to be a smart move, and voila, we've got ourselves a web app that nails hate speech detection.
| Model | Accuracy | F1 Score |
| --- | --- | --- |
| Random Forest | 98% | 97% |
| Decision Tree | 96% | 96% |
| K-Nearest Neighbors | 89% | 88% |
| Logistic Regression | 87% | 88% |
| Naive Bayes | 71% | 77% |
| CNN | 68 % | 65% |

## Reflection
Navigating challenges associated with dataset integration and cleaning throughout the project underscored the pivotal role these aspects play in the success of machine learning applications. The insights derived from exploratory data analysis were instrumental in informing critical decisions at various stages, emphasising the significance of a data-driven approach. The decision to utilize Streamlit for web app development underscored the importance of thoughtful tool selection in enhancing user experience. This project not only showcased technical competencies in data preprocessing and machine learning but also highlighted the ability to make informed decisions grounded in comprehensive data analysis, a valuable skill set for future endeavors.

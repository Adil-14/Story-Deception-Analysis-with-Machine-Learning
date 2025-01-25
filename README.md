# **Story Deception Analysis with Machine Learning**

This project is all about classifying stories as true or false using machine learning techniques. The dataset includes audio recordings of people narrating personal experiences, some real and some made up.

## **What’s This About?**
The idea is to build a machine learning model that can figure out if a story is truthful or deceptive. The steps involved include:
- Working with audio recordings of stories.
- Pulling out useful features from the audio files.
- Training and testing machine learning models to see how well they perform.

## **Dataset**
The dataset has:
- **Audio files**: Each participant recorded 6 stories – 3 true and 3 false.
- **Labels**: Information like the language, whether the story is true or false, and ratings for the emotions in the story (like positivity and intensity).

> **Note**: The dataset isn’t included here for confidentiality reasons, but you’ll find details on how to get and prepare it in the project files.

## **How I Did It**
1. **Extracting Features**:
   - Audio features like pitch, tone, and energy were extracted using tools like Librosa.
   - If there were transcriptions, text-based features were also included.
2. **Preprocessing the Data**:
   - Standardizing the features to make everything uniform.
   - Making sure the dataset was balanced with an equal number of true and false stories.
3. **Training Models**:
   - Tried out different machine learning models, such as Support Vector Machines (SVM), Logistic Regression, and Random Forest.
4. **Evaluating the Results**:
   - Used metrics like accuracy, precision, recall, and F1-score to check how well the models performed.

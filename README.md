# TherapyTalk Assistant Siree

**Developer: Sireejaa Uppal**

Welcome to **TherapyTalk Assistant Siree**, a chatbot designed to support mental health by helping users manage stress, anxiety, depression, and other challenges. This chatbot uses natural language processing (NLP) techniques and a retrieval-based approach to provide accurate and helpful responses to users' questions.

## 📋 Table of Contents
- [Problem Statement](#problem-statement)
- [Existing Solutions](#existing-solutions)
- [Dataset Information](#dataset-information)
- [Attributes](#attributes)
- [Performance Evaluation](#performance-evaluation)
- [Data Exploration](#data-exploration)
- [Model Development](#model-development)
- [Demo](#demo)
- [Key Insights](#key-insights)
- [Future Plans](#future-plans)
- [References](#references)

## 🚩 Problem Statement
Mental health is crucial for overall well-being, impacting how we think, feel, and act. Managing stress effectively is essential for maintaining mental stability. **TherapyTalk Assistant Siree** is designed to assist users in managing their mental health by offering supportive communication.

## 💡 Existing Solutions
Current solutions include simple FAQ-based chatbots that respond only to predefined queries present in the dataset.

## 📊 Dataset Information
The dataset, sourced from Kaggle, includes queries related to mental health and corresponding responses. These queries address various mental health issues, and the responses provide guidance on managing these challenges.

## 🗂️ Attributes
- **Question_ID**: Unique identifier for each question
- **Questions**: Mental health-related questions
- **Answers**: Corresponding answers

## 📈 Performance Evaluation
Cross-validation methods like K-Fold Cross Validation are used to assess the model's accuracy during training. Robust testing ensures accurate responses from the chatbot.

## 🔍 Data Exploration
The dataset includes personal conversations formatted into a JSON file with intents and corresponding responses. Tokenization and lemmatization techniques are applied to clean and prepare the data.

## 🛠️ Model Development
TherapyTalk Assistant Siree employs a retrieval-based approach with a straightforward architecture of dense and dropout layers. The model is trained and the best-performing version is saved.

## 🎥 Demo
![Demo Image](demo_image_link)

## 📝 Key Insights
- Maintaining clean data is critical for chatbot and NLP tasks.
- For large datasets, vectorization and lemmatization enhance grammar understanding during training.
- Dividing data based on intents and entities improves the accuracy of chatbot predictions.

## 🚀 Future Plans
- Develop a mobile application to make TherapyTalk Assistant Siree more user-friendly and accessible.

## 📚 References
- [Applied Roots](https://www.appliedaicourse.com)
- [Mental Health FAQ for Chatbot](https://www.kaggle.com)
- [Creating a mental health resource chatbot with a deep neural network](https://alishaarora56.medium.com)
- [Karger Article](https://www.karger.com/Article/Fulltext/501812)

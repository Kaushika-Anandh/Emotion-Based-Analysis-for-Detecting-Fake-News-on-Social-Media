# Emotion-Based-Analysis-for-Detecting-Fake-News-on-Social-Media
Mini Project 

Proposed By : Kaushika A

Register Number : 212221230048

# Project Overview
## Introduction
In the digital era, the demand for reliable information is crucial, with microblogging and social media as primary sources. Dealing with misinformation and fake news on these platforms is challenging due to their deceptive nature. Misinformation in microblogs can evoke strong emotions, making it essential to detect algorithmically concealed falsehoods.
Managing users' heightened emotions requires effective solutions for accurate information classification.

The project addresses sarcastic and emotionally triggering journalism found in rumor posts. Combining sentiment analysis with misinformation detection improves the system's ability to verify accuracy and classify emotional sensitivity.

## Problem Statement 
Accurate classification and mitigation of misinformation on social media is the central problem addressed.
False information, often emotionally triggering, poses a significant threat to the reliability of information sources.
- **Project Goal:** Healthier Information Space
  - The project aims to contribute to a healthier information space by precisely categorizing news on social media.
  - It focuses on addressing issues such as emotionally triggering journalism in rumor posts.
- **Dynamic and Interconnected Content Nature**
  - Developing a model that accounts for the dynamic and interconnected nature of social media content is crucial.
- **Subjectivity and Nuances in Emotional Expression**
  - Emotions are inherently subjective, requiring a standardized set and inter-annotator agreement.

## Proposed Model 
The methodology employed follows a systematic and innovative approach. The foundation lies in the acquisition of labeled datasets containing accurate emotion annotations and reliable labels for fake news from reputable platforms. The project integrates advanced NLP techniques, leveraging sentiment analysis and LSTM-based detection models implemented using TensorFlow and Keras. The LSTM model undergoes training on tokenized and padded sequences of text, allowing it to capture intricate sequential patterns and nuances within the language.

The methodology extends to the incorporation of an emotion classifier, utilizing dictionaries for emotional intensity scores and word embeddings through Word2Vec. This combination enriches the system's ability to understand emotional contexts, providing a comprehensive analysis of news content. The systematic methodology employed guarantees a well-rounded, sophisticated system capable of addressing the challenges posed by misinformation on social media.

## Methodology

<p align="center">
<img src="https://github.com/Kaushika-Anandh/Emotion-Based-Analysis-for-Detecting-Fake-News-on-Social-Media/blob/main/FlowDiagram.PNG">
</p>

**Data Collection**
- This specific project requires two types of data:
- Data classifying Fake and Real News
- Data containing various forms of textual emotions

**Pre-processing**
- The datasets collected are removed from any punctuations, which hinder the Machine Learning models from processing the words properly.
- Then the words are converted to lowercase to reduce the processing complexity of the data. Finally, the stopwords are removed from the data. 

**Data Analysis**
- A word cloud is used to represent the frequency of data by the size of the words displayed in the plot. A bar chart of the data is also derived.

**Data splitting**
- The data is divided into training and testing sets, with training data used for model fitting and testing data for validating the model's classification accuracy. 
- This standard practice helps ensure the model generalizes well to unseen data, mitigating overfitting. 

**Fake News Detection Model Training and Model Selection** 
- Three models are tested and compared for fake news detection 
- Each model offers different approaches, ranging from traditional decision trees to advanced deep learning techniques, allowing for a comprehensive evaluation of their effectiveness.

**Metrics**
- The code evaluates model performance using accuracy, loss, and confusion matrices. 

**Emotion Classification** 
- The combined functionality of emotion scoring, classification, word embeddings, and text preprocessing results in a comprehensive system for emotion classification in text. 

**Model Combination** 
- By combining the trained models, the overall Fake News Detection system becomes more robust. 
- The LSTM Model contributes its proficiency in understanding textual structures, while the Emotion Classifier adds a layer of comprehension regarding the emotional context. 
- The integrated model is better equipped to distinguish between genuine and deceptive content by considering both structural patterns and emotional cues.

**Testing**
- The user is prompted to input a tweet, which is then tokenized and transformed into sequences using a pre-fitted tokenizer. 
- The tokenized and padded sequences are passed to the driver code, which combines the LSTM model with an Emotion Classifier based on pre-defined functions. 
- The output is the predicted news category (e.g., fake or real) and the associated emotion intensity. 
- The final results are then displayed.

## Output 

<p align="center">
<img src="https://github.com/Kaushika-Anandh/Emotion-Based-Analysis-for-Detecting-Fake-News-on-Social-Media/blob/main/Output.PNG">
</p>

## Conclusion

The project presents a groundbreaking methodology aimed at tackling the widespread problem of misinformation rampant on social media platforms. By synergizing advanced deep learning techniques with emotion analysis, the initiative seeks to establish a robust framework for distinguishing between trustworthy and misleading information. The ultimate goal is to contribute significantly to the creation of a safer and more reliable digital information environment. Looking ahead, the project envisions expanding its impact by analyzing entire threads of tweets, thereby addressing misinformation at a broader scale. Additionally, future plans include incorporating features such as sarcasm detection and emotional sensitivity level analysis, aiming to elevate the examination of higher-level blog posts for even greater accuracy and effectiveness.

## Future Enhancements

The project is characterized by the integration of cutting-edge Natural Language Processing (NLP) techniques, pushing the boundaries of technological sophistication to combat misinformation. A key feature involves real-time learning and continuous model updating, ensuring adaptability to evolving patterns of deceptive content. The initiative boasts enhanced multilingual support, recognizing the global nature of misinformation. A strategic aspect involves collaboration with social media platforms, fostering a synergistic approach to information integrity. Furthermore, the project delves into collaborative filtering and collective intelligence, exploring innovative ways to harness the power of collective user insights. Overall, the endeavor is underpinned by strategic enhancements, aiming for a lasting impact on the battle against misinformation in the digital landscape.

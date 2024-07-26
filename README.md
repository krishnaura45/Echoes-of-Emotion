<h1 align=center> Echoes of Emotion : Sentiment Analysis of Customer Reviews</h1>

**Echoes of Emotion** is a comprehensive project aimed at analyzing the sentiment of Amazon food reviews using various techniques, including VADER and a fine-tuned pretrained RoBERTa model. This project processes a large dataset of customer reviews, applies text preprocessing techniques, and compares the performance of different models to classify reviews into three sentiment categories: positive, negative, and neutral.

## Features

### Data Processing
- **Dataset**: Processes a large dataset of Amazon food reviews.
- **Text Preprocessing**: Applies techniques such as word tokenization, part of speech tagging, and named entity recognition.

### Sentiment Analysis Techniques
- **VADER**: Uses VADER for rule-based sentiment analysis.
- **RoBERTa**: Implements a fine-tuned pretrained RoBERTa model for context-aware sentiment scoring.

### Model Comparison
- **Performance Comparison**: Compares the performance of VADER and RoBERTa models in classifying sentiments.

### Implementation
- **Programming Language**: Python
- **Libraries Used**: NLTK, Scikit-learn, Hugging Face's Transformers

## Installation

Follow these steps to set up the project on your local machine:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/krishnaura45/Echoes-of-Emotion.git
    cd Echoes-of-Emotion
    ```

2. **Install required dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Download the dataset**:
    - Ensure you have downloaded the Amazon food reviews dataset from kaggle and placed it in the appropriate directory.

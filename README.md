# SDAIA Large Language Models Bootcamp 🤖

A collection of hands-on notebooks, exercises, and projects completed during the **SDAIA Large Language Models Bootcamp**.

This repository documents my practical learning journey across Machine Learning, Deep Learning, Natural Language Processing, Large Language Models, Fine-Tuning, Transfer Learning, and Retrieval-Augmented Generation.

---

## 📚 Topics Covered

- Machine Learning
- Neural Networks
- Functional vs Sequential Models
- Classification
- Convolutional Neural Networks
- MNIST Image Classification
- Natural Language Processing
- Text Cleaning and Preprocessing
- Customer Feedback Analysis
- Sentiment Analysis
- Text Generation
- GPT-2
- Text Summarization
- Model Fine-Tuning
- Transfer Learning
- Retrieval-Augmented Generation
- SMS Spam Classification

---

## 📂 Repository Structure

```text
SDAIA-LARGE-LANGUAGE-MODELS-BOOTCAMP/
│
├── 1-Functional_vs_Sequential.ipynb
│
├── 2-Iris_Specie_Detection.ipynb
├── 2-Positive_Stroke_Cases.ipynb
├── 2-Positive_Stroke_Cases2.ipynb
│
├── 3-Mastering_CNN_Architectures.ipynb
├── 3-MNIST_handwritten_digit_classification.ipynb
│
├── 4-Python_for_text_data_cleaning.ipynb
├── 4-Understanding_the_Customers_Feedback.ipynb
│
├── 5-Deep_sentiment_analysis.ipynb
├── 5-Text_Generation_GPT-2.ipynb
│
├── 6-Comparing_Text_Summarization_Pipelines.ipynb
├── 6-Model_Fine_Tuning.ipynb
│
├── 7-Transfer_Learning_with_RAG_Models.ipynb
│
├── 8-SMS_Spam_Classification.ipynb
│
├── healthcare-dataset-stroke-data.csv
├── iris.csv
├── sonar.csv
│
├── requirements.txt
└── README.md
```

---

# 🧠 Notebook Overview

## 1. Functional vs Sequential Models

Introduction to building neural networks using different model architectures.

Topics covered:

- Sequential API
- Functional API
- Neural network architecture
- Model building
- Model training
- Model evaluation
- Differences between Sequential and Functional models

---

## 2. Machine Learning Classification

Several classification problems are explored using structured datasets.

Projects include:

### Iris Species Detection

A classification model used to predict the species of an Iris flower based on its features.

Topics include:

- Data loading
- Data exploration
- Feature selection
- Model training
- Classification
- Model evaluation

Dataset:

```text
iris.csv
```

### Stroke Prediction

Machine learning models are used to analyze healthcare data and identify positive stroke cases.

Topics include:

- Data preprocessing
- Missing values
- Feature engineering
- Classification
- Imbalanced data
- Model evaluation

Dataset:

```text
healthcare-dataset-stroke-data.csv
```

Additional structured data experiments are also included using:

```text
sonar.csv
```

---

## 3. Convolutional Neural Networks

Exploration of Convolutional Neural Networks for image processing and classification.

Topics covered:

- CNN architecture
- Convolution layers
- Filters
- Feature maps
- Pooling layers
- Flatten layers
- Fully connected layers
- Image classification
- Model training
- Model evaluation

### MNIST Handwritten Digit Classification

A deep learning model is trained to classify handwritten digits from the MNIST dataset.

The model learns to recognize digits:

```text
0 1 2 3 4 5 6 7 8 9
```

This exercise demonstrates how neural networks can automatically learn visual patterns from image data.

---

## 4. Text Data Cleaning and Customer Feedback

Natural Language Processing starts with preparing raw text before sending it to a model.

### Python for Text Data Cleaning

Topics covered:

- Lowercasing
- Removing punctuation
- Removing unnecessary characters
- Tokenization
- Text normalization
- Stop word removal
- Cleaning noisy text
- Preparing text for NLP models

### Understanding Customer Feedback

Customer feedback is analyzed using Natural Language Processing techniques.

Topics include:

- Processing customer reviews
- Understanding text patterns
- Preparing text for analysis
- Extracting useful information from feedback
- Text classification concepts

---

## 5. Sentiment Analysis and Text Generation

## Deep Sentiment Analysis

Sentiment analysis is used to understand the emotional meaning of text.

Examples of sentiment classes include:

- Positive
- Negative
- Neutral

Topics include:

- Text preprocessing
- Tokenization
- Deep learning models
- Sentiment classification
- Model evaluation

---

## GPT-2 Text Generation

This notebook explores text generation using the GPT-2 language model.

GPT-2 is a transformer-based language model capable of generating text based on an input prompt.

Topics covered:

- Transformer models
- Pre-trained language models
- Tokenizers
- Input prompts
- Text generation
- Language modeling
- Hugging Face Transformers

Example workflow:

```text
Input Prompt
     ↓
Tokenizer
     ↓
GPT-2 Model
     ↓
Generated Tokens
     ↓
Generated Text
```

---

## 6. Text Summarization and Model Fine-Tuning

## Comparing Text Summarization Pipelines

Different text summarization approaches are explored and compared.

Text summarization aims to convert long text into shorter text while preserving the most important information.

Example:

```text
Long Document
      ↓
Summarization Model
      ↓
Short Summary
```

Topics covered:

- Transformer pipelines
- Pre-trained models
- Text summarization
- Comparing model outputs
- Evaluating generated summaries

---

## Model Fine-Tuning

Fine-tuning allows a pre-trained model to adapt to a specific task or dataset.

Instead of training a large model from scratch:

```text
Pre-trained Model
       ↓
Task-Specific Dataset
       ↓
Fine-Tuning
       ↓
Specialized Model
```

Topics covered:

- Pre-trained models
- Transfer of learned knowledge
- Training on custom datasets
- Model adaptation
- Hyperparameters
- Evaluation

---

## 7. Transfer Learning and Retrieval-Augmented Generation

## Transfer Learning

Transfer Learning allows knowledge learned by one model to be reused for another related task.

Instead of starting from zero:

```text
Pre-trained Model
       ↓
Existing Knowledge
       ↓
New Task
       ↓
Fine-Tuned Model
```

Benefits include:

- Faster training
- Less training data required
- Reduced computational cost
- Better performance

---

## Retrieval-Augmented Generation

Retrieval-Augmented Generation combines information retrieval with Large Language Models.

Instead of relying only on the knowledge stored inside the model, relevant external information is retrieved first.

Basic RAG architecture:

```text
User Question
      ↓
Retriever
      ↓
Relevant Documents
      ↓
Prompt + Context
      ↓
Large Language Model
      ↓
Final Answer
```

Topics explored:

- Information retrieval
- Context augmentation
- Language models
- Transfer Learning
- RAG models
- Combining retrieval and generation

---

## 8. SMS Spam Classification

An NLP classification pipeline is built to identify whether an SMS message is spam or legitimate.

Example:

```text
Message
   ↓
Text Cleaning
   ↓
Vectorization
   ↓
Classification Model
   ↓
Spam / Not Spam
```

Topics covered:

- Text preprocessing
- Feature extraction
- Text vectorization
- Classification
- Spam detection
- Model evaluation

---

# 🛠️ Technologies and Libraries

The notebooks in this repository use technologies and libraries such as:

## Programming

- Python
- Jupyter Notebook

## Data Processing

- Pandas
- NumPy

## Machine Learning

- Scikit-learn

## Deep Learning

- TensorFlow
- Keras
- PyTorch

## Natural Language Processing

- Hugging Face Transformers
- Tokenizers
- NLP Pipelines

## Large Language Models

- GPT-2
- Transformer Models
- Pre-trained Language Models
- Fine-Tuning
- Transfer Learning
- Retrieval-Augmented Generation

## Data Visualization

- Matplotlib

---

# 🚀 Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/SDAIA-LARGE-LANGUAGE-MODELS-BOOTCAMP.git
```

Replace:

```text
YOUR_USERNAME
```

with your GitHub username.

---

## 2. Navigate to the Project

```bash
cd SDAIA-LARGE-LANGUAGE-MODELS-BOOTCAMP
```

---

## 3. Create a Virtual Environment

```bash
python -m venv ai-env
```

---

## 4. Activate the Virtual Environment

### macOS / Linux

```bash
source ai-env/bin/activate
```

### Windows

```bash
ai-env\Scripts\activate
```

---

## 5. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6. Start Jupyter Notebook

```bash
jupyter notebook
```

Then open any notebook and run the cells.

---

# 🎯 Learning Outcomes

Through these exercises and projects, I gained hands-on experience with:

- Building machine learning models
- Preparing structured datasets
- Training classification models
- Evaluating model performance
- Building neural networks
- Understanding Sequential and Functional neural network architectures
- Developing Convolutional Neural Networks
- Performing handwritten digit classification
- Cleaning and preprocessing text data
- Building NLP pipelines
- Performing sentiment analysis
- Working with transformer models
- Generating text using GPT-2
- Comparing text summarization approaches
- Fine-tuning pre-trained models
- Applying Transfer Learning
- Understanding Retrieval-Augmented Generation
- Building spam classification models
- Working with Hugging Face models and pipelines

---

# 🌱 Areas of Interest

This bootcamp strengthened my interest in:

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Natural Language Processing
- Large Language Models
- Generative AI
- Retrieval-Augmented Generation
- AI Engineering
- Agentic AI

---

# 📈 Learning Journey

The notebooks in this repository progress from foundational Machine Learning and Neural Network concepts toward more advanced Natural Language Processing and Large Language Model techniques.

The learning path can be summarized as:

```text
Machine Learning
      ↓
Neural Networks
      ↓
CNN
      ↓
Text Processing
      ↓
Natural Language Processing
      ↓
Sentiment Analysis
      ↓
Transformers
      ↓
GPT-2
      ↓
Text Summarization
      ↓
Fine-Tuning
      ↓
Transfer Learning
      ↓
Retrieval-Augmented Generation
```

---

# 👩‍💻 Author

**Rasha**

Senior Software Engineer with 7+ years of experience building scalable digital applications, APIs, and data-driven platforms.

Currently expanding my experience into:

- Artificial Intelligence
- AI Engineering
- Large Language Models
- Generative AI
- Retrieval-Augmented Generation
- Agentic AI

---

# 📌 Note

This repository contains educational notebooks, exercises, and experiments completed as part of my learning journey during the **SDAIA Large Language Models Bootcamp**.

The projects are intended to demonstrate practical understanding and hands-on implementation of Machine Learning, Deep Learning, Natural Language Processing, and Large Language Model concepts.

---

## ⭐ Repository Purpose

The main purpose of this repository is to:

- Document my AI learning journey
- Practice AI and Machine Learning concepts
- Build hands-on experience with modern AI technologies
- Create a technical portfolio of AI projects
- Apply theoretical concepts through practical implementations
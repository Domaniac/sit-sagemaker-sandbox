# SIT-SAGEMAKER AI Sandbox - Starter Pack

Welcome to the **SIT-SAGEMAKER AI Sandbox Starter Pack**! This repository contains three sample machine learning modules designed for students to run in their provisioned SageMaker Studio environment. Each module demonstrates a different aspect of machine learning: regression analysis, natural language processing, and computer vision.

## 📚 Overview

This starter pack provides hands-on examples of:
- **Regression Analysis**: Predictive modeling with structured data
- **Sentiment Analysis**: Natural language processing with text data
- **Object Recognition**: Computer vision with image data

## 🚀 Usage Instructions

To get started with these modules in your SageMaker Studio environment:

1. Open a terminal in SageMaker Studio
2. Clone this repository:
   ```bash
   git clone [github url here]
   ```
3. Navigate into the cloned directory:
   ```bash
   cd sit-sagemaker-sandbox
   ```
4. Open any of the three module folders and launch the `notebook.ipynb` file

## 📊 Module 1: Regression Analyst

**Purpose**: Predicts housing prices from a CSV.

This module demonstrates predictive analytics using a linear regression model. Students will:
- Load housing data from a CSV file
- Train a regression model on features like square footage, bedrooms, bathrooms, and age
- Evaluate model performance using R-squared scores
- Visualize actual vs. predicted prices

**Location**: `1-Regression-Analyst/notebook.ipynb`

## 💬 Module 2: Sentiment Analyzer

**Purpose**: Analyzes the sentiment of text reviews from a .txt file.

This module showcases Natural Language Processing (NLP) capabilities. Students will:
- Load a collection of movie reviews from a text file
- Use a pre-trained transformer model for sentiment classification
- Analyze each review and classify it as POSITIVE or NEGATIVE
- See confidence scores for each prediction

**Location**: `2-Sentiment-Analyzer/notebook.ipynb`

## 🖼️ Module 3: Object Recognizer

**Purpose**: Detects objects in sample images.

This module demonstrates practical computer vision tasks. Students will:
- Load sample images (JPG format)
- Use a pre-trained object detection model
- Identify and locate objects within images
- View bounding boxes and confidence scores for detected objects

**Location**: `3-Object-Recognizer/notebook.ipynb`

## 📦 Requirements

All required Python packages are installed within each notebook using `pip install` commands. The main dependencies include:
- pandas
- scikit-learn
- matplotlib
- transformers
- torch
- Pillow

## 🎓 Learning Objectives

By working through these modules, students will gain practical experience with:
- Loading and preprocessing different types of data (CSV, text, images)
- Using scikit-learn for traditional machine learning
- Leveraging pre-trained models from Hugging Face Transformers
- Evaluating and visualizing model results
- Understanding different ML paradigms (supervised learning, NLP, computer vision)

## 📝 Notes

- Each module is self-contained and can be run independently
- The notebooks include detailed comments and explanations
- Sample datasets are provided in each module's `data/` folder
- Internet access is required to download pre-trained models

---


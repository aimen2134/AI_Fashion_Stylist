# AI Fashion Stylist – Simple Outfit Recommendation System

This is a simple rule-based outfit recommendation project built for a semester submission.  

It takes a natural language description like:

and generates:

- Gender classification (male/female)
- Style classification (casual/formal/party)
- An outfit recommendation sentence
- Optional image paths (if added in the future)

---

# Run the Project in Google Colab

Click the button below to run the project immediately in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimen2134/AI_Fashion_Stylist/blob/main/AI_Fashion.ipynb)

---

#  How It Works

The project follows a simple 3-layer software architecture:

### 1. **Data Layer**
Contains a built-in catalogue of outfit templates and sample image paths.

### 2. **Application Layer**
- TextPreprocessor
- RequestValidator
- CategoryClassifier (rule-based)
- RecommendationEngine
- SystemLogger
- AppController

These components work together to process input and generate recommendations.

### 3. **Presentation Layer**
A simple **console-based user interface** inside the notebook:

- You type a description  
- The system outputs:
  - classified gender  
  - style  
  - recommended outfit  
  - sample image path  

---

#  Files in This Project

| File | Purpose |
|------|---------|
| `AI_Fashion.ipynb` | Main executable notebook |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |




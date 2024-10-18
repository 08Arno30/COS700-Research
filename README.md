# Department of Computer Science

## COS700 Research Project

### Honours Research Project: Explainable AI for Truthful Assessment in Low-Resource Languages

**Author**: Arno Jooste (u21457451)  
**Supervisors**: Prof. Vukosi Marivate, Ms. Seani Rananga, Mr. Thapelo Sindane  
**Date**: October 2024  

---

### Introduction

Misinformation has the potential to spread rapidly in low-resource languages like Afrikaans, where reliable information sources are limited. This notebook investigates the use of Explainable Artificial Intelligence (XAI) in the detection and analysis of misinformation translated from English into Afrikaans. By focusing on misinformation classification in a low-resource language, the study aims to explore how models can be made more interpretable for better understanding and trustworthiness.

The workflow involves four main steps:

1. **Translation:** Misinformation texts are first translated from English to Afrikaans, and the translation quality is assessed.
2. **Text Encoding:** BERT embeddings are generated from the translated texts, capturing their contextual information.
3. **Classification:** These embeddings are fed into different machine learning models — Random Forest, Logistic Regression, and SVM — to classify the misinformation.
4. **XAI Application:** The best-performing classification model is further analysed using LIME (Local Interpretable Model-agnostic Explanations) to explain its predictions.

_Note: ensure to create your own `.env` file and add `GOOGLE_API_KEY = <your-google-api-key>`. This is important if you want to make use of Gemini for translations. You can find an API key [here](https://ai.google.dev/gemini-api/docs/api-key?authuser=2)_


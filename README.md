# TRAX_transformer_generative_summarization_model
Use Trax and Transformer architecture for generative summarizer deep learning model

This colab notebook is based on Deeplearning.ai / coursera course ["Natural Language Processing with Attention Models"](https://www.coursera.org/learn/attention-models-in-nlp/home/welcome) week 2 assignment. This module is part of Deeplearning.ai 4-course [Natural Language Processing specialization](https://www.coursera.org/specializations/natural-language-processing).

Requierements
- Trax==1.3.4
- T5==0.6.2

The model uses large 'cnn-dailymail' tensorflow dataset to train a transformer model on news article and associated sumamry. The model will then be able to generate summary for a text provided as an input. You can refer to a couple of my previous projects covering the different types of summary generation (extractive vs generative). This model generates a summary from the input text by elaborating own sentences. Greedy approach used.

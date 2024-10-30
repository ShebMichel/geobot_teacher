# geobot_teacher   

A conversational chatbot which assess geoscience student's assignments. It decides whether you fail or pass!
<p align="center">
<img src="https://github.com/ShebMichel/kagglex_imagebot/blob/main/geoBot_to_github.gif" alt="GeoBot Demo">
</p>

# Training gemma_2b_en For a Conversational Chatbot using Kaggle 

## Introduction

This project demonstrates how to build a chatbot using the Kaggle model Gemma 2 (gemma_2b_en)

## Load Model

KerasNLP includes implementations of various popular model architectures. In this tutorial, you’ll use GemmaCausalLM, a complete Gemma model for causal language modeling. Causal language modeling predicts the next token by analyzing previous tokens.

To create and load a model from_preset such as

gemma_lm = keras_nlp.models.GemmaCausalLM.from_preset("gemma_2b_en")

Alternatively, you can download and unzip the model from or run a Python script to download the model from your local

## Bot Testing

The frontend is implemented using `gradio` as well as `Huggingface`. 
To use huggingface, please click the link bellow:
[Huggingface](https://huggingface.co/spaces/ShebMichel/GeoScience_Exam_Marker)




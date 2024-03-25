# Classics with LLMs - fine-tuning BERT for Iris dataset classification task

## Introduction
Ever wondered how new generation of LLMs handle classical ML tasks? Goal of this series of experiments is to verify how LLMs perform on classical datasets. I create a series of simple experiments fine-tuning LLMs with various classic tasks.

This time we'll see how fine-tuned BERT handles the Iris classification task dataset.

Iris in a "Hello World" kind of dataset in machine learning. From LLM side we will use BERT - one of the simplest encoder-only models. Encoder because in the kind of taks like classification we care more about model creating a rich representation of data (encoder focus) rather then on sequence generation (decoder focus). 

Let's see how BERT handles the Iris dataset.

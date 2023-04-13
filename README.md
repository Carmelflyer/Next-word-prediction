# Next word prediction

## 1. Introduction
Natural language processing has been an area of research and used widely in different applications. We often love texting each other and find that whenever we try to type a text a suggestion poops up trying to predict the next word we want to write. This process of prediction is one of the applications NLP deals with. We have made huge progress here and we can use Recurrent neural networks for such a process.

## 2. Long Short-Term Memory Model Explanation
The problem with Recurrent Neural Networks is that they have a short-term memory to retain previous information in the current neuron. However, this ability decreases very quickly for longer sequences. As a remedy for this, the LSTM models were introduced to be able to retain past information even longer.
The problem with Recurrent Neural Networks is that they simply store the previous data in their “short-term memory”. Once the memory in it runs out, it simply deletes the longest retained information and replaces it with new data. The LSTM model attempts to escape this problem by retaining only selected information in short-term memory. This short-term memory is stored in the so-called Cell State. In addition, there is also the hidden state, which we already know from normal neural networks.

## 3. Dataset Description
The project’s aim is to predict the next word based on the input given.
The dataset in this project can be any storybook of the user’s choice in txt format. The details of the dataset used are as follows:
Name: Pride and Prejudice
Author: Jane Austen
Length of file: 698418 characters

## 4. MODEL PLOT


![image](https://user-images.githubusercontent.com/96384397/231660638-871d89db-0ab3-4750-b58b-0ebb7e4a0730.png)


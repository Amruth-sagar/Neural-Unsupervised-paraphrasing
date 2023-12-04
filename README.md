# Neural-Unsupervised-paraphrasing
Neural unsupervised Paraphrasing is one of the interests of recent NLP researchers.
This research helps to use datasets which don’t have human annotations and thus opens
a new direction in the field of paraphrasing. We have used pretrained BART to form pseudo
Ground truth and then perform an end-to-end supervised training of transformers from
scratch. We used four different corruption techniques, making our model more
robust.

## Introduction
- Paraphrasing is rewriting a given sentence in other words or forms without losing the meaning of the original sentence. 
- Paraphrasing can be achieved via training a deep sequence to sequence models, like RNN, LSTMs, Transformers etc, in a supervised setting.
- Creating supervised datasets for paraphrasing is both time-consuming and expensive.
- Therefore, several approaches aim to achieve paraphrasing using unsupervised methods.
This project aims to generate paraphrases by corrupting a sentence and reconstructing the correct sentence using deep auto-regressive denoising approaches. 
![image](https://github.com/Amruth-sagar/Neural-Unsupervised-paraphrasing/assets/89086031/cc6d733e-c552-4aff-a763-0fbc865205dc)



# zindi-audio-classification
This is a solution to a competition held on Zindi. This solution ranked 40/255 (Top 16%) 

Challenge: Classify audio utterances in Luganda and English from Uganda
The objective of this competition is to build a machine learning model to identify the agricultural keyword (which may be in English or Luganda) spoken in an audio clip. The keywords relate to crops, diseases, fertilizers, herbicides or other general agricultural topics.

Approach: 

Generating audio spectograms with librosa

Augmenting data with librosa using methods such as adding noise, hpss and pitch shift

Training:

Resnet34 model with a custom head and fully connected output layer.

3 fold Stratified cross-validation

Insights:
I only worked on this for 8 hours on the last day of the competition (which had lasted 2 months) and still made top 16%


Link: https://zindi.africa/competitions/giz-nlp-agricultural-keyword-spotter

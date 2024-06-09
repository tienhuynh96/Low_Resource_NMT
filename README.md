# Low_Resource_NMT

This repo contains demo code for implementing models to translate from English to Vietnamese in case of low resource.

1. Use Pre-trained mBART50:
- Data: The IWSLT'15 English-Vietnamese data is used from Stanford NLP group.
  1 Demo code: [code]_NMT_mBART50.ipynb
 
2 Use Pre-trained mBART50 and technique "Back-Translation" include steps:
  - Train model to translate VI-EN
  - Synthetic Data (create more data):
    + Use trainer (VI-EN) to create sample.
    + Use Reference to create sample or batch sample.
  - Train model EN-VI include orginial data and created data
  - Demo code: [Demo]-NMT-Back-Translation.ipynb

*** For reference: T5 model for generate text, translation, sumarization.
Demo code: [Demo]_Use_T5.ipynb

# ATCSIndProj
This is my final project for the 2023-2024 Advanced Topics in CS course at Polytechnic School. 

## 2024-05-09

- decided topic, machine learning instead of C (resource bookmarked for another time though!)
- Made and verified Kaggle account
- Made a copy of the notebook and started on it

## 2024-05-17

  1. watched fastai video Practical Deep Learning for Coders: Lesson 1. Some notes:

  - how machine learning has changed, in 2012 (ex: 5 yr survival rate of breast cancer patients) manually developed relationships, now neural networks do for us 
    - "we don't give it features, we ask it to learn features" so it can identify things = deep learning. 
    - start with random neural network, feed it examples, weights are adjusted

  - Jupyter lets you insert text (markdown), helpful for future self and open source comm

  - in practical application, deep learning comm has found reasonably small amount of neural archictures that work for almost everything you need

  - explained the code on the Jupyter notebook
    - set aside some data for validation set, in this notebook 20% data 
    - we're using pretrained not random weights here. fastai's finetune method adjusts weights to teach model differences between your dataset and what the model was originally trained for


1. Ran Jupyter notebook and got an error that urls is not defined. Figured out eventually that the mod on the crashwhite website says it's meant for the fourth block but it's actually a mod for the third block. Notebook worked after this mod and the other suggestions on the website (enable internet access and select latest environment version)


3. Tried to get the model to classify other things:
   - f1 drivers charles leclerc vs carlos sainz, did not work well. only 20% certain charles was charles and 50% certain carlos was charles. 
   - Then tried to get it to classify f1 vs motogp pictures. Worked very well: 0.9999 probability f1 photo is f1, 0 probability motogp photo is f1 
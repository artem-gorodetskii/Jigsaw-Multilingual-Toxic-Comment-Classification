# Jigsaw-Multilingual-Toxic-Comment-Classification
My project from Kaggle competition Jigsaw Multilingual Toxic Comment Classification 
(https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/data). 
Using my model and data preparation strategy is possible to achieve 78% accuracy 
on multilingual test dataset.

In a nutshell, in order to predict toxicity of multilanguage comments I developed the following model:

(1) 17368 comments from training set were selected and translated on six different languages using translators library;
(2) for toxic and normal comments vocabularies were created separately and then combined;
(3) the final model contain embedding layer, two layers with GRU cells and one Dense layer.

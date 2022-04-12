# Sartorius-LiveCell-Instance-Segmentation
Sartorius LiveCell Instance segmentation is a kaggle competition. Challenge is to do instance segmentation of Neural Cells using state of the art deep learning methods for maximum score.
https://www.kaggle.com/c/sartorius-cell-instance-segmentation

Evaluation Criteria is Intersection Over Union. Details are given on the kaggle page.

Model was pretrained on Livecell dataset, which is a bigger dataset than sartorius and have 8 cell types. 
For training Detectron 2 Library was used, and Mask RCNN FPN was used as base model.
Model was fine tuned on sartorius dataset to get the final results.



# Python-ML-Production
This repository shows a test machine learning pipeline that is done through Amazon Sagemaker.
The purpose of the pipeline being on Sagemaker was to automate the update of database to account for data drift in reality,
the pipeline consists of every step in a typical machine learning production (with model training and evaluation) excluding data monitoring.

I did not proceed with the data monitoring because I was racking up quite a bill with Sagemaker... and it was simply a matter of evaluating the
model packages which resulted from previous steps in the pipeline.

This was based on assignments in the ml.school lectures by Santiago L. Valdarrama as part of the Machine Learning School program.
In the original machine learning school program, a keras model was used. The pipeline that I have coded takes the rote portions (mostly Sagemaker stuff)
from Santiago while my learning consisted of mainly these:
- Concepts for a practical machine learning pipeline
- Building a machine learning pipeline with Amazon Sagemaker
- Understanding how a Pytorch model is built, trained, saved and loaded using Sagemaker tools.

This program serves as part of my interest in exploring the creation of a machine learning model to recognize real data structures of digital 3D models
such as IFC, BIM, Speckle, etc.

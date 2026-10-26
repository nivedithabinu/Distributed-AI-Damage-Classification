# Distributed AI Damage Classification Service
An AI-powered image classification service for identifying visible structural damage, with a focus on reproducible model evaluation and distributed inference across three laptops.

## Project objectives
1. Investigate a suitable structural-damage dataset.
2. Train and compare a baseline CNN and ResNet18.
3. Evaluate classification performance using accuracy, precision, recall, and F1-score.
4. Develop a FastAPI prediction service and a React interface.
5. Store prediction results in a database.
6. Containerize the service and evaluate distributed inference using three laptops.

## Current status
Project setup and dataset selection.

The dataset, class labels, and separate material-prediction task must be verified before training begins.

An AI-powered image classification service designed to identify visible damage categories from structural or surface images and investigate distributed model inference across multiple low-cost machines.

The project combines computer vision, backend development, and distributed systems to build an accessible damage classification service.

A user submits an image through a web interface. The backend processes the image using a trained classification model and returns a predicted category with its confidence score. Prediction results can be stored for later reference.

The system will also be evaluated in a multi-node deployment to study how incoming inference requests are distributed across three laptops.
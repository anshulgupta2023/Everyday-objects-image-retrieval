This repo contains my deep learning term project where I build a small, practical image search and recognition system for everyday objects. The project is split into two milestones:

Milestone 1 – Everyday Object Catalog & Attribute Retrieval: I created a custom dataset of ~600 images across 10 everyday object classes, each with a caption, attribute tags (e.g., color, material, condition), and train/val splits designed for good generalization.

Milestone 2 – Modeling & Retrieval: I train and compare two lightweight Vision Transformer variants on (1) my own dataset and (2) a pooled multi-team dataset to perform object classification, attribute prediction, and text→image retrieval for queries like “blue plastic mug”. I report accuracy/F1 scores, confusion matrices, and example retrievals, and analyze how model choice and dataset scale affect performance.

The repo includes:

Custom image dataset (spec & annotations)

Training scripts for the transformer models

Evaluation + analysis notebooks

A simple demo notebook for class/attribute prediction and text-based image retrieval

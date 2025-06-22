# SkimLit Project

## Overview
The purpose of this project is to build an NLP model to make reading medical abstracts easier. In the the general notebook you could see all the process for the data preparation and the different experiments to achieve the  architecture used in the paper https://arxiv.org/abs/1710.06071

## Main Features
* Train a NLP model using a tribrid embedding
* Transfer Learning with a pretrained toklen embedding
* Chracter level and positional embeddin
* Data preparation and prefetching preparation
* Metrics comparative amonmg the different experiments 
## Usage
 1. For experimentation process run the notebook SkimLit_project.ipynb
 2. Run SkimLit_Best_model.ipynb for the best model architechture
## Project Structure
- SkimLit_project.ipynb          # Training and developing notebook of the project 
- SkimLit_Best_Model.ipynb       # Best model notebook
- skimlit_tribid_model.keras     # Model
- LICENSE
- README.md                     
## Technologies Used
* Jupyther Notebooks
* Tensorflow/keras
* Sklearn Metrics
* Tensorflow Hub
* Matplotlib
* Pandas/Numpy
## License 
This project is licensed under the MIT License. See the LICENSE file for details.

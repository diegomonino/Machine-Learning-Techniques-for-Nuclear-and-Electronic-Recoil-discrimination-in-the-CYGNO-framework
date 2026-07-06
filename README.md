# BRIEF INTRODUCTION #

The goal of our Project was to develop a reliable and efficient method for the discrimination of Electronic Recoils (Background Events) and Nuclear Recoils (Signal Events) in the CYGNO Framework. 
Thanks to Machine Learning, the objective was to train a Model to learn the characteristic features of the two events, being able to discriminate between them in the Energy-Density Plane. 
The analysis develops around Two Real Datasets (a Fully Electronic Background Dataset and a Mixed Dataset) and Two Monte Carlo Simulated Datasets (an Electronic Recoil Dataset and a Nuclear Recoil Dataset).
Since labels for the real mixed dataset are not available, the project revolves around two different strategies: training the models on Monte Carlo Data and Training using the CWoLa Approach. 

Starting from a previous CNN model, different routes have been explored:
- GNN Network: to improve performance and classification, taking advantage of the morphology of these events to perform classification;
- CNN Uncertainty Quantification: to have an idea on how good the starting CNN performs classification, trying to understand how reliable it is;
- CNN Contrastive Learning: to mix the Monte Carlo training with the CWoLa Approach, to obtain the best results possible.

Each of the approaches has a different .ipynb file, and the Results are presented in the CYGNODiscrimination.pptx file.


<img width="2048" height="1016" alt="image" src="https://github.com/user-attachments/assets/0a7792ac-6d48-4f59-9c70-304fd650cde8" />

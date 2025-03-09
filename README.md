# ML4SCI 2025
A repository containing my submissions for the evaluation test for prospective
 GSoC applicants for the End-to-End Deep Learning (E2E) project and SYMMETRY project.
 I applied for, the **Discovery of hidden symmetries and conservation laws** project 
 and **Semi-supervised Symmetry Discovery** project, and did the following tests:
- **Common Task:** Electron/photon classification solution can be found [here](https://github.com/GiuseppeFrigeni/ML4SCI2025/blob/main/First%20task/ml4sci-2025-first-task.ipynb)
- **Specific Tasks:** Supervised and Unsupervised Symmetry Discovery can be found ...  
  
### Common Task: Electron/photon classification
Task: given a dataset, composed of two classes (photons and electrons), of 32x32
matrices with two channels (hit energy and time) classify them using a **Resnet-15**.

To maximize performace i used data augmentation and a fraction of the dataset so that
the model could be more robust and less prone to overfitting compared to training
the entire dataset without data augmentation.


### Specific Task: 

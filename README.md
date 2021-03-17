# Event Classification with Layerwise Learning for Data Re-uploading Classifier in High Energy Physics

Team Name: Entangled_Nets

### Abstract

This project aims to use the method of modified layerwise learning[8] on data re-uploading classifier[6], where parametrized quantum circuit will be used as quantum classifiers to classify the SUSY dataset[1]. We managed to produce a better result using this approach compared to the previous related research[2] with less number of qubit. We obtained AUC of 0.8488 on testing dataset with 5000 training and testing samples, trained and tested using a simulator. We also tested to run the circuit on Rigetti's Aspen-9 QPU provided by AWS using the already optimized parameter to predict 2000 samples of test dataset and we obtained AUC of 0.8298.


### Acknowledgment 

This work is submitted to the QHack 2021 organized by Xanadu. During the hackathon, we had the opportunity to learn and implement ideas in the field of QML. It was a pleasure to be part of this hackathon, and as a team, we would like to thank all the speakers for their valuable presentations and the Xanadu team for organizing an amazing event.


**References:**

[1] [SUSY Dataset - UCI Machine Learning Repository.](https://archive.ics.uci.edu/ml/datasets/SUSY#)

[2] [Event Classification with Quantum Machine Learning in High-Energy Physics.](https://arxiv.org/abs/2002.09935)

[3] [Unfolding measurement distributions via quantum annealing.](https://link.springer.com/article/10.1007/JHEP11(2019)128)

[4] [Quantum Computing in the NISQ era and beyond.](https://quantum-journal.org/papers/q-2018-08-06-79/#)

[5] [Quantum Machine Learning in High Energy Physics.](https://arxiv.org/abs/2005.08582)

[6] [Data re-uploading for a universal quantum classifier, Adrián Pérez-Salinas, Alba Cervera-Lierta, Elies Gil-Fuster, José I. Latorre.](https://arxiv.org/abs/1907.02085)

[7] [PennyLane optimizers](https://pennylane.readthedocs.io/en/stable/introduction/optimizers.html)

[8] [Layerwise learning for quantum neural networks, Andrea Skolik, Jarrod R. McClean, Masoud Mohseni, Patrick van der Smagt,  Martin Leib](https://arxiv.org/abs/2006.14904)


### Note
The final notebook is [here](https://github.com/eraraya-ricardo/qhack-2021-openproject/blob/main/QHack_Final.ipynb). GitHub sometimes failed to render Jupyter Notebook's markdown properly, so in case of that please use this [link](https://nbviewer.jupyter.org/github/eraraya-ricardo/qhack-2021-openproject/blob/main/QHack_Final.ipynb) to see the notebook in nbviewer. <br>
The final notebook is the clean version of the code that by itself should be enough to reproduce the results, but all the testing/temporary codes and other files used in this project are available at the [Old GitHub Repo](https://github.com/VoicuTomut/Event-Classification-with-data-reuploading-in-High-Energy-Physics).
Our numerical results from the Rigetti's QPU device are stored inside the Amazon Braket.

# :pill: SARS Coronavirus Inhibitor Prediciton

Drug discovery and design is an extensive process that traditionally requires synthesis of several whole molecules and use of various, often repetitive physicochemical tests. With the advent of in silico chemical analysis, significant amounts of time, effort, and resources can be saved, requiring the synthesis, testing, and manufacturing of only one or a few candidate drugs.

In this project, I have created a model to predict the candidacy of input molecules in being effective drugs against the SARS coronavirus. The specific target protein used in my model is the 3-chymotrypsin-like cysteine proteinase because it plays an important role in viral replication; inhibition of this enzyme is likely to inhibit the virus' lifecycle.

The Python notebook files contain the entire pipeline for this project, which was adopted from [Chanin Nantasenamat's tutorial on bioactivity prediction](https://github.com/dataprofessor/code/tree/master/python). The bioactivity_app.py contains the deployment of the model.

### 🛠️ Tools used:
- ChEMBL database
- RDkit
- PaDEL-Descriptor
- scikit-learn
- Streamlit

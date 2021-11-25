# :pill: SARS Coronavirus Inhibitor Prediciton

Drug discovery and design is an extensive process that traditionally requires synthesis of several whole molecules and use of various, often repetitive physicochemical tests. With the advent of in silico chemical analysis, significant amounts of time, effort, and resources can be saved, requiring the synthesis, testing, and manufacturing of only one or a few candidate drugs.

In this project, I have created a model to predict the candidacy of input molecules in being effective drugs against the SARS coronavirus. The specific target protein used in my model is the 3-chymotrypsin-like cysteine proteinase because it plays an important role in viral replication; inhibition of this enzyme is likely to inhibit the virus' lifecycle. This model was then used to create a web application with Streamlit and Heroku to predict the drug candidacy of any input molecule towards this protein. This application has been deployed at https://sars-drug-bioactivity.herokuapp.com/ and its source code can be found in the [sars_bioactivity_app](https://github.com/hamiq/sars_bioactivity_app) repository.

The Python notebook files in this repository contain the framework and pipeline for this project, which was adopted from [Chanin Nantasenamat's tutorial on bioactivity prediction](https://github.com/dataprofessor/code/tree/master/python).

### 🛠️ Tools used:
- ChEMBL database
- RDkit
- PaDEL-Descriptor
- scikit-learn

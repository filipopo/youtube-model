# youtube-model

This Python project contains a youtube.ipynb Jupyter notebook in which videos from the youtube trending 2017 dataset were analyzed with pandas and visualisations were made using matplotlib

![image](https://github.com/user-attachments/assets/ff5a3d3c-4b2e-426e-8ede-1f342208596b)

In the last section of the notebook a one class classifier ML model was made in Scikit-learn which predicts will a new video be trending

The dataset is saved under the dataset folder but it can also be found here: https://www.kaggle.com/datasets/elmarico/youtube-trending-2017

In the report folder, there's a graphical report of the findings in the Serbian langauge made in PyQT5 for which the interface was made using QT designer

You can install the requirements for the entire project with `pip install -r requirements.txt`

Then you can view the PyQT5 report

`python izvestaj.py`

The resources for the report were compiled by running
`pyrcc5 resursi.qrc -o resursi_rc.py`

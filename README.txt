All code is contained in Jupyter notebooks dev1_credit_default.ipynb and dev2_fma.ipynb.

Their names correspond to the dataset they are used for.

Code can be found here: https://github.gatech.edu/clu328/ml-assignment1

If you cannot access gaTech GitHub, I have also pushed it to external GitHub here: https://github.com/luclement/ml-assignment1

Datasets:

1. Credit Card Default dataset is provided under datasets folder, if it does not work for some reason, it can be downloaded here: https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset/download
  a. Place under datasets/
2. Free Music Archive is quite large, it can be downloaded here: https://os.unil.cloud.switch.ch/fma/fma_metadata.zip
  a. Place under datasets/fma_metadata/

Install:

1. Run "pip install -r requirements.txt" to install required dependencies
2. Make sure you have Jupyter installed by running "jupyter --version" and you should see jupyter-notebook installed
3. To start the notebook, run: jupyter notebook
4. Navigate to desired notebook and run from the top down

Code references:
1. Sklearn for general tutorials and library usage: https://scikit-learn.org/stable/user_guide.html
2. SO post for generating tree graph: https://stackoverflow.com/questions/27817994/visualizing-decision-tree-in-scikit-learn
3. Sklearn kNN plotting tutorial: https://scikit-learn.org/stable/auto_examples/neighbors/plot_classification.html#sphx-glr-auto-examples-neighbors-plot-classification-py
4. Datacamp tutorial on using Sklearn SVM classifier: https://www.datacamp.com/community/tutorials/svm-classification-scikit-learn-python
5. In utils, credit to Sklearn for the learning curve plotting code: https://scikit-learn.org/stable/auto_examples/model_selection/plot_learning_curve.html
6. In utils, credit to Sklearn for the validation curve plotting code: https://scikit-learn.org/stable/auto_examples/model_selection/plot_validation_curve.html
7. In utils, credit to FMA for FMA data loading code: https://github.com/mdeff/fma/blob/master/utils.py
8. Credit to FMA for usage instructions/code: https://github.com/mdeff/fma/blob/master/usage.ipynb

Packages used:
1. scikit-learn: https://scikit-learn.org/stable/
2. pandas: https://pandas.pydata.org/
3. graphviz: https://www.graphviz.org/
4. pydotplus: https://pydotplus.readthedocs.io/
5. jupyter: https://jupyter.org/
6. numpy: https://numpy.org/
7. matplotlib: https://matplotlib.org/

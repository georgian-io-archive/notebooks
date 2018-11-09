Please use this repository for jupyter notebooks for the following purpose:
1. share tips or interesting findings when using python data science libraries such as numpy, pandas, scikit-learn.
1. share tips or interesting findings for data processing
1. share tips or interesting findings for machine learning
1. share information with external collabrators outside Georgian Partners

Please note that this repository is **public**. **DO NOT** include any prepriatory data, algorithm, implemenation or any other confidential information in this repository.

### View notebooks via GitHub
Since GitHub renders jupyter notebook automatically, to simply view the notebook, not juypter server is needed.

### Run notebooks via Google Colab
This repository is public, so you can open the notebook directly from Google Colab and run the notebook there. [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb) is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud. 

1. Click on [Open A Notebook in Colab](https://colab.research.google.com/github/georgianpartners/notebooks/blob/master)
1. Click to open the desired notebook from the list
1. After the notebook is loaded, you can run the cells as normal

If you made changes to the notebook and would like to update the version in the repository, simply download the notebook from Colab and drag&drop to the repository in GitHub. Make sure the file has the same name as the older version unless you want to create another copy. Please always add a comment to state the change before you commit the new version.

### Run notebooks via local Jupyter server
If you would like to use a local Jupyter server to runn the notebook, a typical git workflow can be used.

1. Clone or pull from the repository to local
1. Start a local Jupyter server to run the notebook (PyCharm will automatically start a Jupyter server when double click an notebook file).
1. If you make changes, follow the normal git commit/git push workflow to update the version in the repository.

### Best practices
1. See [this](https://colab.research.google.com/notebooks/snippets/importing_libraries.ipynb) for how to declare your dependencies in the notebook. Google Colab already have many libraries pre-installed, including numpy, pandas, scikit-learn, xgboost and tensorflow.
1. See [this](https://colab.research.google.com/notebooks/io.ipynb) for how to load external data. It is not recommended to add data files to this repository.
1. It is recommended to add a link to the top of your repository so that it could be opened directly in Colab. The link follows this format `https://colab.research.google.com/github/georgianpartners/notebooks/blob/master/${PATH_TO_NOTEBOOK_IN_REPOSITORY}`. See [MultiCategoricalEncoder.ipynb](MultiCategoricalEncoder.ipynb) for an example.


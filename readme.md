# Jupyter Prov Demo
There are two Jupyter notebooks in this repository:
1. [prov_display.ipynb](prov_display.ipynb) - utilises Python to query a provenance database and display the results using graphviz.
2. [prov_sparql_kernal.ipynb](prov_sparql_kernal.ipynb) - utlises a SPARQL kernal for Jupyter to directly run and display queries against a SPARQL endpoint. Visualisation is supported by the kernal but not yet working in this codebase.
## Installation and Usage
1. run pip install -r requirements.txt or poetry install.
2. If using the prov_sparql_kernal notebook, run `jupyter sparqlkernel install --user` in a terminal.
3. Run the notebook you wish using:
- `jupyter notebook [notebook_name]` locally
- IDEs with Jupyter integration (e.g. PyCharm) - see IDE's documentation for more information.
- Google Colab e.g. https://colab.research.google.com/github/surroundaustralia/Jupyter-Prov-Demo/blob/master/prov_display.ipynb
- mybinder.org e.g. https://mybinder.org/v2/gh/surroundaustralia/Jupyter-Prov-Demo/HEAD?labpath=prov_display.ipynb

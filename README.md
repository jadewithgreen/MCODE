<<<<<<< Updated upstream
=======
# MCODE
basic implementation of mcode in Python
>>>>>>> Stashed changes
# MCODE-Based Protein Complex Detection (Vertex Weighting Project)

In this project, we use a Jupyter Notebook to implement the **vertex-weighting stage** of the MCODE algorithm to help identify potential protein complexes in a yeast kinase–substrate interaction network. Our goal is to turn the interaction data into a graph and then compute weights for each protein based on how dense its local neighborhood is.

The dataset we use comes from:

> Bandyopadhyay S. et al., *A human MAP kinase interactome* (2010)
<<<<<<< Updated upstream
=======
> https://doi.org/10.1038/ncomms1139
>>>>>>> Stashed changes

In our graph:
- Each protein is a **node**
- Each interaction between proteins is an **edge**

We load the dataset, build the graph using NetworkX, calculate vertex weights using k-core density, and visualize the results.

---

## Files Included

- **`mcode.ipynb`** – Our main notebook with all code, explanations, and plots.
- **`Bandyopadhyay2010.xls`** – The protein interaction dataset (this must be in the same folder as the notebook for it to load correctly).

---

## Requirements

To run everything, we need:

- **Python 3.9+** (3.10+ recommended)
- **Jupyter Notebook** or **JupyterLab**
- These Python packages:
  - `numpy`
  - `polars`
  - `networkx`
  - `matplotlib`
  - `seaborn`
  - `plotly`

If we want, we can also create a `requirements.txt` file to manage dependencies:

```txt
numpy
<<<<<<< Updated upstream
polars
=======
polars==1.34.0
>>>>>>> Stashed changes
networkx
matplotlib
seaborn
plotly
<<<<<<< Updated upstream
jupyter


=======
jupyter
>>>>>>> Stashed changes

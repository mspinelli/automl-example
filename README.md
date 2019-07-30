# Auto ML Example

The easist way to look at this repo is to view the [notebook](https://nbviewer.jupyter.org/github/mspinelli/automl-example/blob/master/automl.ipynb) through jupyter.org (Github doesn't always render notebooks properly). Alternatively, clone the repo and open `automl.slides.html` in a browser.

## Running the Code

To run the code in this repo you'll need to install [miniconda](https://docs.conda.io/en/latest/miniconda.html). Then run the following:

```bash
conda -n automl python=3 jupyter scikit-learn pandas seaborn
source activate automl
pip install tpot
```

Next install graphviz, which on Ubuntu can be done as follows:

```bash
sudo apt install graphviz
```

Launch the notebook with:

```bash
jupyter notebook automl.ipynb
```
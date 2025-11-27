# Visualizing Customer Segments with a Self-Organizing Map (SOM)

This repository contains a Jupyter Notebook that demonstrates how to visualize customer segments using a Self-Organizing Map (SOM) and simple clustering (KMeans) on the Mall Customers dataset.

Notebook
- `ml2assignment.ipynb` — A Colab-origin notebook (downloaded and stored here) that:
  - Loads the Mall Customers dataset from a working GitHub-hosted CSV.
  - Preprocesses features (Annual Income, Spending Score) with MinMax scaling.
  - Trains a MiniSom grid and visualizes the U-Matrix (distance map).
  - Maps customers to winning neurons and overlays points on the SOM.
  - Uses KMeans on neuron weight vectors to label region clusters and inspects centroids.

Authors
- Asifa Bandulal Beedi


Quick start
1. Create a virtual environment (recommended) and activate it. Example (Windows PowerShell):

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Launch Jupyter Notebook (or Jupyter Lab) and open `ml2assignment.ipynb`:

```powershell
jupyter notebook
```

Notes
- The notebook was originally developed in Google Colab and uses `!pip install` in the first cell to install `minisom` when run in Colab. Installing from `requirements.txt` in a local environment is recommended for reproducibility.
- The dataset is loaded from a raw GitHub URL in the notebook; you do not need to include the dataset in the repository.

Contact
- For questions about the notebook, reach out to the authors listed above.

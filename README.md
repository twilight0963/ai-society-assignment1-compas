# Assignment work from AI&Society - Assignment 1

Please consult the report for this code for further details. Run `pip install -r requirements.txt` to install all required packages. Open .ipynb file in Jupyter/VSCode/Colab.

## Dataset:

I used ProPublica's COMPAS dataset ([source repository](https://github.com/propublica/compas-analysis)).
Download it into the project root (same folder as the notebook), keeping the file name `compas-scores-two-years.csv`:

```bash
curl -L https://raw.githubusercontent.com/propublica/compas-analysis/master/compas-scores-two-years.csv -o compas-scores-two-years.csv
```

## Quick install:

For a quick download of the notebook and dataset, also the libraries:

```bash
git clone https://github.com/twilight0963/ai-society-assignment1-compas; 
curl https://raw.githubusercontent.com/propublica/compas-analysis/master/compas-scores-two-years.csv > ai-society-assignment1-compas/compas-scores-two-years.csv;
pip install -r ./ai-society-assignment1-compas/requirements.txt
```

then run `jupyter-lab`. Otherwise open the `.ipynb` file in Google Colab or VSCode.


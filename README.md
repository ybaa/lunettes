# lunettes

### project structure
```
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- documentation
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data
│   │   
│   ├── experiments    <- Scripts with code for testing model 
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │                     predictions
│   ├── __init__.py    <- Makes src a Python module
|   |
│   ├── main.py        <- Makes src a Python module
|   |
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
├── README.md          <- The top-level README.│
└── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
```

### Installing development requirements
   
    conda install requirements-conda.txt
    pip install -r requirements-pip.txt
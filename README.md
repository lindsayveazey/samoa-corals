# samoa_corals

This repository is a work in progress and will include primarily Jupyter Notebooks using R and Python. Raw data may be included at some point.

- data_wrangling.ipynb (R): organizing, importing, cleaning raw data. *Completed raw data cleaning*

- spatial_model_setup.ipynb (R): checking for correlations, outliers, and missing data; imputing/removing data as needed *Completed checks*

- classifier_models (Python): running various classifier models to predict occurrence of different coral groups per region. Note- the classifiers aren't useful, so abundance is the way we're going... *Completed- abandoned*

- abundance_models (Python): running various regressor models to predict percent abundance of different coral groups per region. 7/7 models run, 5 are valid and usable; all predictions vs. actual data saved to dfs for visualization; all model estimates predicted out for the AS_all.csv df. *Completed and ready for visualization*

- visualization.ipynb (R): maps, predictions vs. actual, variable importance figures *In progress*

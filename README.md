Temps de Réponse de la Brigade des Pompiers de Londres  (CodeName: Jan24_cds_Pompiers)
==============================

**Description du projet :**

*L’objectif de ce projet est d’analyser et/ou d’estimer les temps de réponse et de mobilisation de la Brigade des Pompiers de Londres.La brigade des pompiers de Londres est le service d'incendie et de sauvetage le plus actif du Royaume-Uni  et l'une des plus grandes organisations de lutte contre l'incendie et de sauvetage au monde.*

*Le premier jeu de données fourni contient les détails de chaque incident traité depuis janvier 2009. Des informations sont fournies sur la date et le lieu de l'incident ainsi que sur le type d'incident traité.*

*Le second jeu de données contient les détails de chaque camion de pompiers envoyé sur les lieux d'un incident depuis janvier 2009. Des informations sont fournies sur l'appareil mobilisé, son lieu de déploiement et les heures d'arrivée sur les lieux de l'incident.*

**Ressources à consulter :**

- **Données :**
  - Deux principaux jeux de données disponibles ici :

    <https://data.london.gov.uk/dataset/london-fire-brigade-incident-records>

  - Et : <https://data.london.gov.uk/dataset/london-fire-brigade-mobilisation-records>

**Conditions de validation du projet :**

- un **rapport** d’exploration, de data visualisation et de pre-processing des données ;
- un **rapport** de modélisation ;
- un **rapport** final et le **Code** associé.
[DataScientest.com](https://datascientest.com/)

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------

References and Reading
------------

**Projet architecture**

- [how-to-structure-your-machine-learning-project-62f8a1eef582](https://medium.com/@theDrewDag/how-to-structure-your-machine-learning-project-62f8a1eef582)

- [how-structure-machine-learning-projects-we-just-building-vivek-kumar](https://www.linkedin.com/pulse/how-structure-machine-learning-projects-we-just-building-vivek-kumar/)

- [deep-dive-how-to-structure-your-code](https://newsletter.theaiedge.io/p/deep-dive-how-to-structure-your-code)

- [Machine-Learning-Project-Structure](https://github.com/ghimiresunil/Machine-Learning-Project-Structure)

- [how-to-organize-deep-learning-projects-best-practices](https://neptune.ai/blog/how-to-organize-deep-learning-projects-best-practices)

- <https://medium.com/@l.charteros/scalable-project-structure-for-machine-learning-projects-with-pytorch-and-pytorch-lightning-d5f1408d203e>

- [cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science)

- [Anaconda Vs Miniconda](https://github.com/ssime-git/mc-tooling-dsmlops/blob/main/Intro_conda_jupyterNB_FR.ipynb)

- [Documenting_Example](https://github.com/Irene-arch/Documenting_Example)

**Other :**

- TODO

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

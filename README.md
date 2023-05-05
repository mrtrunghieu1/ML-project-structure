# ML-project-structure
## The resulting directory structure

The template of machine learning projects looks like this:
```commandline
├── data   
│   ├── processed          <- The raw data is processed.             
│   └── raw                <- The original, immutable data dump.
│
├── documents              <- Other materials such as research papers, docs, images
│   
├── models                 <- Trained models, weight of models
│   
├── notebooks              <- Jupyter notebooks. Naming convention is a number (for ordering),
│                              the creator's initials, and a short `-` delimited description.
├── results                <- Output_writer is to save the results.
│
├── src                    <- Source code for use in this project.
│   ├── data_helper.py     <- Parameters, data paths are storaged here.
│   │
│   ├── evaluation.py      <- Scripts to evaluate models.
│   │
│   ├── model.py           <- Scripts to build ML or DL models.
│   │
│   ├── train.py           <- Scripts to train models.
│   │
│   ├── visualization.py   <- Scripts to visualize the results such as bar charts, scatter charts.
│   │
│   ├── utils.py           <- Scripts to code small functions that support other files.
│   
├── .gitignore             <- Files ignore when committing your project to the Github repository.
│   
├── README.md              <- README for developers using this project.
│   
├── requirements.txt       <- Installing all modules/ libraries that are used in the projects.
```

## Thank-You for reading! Share your ❤️ by starring your machine learning project!
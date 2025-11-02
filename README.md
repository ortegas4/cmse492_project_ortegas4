# The better fantasy football projector (BFFP)

The Better Fantasy Football Projector (BFFP) is a machine learning project designed to more accurately predict fantasy football performance by incorporating key offensive metrics. The model leverages player statistics such as targets, receptions, passing yards, and fumbles lost to estimate weekly fantasy point outcomes with higher precision than standard projections. Using regression-based learning techniques, BFFP identifies trends in player efficiency and usage patterns to produce data-driven forecasts that help fantasy managers make smarter lineup and trade decisions. As of now no dependencies are needed apart from a regular python enviroment but, as the project progresses this will be updated.

SET UP INSTRUCTIONS:

1.To be added.


DIRECTORY STRUCTURE

cmse492_project/
├── README.md                 # Overview of the project, setup instructions, and usage examples
├── .gitignore                # Files and folders to ignore in version control (e.g., logs, cache, venv)
├── data/
│   ├── raw/                  # Original, unmodified datasets (e.g., player stats, weekly fantasy data)
│   └── processed/            # Cleaned and preprocessed data ready for analysis or modeling
├── notebooks/
│   └── exploratory/          # Jupyter notebooks for exploratory data analysis (EDA), visualization, and testing ideas
├── src/
│   ├── preprocessing/        # Scripts for data cleaning, feature engineering, and transformations
│   ├── models/               # Machine learning model definitions, training scripts, and saved model files
│   └── evaluation/           # Model validation, metrics calculation, and performance comparison scripts
├── figures/                  # Plots, charts, and other visual outputs generated during analysis
├── docs/                     # Project documentation, reports, and presentation materials
└── requirements.txt          # List of Python dependencies and package versions needed to run the project

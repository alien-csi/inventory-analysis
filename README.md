# Citizen science projects on alien species in Europe

This repository contains the code to analyze survey responses described and published in [Price-Jones et al. 2022](https://doi.org/10.5281/zenodo.4719259). This survey relates to COST (European Cooperation in Science and Technology) Action CA17122 - Alien CSI - Increasing understanding of alien species through citizen science (see https://alien-csi.eu/). The main aim of this survey was to collect information on Citizen Science projects/initiatives involving alien species in European Member States and some neighbouring countries.

## Workflow

The raw dataset resulting from the survey was transformed to allow further analysis in R. This resulted in [processed_data.csv](https://github.com/alien-csi/inventory-analysis/blob/master/data/processed_data.csv). The analyses are described in [analysis.Rmd](https://github.com/alien-csi/inventory-analysis/blob/master/src/analysis.Rmd) and can be obtained after running the script.

## Related publications

* [Raw and processed data on Zenodo](https://doi.org/10.5281/zenodo.4719259)
* Scientific paper discussing the results (to be added)

## Repo structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). 

```
├── README.md         : Description of this repository
├── LICENSE           : Repository license
├── inventory-analysis.Rproj : RStudio project file
├── .gitignore        : Files and directories to be ignored by git
│
├── data              : Processed dataset, input for the analyses
│
├── docs              : Repository website GENERATED
│
└── src
    ├── analysis.Rmd : script to analyse survey responses
    ├── _site.yml          : Settings to build website in docs/
    └── index.Rmd          : Template for website homepage
```

## Contributors

[List of contributors](https://github.com/alien-csi/inventory-analysis/graphs/contributors)


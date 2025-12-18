## Revisiting MindScape: Behavioral and Linguistic Insights from Contextual and Generic Prompt Journaling

Functionality:
All the codes ran successfully and the results can be reproduced. However, the condition is that you have to have access to the MindScape Study Datasets (which is allowed to 
share publicly yet). Therefore, we are not sharing the datasets in this github. 

Organization and readability: 

`nadiaCode`: This is a folder of codes where you will find the results of the Report sections from 4.1 to 4.4.
- Behavioral signals (sleep, physical activity, digital habits, social interaction)
- Linguistic and emotional content of journal entries
- Journaling consistency and engagement over time

The analyses are primarily conducted using **Python** and **Jupyter Notebooks**.

## Notebooks

- `behavior_digitalhabit.ipynb` — Analysis of digital usage behaviors
- `behavior_physical.ipynb` — Physical activity feature analysis
- `behavior_sleep.ipynb` — Sleep behavior analysis
- `behavior_socialInt.ipynb` — Social interaction metrics
- `content.ipynb` — Journal content and linguistic analysis
- `filtering.ipynb` — Data cleaning and preprocessing
- `journal_prompt.ipynb` — Prompt categorization and analysis

(Add yours)


## Methods & Tools

Python (pandas, numpy, scipy, matplotlib, seaborn)

Jupyter Notebook

Dictionary-based and statistical analysis methods

Behavioral feature aggregation across study weeks

## How to Run Code

For running any files from `nadiaCode` (assuming you have the datasets in your local), you would run `filtering.ipynb` for pre-processing the data. 
Afterwards, you can follow the codes or the files to re-run to produce the results and graph.



## Notes

Raw data files are not included in this repository.

Notebooks assume preprocessed datasets with appropriate week labels and participant IDs.

macOS system files (.DS_Store) are ignored.

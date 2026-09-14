# FoodHub Data Analysis

[![View live report](https://img.shields.io/badge/Report-View%20live%20report-blue)](https://afrozejehan.github.io/fds-project/)
[![Notebook](https://img.shields.io/badge/Notebook-View%20analysis-orange)](notebooks/FDS_Project_LearnerNotebook_FullCode.ipynb)

FoodHub order analysis completed for the MIT Professional Education Applied
Data Science Program: *Leveraging AI for Effective Decision-Making*.

## Objective and business context

FoodHub is a food-aggregation platform that connects customers with
restaurants and delivery riders. This analysis uses historical order records
to understand restaurant and cuisine demand, customer ratings, order value,
and delivery performance. The goal is to support better customer experience,
restaurant partnerships, rider allocation, and promotional decisions.

## Methodology

The supplied notebook performs data-quality checks, descriptive statistics,
univariate and multivariate exploration, and business-question analysis. It
examines order volume by cuisine, restaurant, and day type; order cost and
ratings; preparation and delivery times; repeat-customer activity; restaurant
promotion criteria; and an illustrative revenue calculation. The original
notebook and rendered report remain unchanged.

## Results and insights

The [results notes](docs/results.md) summarize findings supported by the
existing notebook and report. Highlights include:

- 1,898 unique orders are analyzed.
- American, Japanese, and Italian cuisines account for about 71% of orders.
- 38.8% of orders have no customer rating.
- Half of orders cost $14 or less, indicating price sensitivity.
- Weekend delivery takes about 5–6 minutes longer on average than weekday
  delivery.
- 10.54% of orders take more than 60 minutes from order placement through
  delivery.

These are educational analysis outputs, not production KPIs. See the report
for the original tables and visual context.

## How to view or run

- **[Open the live report](https://afrozejehan.github.io/fds-project/)** for the
  easiest review experience.
- Open the [rendered report](docs/index.html) locally, or inspect the
  [source notebook](notebooks/FDS_Project_LearnerNotebook_FullCode.ipynb).
- To rerun the notebook, install the packages in
  [`requirements.txt`](requirements.txt), place `foodhub_order.csv` in the
  project root, and update the notebook's data path if needed. The CSV is
  intentionally ignored by Git and is not redistributed here.

## Repository structure

```text
.
├── docs/
│   ├── data-dictionary.md
│   ├── index.html
│   └── results.md
├── notebooks/
│   └── FDS_Project_LearnerNotebook_FullCode.ipynb
├── requirements.txt
└── README.md
```

## Data and reproducibility

The local `foodhub_order.csv` contains the source columns described in the
[data dictionary](docs/data-dictionary.md), but remains ignored as an existing
local data artifact. Reproducing the analysis requires that data file and the
notebook's original environment/path. Results in this repository are
transcribed from the supplied notebook and rendered report; no new metrics are
claimed here.

## Limitations

The dataset represents a historical sample and includes a single customer
rating field, with many ratings missing. Weekend/weekday comparisons and
revenue figures should therefore be treated as exploratory. The analysis does
not establish causal effects or replace operational monitoring and validation.

## Attribution and license

Developed for the MIT PE Applied Data Science Program: *Leveraging AI for
Effective Decision-Making*. Released under the [MIT License](LICENSE).

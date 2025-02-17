# proxy-estimation-for-race
This repository contains code to implement and compare proxy estimation methods for inferring race from limited demographic data. It includes implementations, curated datasets, testing scripts, and an interactive decision flowchart to help practitioners select the most appropriate method for their specific context.  

## Repository Structure

```text
proxy-estimation-methods/
├── README.md              # This file
├── LICENSE                # Licensing info
├── requirements.txt       # Python dependencies
├── docs/                  # Documentation files
│   ├── methodology.md     # Detailed project methodology
│   ├── user_guide.md      # How-to guide for using the codebase
│   └── decision_flowchart.md  # Explanation of the decision flowchart
├── data/                  # Datasets used in the project
│   ├── raw/               # Original, unprocessed datasets
│   ├── processed/         # Data after cleaning/preprocessing
│   └── curated/           # Curated datasets for evaluations
├── src/                   # Source code
│   ├── bisg/              # Implementation of the BISG method
│   │   ├── __init__.py
│   │   └── bisg.py
│   ├── ml_methods/        # Alternative proxy estimation methods using ML
│   │   ├── __init__.py
│   │   └── classifier.py
│   ├── flowchart/         # Code for the interactive decision flowchart
│   │   ├── __init__.py
│   │   └── flowchart.py
│   └── utils/             # Utility functions and helpers
│       ├── __init__.py
│       └── data_utils.py
└── tests/                 # Unit tests for the codebase
    ├── test_bisg.py
    ├── test_classifier.py
    └── test_flowchart.py
```

# Contact
For any questions, suggestions, or contributions, please email the project maintainers at [samdeet_khan@brown.edu](mailto:samdeet_khan@brown.edu), [yixun_kang@brown.edu](mailto:yixun_kang@brown.edu), and [letian_yu@brown.edu](mailto:letian_yu@brown.edu). We welcome feedback and collaboration!

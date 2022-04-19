# boilerplate-ml-setup

# Usage

## Loading & Cleaning
From the `/scripts` directory, run:

```
python3 load_preprocess_data.py --raw-data-path '../data/raw/raw_review_data.json' --output-dir '../data/interim/'
```

This will generate the clean data to a new file (`clean_review_data.json`) in the `\interim` directory.

## Featurizer
From the `/scripts` directory, run:

```
python3 featurize_data.py --interim-data-path '../data/interim/clean_review_data.json' --output-dir '../data/interim/'
```

This will generate the clean data to a new file (`featurized_data.json`) in the `\interim` directory.
# Inferactive datasets


In the [datasets](datasets/) directory, you'll find csv files.

In the [metadata](metadata/) directory, you'll find corresponding metadata in YAML format. The metadata includes info about where the data came from, and sample analyses and related stories.

Datasets:

- ca-city-salaries [csv](datasets/ca-city-salaries.csv) [metadata](metadata/ca-city-salaries.yaml)
- fec-independent-expenditures [csv](datasets/fec-independent-expenditures.csv) [metadata](metadata/fec-independent-expenditures.yaml)
- ssa-babynames-illinois [csv](datasets/ssa-babynames-illinois.csv) [metadata](metadata/ssa-babynames-illinois.yaml)
- us-presidental-election-county-results [csv](datasets/us-presidental-election-county-results.csv) [metadata](metadata/us-presidental-election-county-results.yaml)
- usgs-earthquakes-contiguous-united-states [csv](datasets/usgs-earthquakes-contiguous-united-states.csv) [metadata](metadata/usgs-earthquakes-contiguous-united-states.yaml)
- vice-shot-by-cops [csv](datasets/vice-shot-by-cops.csv) [metadata](metadata/vice-shot-by-cops.yaml)
- wapo-police-shootings [csv](datasets/wapo-police-shootings.csv) [metadata](metadata/wapo-police-shootings.yaml)





## Python snippet to verify proper yaml


(quickie purposes)

```py
FNAME = 'metadata/wapo-police-shootings.yaml'

import yaml
from pathlib import Path
txt = Path(FNAME).read_text()
metadata = yaml.load(txt)
```

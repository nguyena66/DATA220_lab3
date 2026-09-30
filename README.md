# Campus space project

## Purpose
To summarize spaces.

## Data
Use data/sample/campus_spaces.csv, a synthetic teaching sample.
See [the data dictionary](docs/data_dictionary.md).
## Repository structure
scripts/ contains code.
data/sample/ contains the tracked sample.
docs/ contains project documentation.
outputs/ contains generated results and is ignored.

## Requirements
Rscript (R) version 4.3.3 (2024-02-29); no additional R packages are needed.

## How to run
Open a terminal in the repository root, then run:
```bash
Rscript scripts/summarize_spaces.R data/sample/campus_spaces.csv
```

## Expected result
Row count: 12
Occupancy rate: 77.0%
Busiest observed space: S103

## Outputs
This script prints its summary in the terminal and does not create a result file.

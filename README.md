# BIOSTAT707

## Checkpoint 1

To run the code, please place the 4,000 record files in `data/set-a/` and the outcome file at `data/Outcomes-a.txt`, then run `pixi run --locked checkpoint1` from the repository root. This executes `checkpoint1.ipynb` and generates `output/checkpoint1.html`, `output/set-a_long.csv`, `output/set-a_wide.csv`, missingness figures, and a mortality comparison table.


## Checkpoint 2

Please place the 4,000 set-a record files in `data/set-a/` and the outcome file at `data/Outcomes-a.txt`.

From the repository root, run:

```bash
pixi run --locked checkpoint2
```

This executes `checkpoint2.ipynb` and creates `output/checkpoint2.html`. It also saves the final fitted model and out-of-fold predictions under `output/`.

Runtime on my MacBook Air: approximately 7 min and 10 seconds.



## Checkpoint 3

From the repository root, run:

```bash
pixi run --locked checkpoint3
```

Set-a records and outcomes are read from `data/set-a/` and `data/Outcomes-a.txt`. Set-b, set-c, and their outcome files are read from `data/physionet.org/files/challenge-2012/1.0.0/`.

The analysis loads the saved Checkpoint 2 model, predictor list, comparison table, and coefficient table from `output/`. It creates `output/checkpoint3.html`.

Runtime on my MacBook Air: approximately 1 minute 52 seconds.

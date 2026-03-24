<ins>Workflow to run on windows:</ins>

Figure out how to set up environment with conda

```
conda env create -f environment_windows.yml
```

```
source activate crash-model || conda activate crash-model
```

Once enviroment is activated run:

```
python initialize_city.py -city "Manchester, United Kingdom" -f manchester -crash ../manchester-crash-data/manchester-crash-data/mcr-crash-data-ready.csv
```

In src, run:

```
python pipeline.py -c || python pipeline.py -c config/config_manchester.yml
```

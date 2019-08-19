## Creating a cosima-cookbook test environment

Clone this repo to a suitable directory

Load an `conda` environment

```
module use /g/data3/hh5/public/modules
module load conda/python3
```

Create the test environment
```
conda env create -f environment.yml 
```

Activate the environment
```
conda activate cc-test
```

The first time you may need to first run
```
conda init bash
```

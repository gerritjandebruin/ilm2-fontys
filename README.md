# Missing data

## Setup python venv

```commandline
py -m venv venv
```

### Activate environment

```commandline
venv/Scripts/activate
```

### Install packages

```commandline
pip install -r requirments.txt
```

## Run

Run the code in main.ipynb, this will fetch all the data available in the https://ilm2.site.dustmonitoring.nl/download api in 10 minute segments.

Then parse this data into a csv file per location.

The total amount of missing values will be calculated and printed at the end of the file.

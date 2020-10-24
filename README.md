# Gentrification Prediction and Analysis 

_Submission to 2020 European Regional Data Open._

The data included in this repository is tracked using Git LFS, please ensure it is installed before cloning. Install all the dependencies through

```bash
pip install -r requirements.txt
```

GPU acceleration can be enabled by running

```bash
plaidml-setup
```

This product uses the Census Bureau Data API but is not endorsed or certified by the Census Bureau.

To requests new data, export your api key as an environemnt variable `CENSUS_API_KEY`.

List of 2009 ACS5 variables https://api.census.gov/data/2009/acs/acs5/variables.html
(warning: if you're using Chrome, you'll need 1.3 GB of RAM just to load this page)
If you don't mind JSON, then use the file in the data directory.

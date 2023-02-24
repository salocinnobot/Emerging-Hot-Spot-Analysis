# Emerging-Hot-Spot-Analysis
An aggregate spatial-temporal analysis on sale activity using property sales data partitioned across sections and subvisions in Miami 

## Project Poster
***
The final project poster can be found in the Final Layout.pdf file, which features a write-up of the data, methods, and results produced.

***Unfortunately, this repository does not support replicability. The code (Python/ArcGIS) and data used to develop this project were corrupted during their development, and they are mostly unrecoverable.***


## Data Pre-Processing
***

**To reproduce the working environment**
1) Clone the repository
```bash
git clone repo-url
```
2) Change directory to the root project directory
3) Create a virtual environment using venv, and activate it
```bash
python3 -m venv env
. env/bin/activate
```
4) Install all the required libraries to the virtual environment
```bash
pip install -r requirements.txt
```

**geo_data.ipynb**:
Contains geo-data pre-processing that produced our data in the data/ directory

***ps_full.pkl***: was not included into data, as the size exceeded Github's upload limit

## Considerations 
***
The importance of docmentation cannot be understated, thus I will let this serve as a commitment of respponsibility as a data-scientist in ensuring operability, interoperability, interpretability, accuracy, and soundness.

# DE Assessment
This made by Thien Pham to answer the DE Assessment.

# Requirements

- unzip file data.zip inside this folder.
- python=3.8

# Installation

1. open terminal
2. python3.8 -m venv env
3. source env/bin/activate
4. pip install -r requirements.txt
5. jupyter notebook
6. open localhost:8888 and input the token showed in terminal.
7. open Q1.ipynb and Q2.ipynb notebooks.
8. The answer of Q1 & Q2 is these notebooks.

# Notebook Description

All notebooks are structured as follows:
1. Data Dictionary: The dictionary of the result of process described in that notebook.
  - Some description of table/file.
  - 1.x. Column Description
2. Data Extraction: The extraction process.
3. Data Transformation: The transformation process.
  - 3.0. Pre-Transformation
  - 3.x. Transformation Step
  - 3.last. Post-Transformation
4. Data Loading: The loading process.
5. Unit Testing: Apply some tests to make sure the result was good enough.
  - 5.1. Test Metadata
  - 5.2. Test Schema
  - 5.3. Test Head
  - 5.x. Test Sample

# Author
Thien Pham

# Credits

- https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page used for Green Trips Data Dictionary.
- https://nominatim.openstreetmap.org/ui/details.html?osmtype=W&osmid=158042008&class=aeroway used for JFK Airport bounding box.
- https://arrow.apache.org/docs/python/parquet.html used for unsterdanding parquet type.
- https://shapely.readthedocs.io/en/stable/ used for checking a point may be contained by a polygon or not.


# License
None

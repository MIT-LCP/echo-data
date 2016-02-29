# Structuring data from echocardiography reports

This repository contains code for structuring data from echocardiography reports.
This data can be used in studying the relationship between cardiac function and patient health.

# How to access the data

If you are simply interested in accessing the data, it is available on PhysioNetWorks: https://physionet.org/users/

PhysioNet Works is an online repository allowing selective access to data for credentialed users. In order to directly access the data, users must be accredited to use the MIMIC-III clinical database.
If you do not have the appropriate access, you can acquire it by following the steps detailed [here](http://mimic.physionet.org/gettingstarted/access/).

Once you have access to the MIMIC-III database, log in to PhysioNetWorks with your username/password. 
Go to the "MIMIC-III Related Work" project, and scroll down to "Echocardiography data". The CSV files are available to download.
They can be linked back to the MIMIC-III database using `SUBJECT_ID`, `HADM_ID` or `ICUSTAY_ID`.

# How to use this repository

Before using this repository, you'll need to:

1. Install Python 2.7
      * The numpy, pandas, and psycopg2 packages are also required
2. Install PostgreSQL 9.4 or higher
3. Install MIMIC-III locally on your system
      * This requires access to the MIMIC-III database, detailed [here](http://mimic.physionet.org/gettingstarted/access/).
      * An install guide is available [here](http://mimic.physionet.org/tutorials/install-mimic-locally-ubuntu/) (Ubuntu/Mac OS X) or [here](http://mimic.physionet.org/tutorials/install-mimic-locally-windows/) (Windows).

Once these are available on your system, you can begin running the Python script which will generate 
  

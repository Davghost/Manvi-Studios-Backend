# Manvi Studios Backend

This repository contains the backend code for the Manvi Studios project.

## Required Data File

This project requires an external CSV file to work correctly.

The script `import_school.py` reads this CSV file and imports all data into the database.  
It processes official data and loads essential information about **all schools in Brazil**.

## Download Instructions

Download the official dataset from the link below:

https://download.inep.gov.br/dados_abertos/microdados_censo_escolar_2024.zip

After downloading, extract the ZIP file.

Inside the extracted folder, locate the following file:
microdados_censo_escolar_2024/dados/microdados_ed_basica_2024.csv


Copy **only this file** and place it in the project at the following path: data/microdados_ed_basica_2024.csv

## Important Notes

- Only the file `microdados_ed_basica_2024.csv` is required
- All other files from the dataset are **not necessary**
- The CSV file is not included in this repository due to its size
- Without this file, the data import process will not work


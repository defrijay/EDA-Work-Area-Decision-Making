# Exploratory Data Analysis: Determining Work Areas in West Java

## Table of Contents
1. [Introduction](#introduction)
2. [Development Team](#development-team)
3. [Creation Date](#creation-date)
4. [Analysis Questions](#analysis-questions)
5. [Datasets Used](#datasets-used)
6. [Data Analysis Process](#data-analysis-process)
7. [Technologies and Libraries Used](#technologies-and-libraries-used)
8. [Final Results](#final-results)
9. [How to Run the Project](#how-to-run-the-project)
10. [File Structure](#file-structure)
11. [Notes](#notes)

## Introduction
This project aims to assist individuals in determining work locations in West Java by considering various factors, such as expenditure per capita, minimum wages, the number of employed residents, and the poverty line. The data used is sourced from the Central Statistics Agency (BPS) and the Department of Manpower and Transmigration of West Java.

## Development Team
Group 3:
1. Boy Aditya Rohmaulana (2203488)
2. Defrizal Yahdiyan Risyad (2206131)
3. Muhamad Furqon Al-Haqqi (2207207)
4. Raya Cahya Nurani (2205714)
5. Septiani Eka Putri (2206000)

## Creation Date
- Start: September 24, 2023
- Revision: October 1, 2023

## Analysis Questions
1. Districts/Cities in West Java Province with the 5 highest and 5 lowest minimum wages in 2023.
2. Trends in minimum wages in districts/cities over the past few years.
3. Correlation between expenditure per capita, minimum wages, the number of employed residents, and the poverty line per capita.
4. Distribution of data on expenditure per capita, minimum wages, the number of employed residents, and the poverty line per capita.

## Datasets Used
1. **Expenditure Per Capita (bps-od_17106_jml_pengeluaran_per_kapita__kabupatenkota_data.csv)**
2. **Minimum Wages (disnakertrans-od_19868_daftar_upah_minimum_kabupatenkota_di_drh_prov_jabar_data.csv)**
3. **Number of Employed Residents (disnakertrans-od_15793_jumlah_penduduk_yang_bekerja_berdasarkan_kabupatenkota_data.csv)**
4. **Poverty Line (bps-od_17110_angka_garis_kemiskinan_per_kapita_per_bulan__kabupaten_data.csv)**
5. **Inflation Rate (bps-od_17137_nilai_inflasi_berdasarkan_tujuh_kota_data.csv)**

## Data Analysis Process
1. **Data Exploration**: Reviewing dataset structures, cleaning data (removing unnecessary columns, handling null/NaN values).
2. **Data Averaging**: Calculating averages for each dataset based on districts/cities.
3. **Data Merging**: Merging all datasets for correlation and distribution analysis.
4. **Normalization**: Applying Min-Max normalization to ensure data consistency.

## Technologies and Libraries Used
- **Programming Language**: Python
- **Libraries**:
  - `numpy` and `pandas`: Data processing
  - `matplotlib` and `seaborn`: Data visualization

## Final Results
1. Districts/Cities with the highest minimum wages:
   - Karawang has the highest minimum wage due to low inflation and moderate population density.
   
2. Districts/Cities with the lowest minimum wages:
   - Banjar has the lowest minimum wage due to lower living costs and smaller population density.

3. Inflation analysis:
   - Bekasi has the highest inflation due to its large population.
   - Cirebon has the lowest inflation due to lower living needs.

4. Data distribution and correlation:
   - Correlations between expenditure per capita, minimum wages, the number of employed residents, and the poverty line provide insights into the relationships among factors in determining optimal work locations.

## How to Run the Project
1. Ensure Python and the required libraries are installed.
2. Place all datasets in the same directory as the script.
3. Run the script file to perform the analysis.

## File Structure
- `bps-od_17106_jml_pengeluaran_per_kapita__kabupatenkota_data.csv`: Expenditure per capita dataset
- `disnakertrans-od_19868_daftar_upah_minimum_kabupatenkota_di_drh_prov_jabar_data.csv`: Minimum wage dataset
- `disnakertrans-od_15793_jumlah_penduduk_yang_bekerja_berdasarkan_kabupatenkota_data.csv`: Number of employed residents dataset
- `bps-od_17110_angka_garis_kemiskinan_per_kapita_per_bulan__kabupaten_data.csv`: Poverty line dataset
- `bps-od_17137_nilai_inflasi_berdasarkan_tujuh_kota_data.csv`: Inflation dataset

## Notes
This project can be further developed to include predictive analysis, such as using machine learning algorithms to recommend optimal work locations based on individual preferences.
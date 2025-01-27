# Exploratory Data Analysis: Determining Work Areas in West Java

## Introduction
This project aims to assist individuals in determining work locations in West Java by considering various factors, such as per capita expenditure, minimum wage, number of employed population, and poverty line. The data used are sourced from the Central Statistics Agency (BPS) and the West Java Manpower and Transmigration Office.

## Development Team
Group 3:
1. Boy Aditya Rohmaulana (2203488)
2. Defrizal Yahdiyan Risyad (2206131)
3. Muhamad Furqon Al-Haqqi (2207207)
4. Raya Cahya Nurani (2205714)
5. Septiani Eka Putri (2206000)

## Creation Date
- Initial: September 24, 2023
- Revised: October 1, 2023

## Analysis Questions
1. Districts/Cities in West Java Province with the 5 highest and 5 lowest Minimum Wages in 2023.
2. Trends in District/City Minimum Wages over the past few years.
3. Correlation between per capita expenditure, minimum wage, number of employed population, and per capita poverty line.
4. Distribution of data on per capita expenditure, minimum wage, number of employed population, and per capita poverty line.

## Datasets Used
1. **Per Capita Expenditure (bps-od_17106_total_per_capita_expenditure_district_city_data.csv)**
2. **Minimum Wage (disnakertrans-od_19868_list_of_minimum_wage_district_city_in_drh_prov_jabar_data.csv)**
3. **Number of Employed Population (disnakertrans-od_15793_number_of_employed_population_by_district_city_data.csv)**
4. **Poverty Line (bps-od_17110_number_of_poverty_line_per_capita_per_month__district_data.csv)**
5. **Inflation Rate (bps-od_17137_inflation_value_based_on_seven_cities_data.csv)**

## Data Analysis Process
1. **Data Exploration**: Reviewing the dataset structure, cleaning the data (removing unnecessary columns, handling null/NaN values).
2. **Data Average**: Calculating the average for each dataset based on Regency/City.
3. **Data Merge**: Combining all datasets for correlation and distribution analysis.
4. **Normalization**: Performing Min-Max normalization to ensure data consistency.

## Technologies and Libraries Used
- **Programming Language**: Python
- **Libraries**:
- `numpy` and `pandas`: Data processing
- `matplotlib` and `seaborn`: Data visualization

## Final Results
1. Districts/Cities with the Highest Minimum Wages:
- Karawang has the highest UMK due to low inflation and a relatively low population density.

2. Districts/Cities with the Lowest Minimum Wages:
- Banjar has the lowest UMK due to lower cost of living and population density.

3. Inflation analysis:
- Bekasi has the highest inflation due to its high population.
- Cirebon has the lowest inflation due to lower living costs.

4. Distribution and correlation data:
- The correlation between per capita expenditure, UMK, number of employed population, and poverty line provides an overview of the relationship between factors in determining the optimal work location.

## How to Run the Project
1. Make sure Python and the required libraries are installed.
2. Put all datasets in the same directory as the script.
3. Run the script file to perform the analysis.

## File Structure
- `bps-od_17106_jml_pengeluaran_per_kapita__kabupatenkota_data.csv`: Per capita expenditure dataset
- `disnakertrans-od_19868_daftar_upah_minimum_kabupatenkota_di_drh_prov_jabar_data.csv`: Minimum wage dataset
- `disnakertrans-od_15793_jumlah_penduduk_yang_bekerja_berdasarkan_kabupatenkota_data.csv`: Dataset of number of working population
- `bps-od_17110_jumlah_lin_kemiskinan_per_capita_per_bulan__kabupaten_data.csv`: Dataset of poverty line
- `bps-od_17137_nilai_inflation_berdasarkan_tujuh_kota_data.csv`: Dataset of inflation

## Note
This project could be further developed to include predictive analytics, such as using machine learning algorithms to recommend optimal work locations based on individual preferences.
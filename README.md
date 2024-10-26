# DS4002-Project2 - Group 19
Elaine Shagdarjav, Jason Albanese, Brian Xiao

## Section 1: Software and Platform
- For our time-series analysis, we employed the ARIMA model from the statmodels package
- We obtained data for US legal oermenant residents in XLSX format from the online Migration Policy Institute webpage
- We obstained historical unemployment rates in XLSX format from statista.
- We used CloudConvert to conver the XLSX document to CSV
- The CSV was then opened in python, and the ARIMA model was employed. We utilized additional packages, detailed below.
- Windows and Mac were used to run software.

### Section 2: Documentation map
There are three important folders inside of our project folder

SCRIPTS folder
- clean.ipynb
- analysis.ipynb
- analysis2.ipynb

DATA folder
- cleaned_unemployment_data_1890-1988.csv
- cleaned_unemployment_data_1948_2022.csv
- cleaned_unemployment_data_1990_2022.csv
- combined_data.csv
- GDP_percent_change.csv
- GDP.csv
- new_immigration.csv
- unemployment-1890-1988.csv
- unemployment-1990-2022.csv
- us_population.csv

OUTPUT Folder
- Contains output for analysis2.ipynb, including graphs

#### Section 3: Instructions
1. Clone this repository
2. Install the most up-to-date version of Python
3. Download the libraries and packages listed below (if you do not already possess them). This can be done through the terminal with the following syntax: pip install [library]:
    - pandas
    - matplotlib
    - numpy
    - statsmodels
        - [.tsa.statstools.adfuller] adfuller
        - [.graphics.tsaplots.] plot_acf, plot_pacf
        - [.tsa.arima.models] ARIMA
    - from statsmodels.tsa.stattools import adfuller
    - from statsmodels.graphics.tsaplots import plot_acf, plot_pacf
    - from statsmodels.tsa.arima.model import ARIMA
4. Run all of the code blocks in analysis2.ipynb in order

[1] CloudConvert. (n.d.). Convert XLSX to CSV. CloudConvert. Retrieved October 18, 2024,
from https://cloudconvert.com/xlsx-to-csv
[2] Migration Policy Institute. (n.d.). Annual number of U.S. legal permanent residents. Retrieved
October 18, 2024, from
https://www.migrationpolicy.org/programs/data-hub/charts/Annual-Number-of-US-Legal-Perman
ent-Residents?width=850&height=850&iframe=true
[3] Statista. (n.d.). Historical unemployment rate in the United States. Retrieved October 18,
2024, from
https://www.statista.com/statistics/1315397/united-states-unemployment-number-rate-historical/
https://www.machinelearningmastery.com/arima-for-time-series-forecasting-with-python/
https://www.projectpro.io/article/how-to-build-arima-model-in-python/544


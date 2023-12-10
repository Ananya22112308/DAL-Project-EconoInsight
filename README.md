# DAL-Project-EconoInsight <br>

## Overview <br>
The project aims to explore the determinants of economic growth in a range of countries, encompassing both developed and developing nations, each with its unique narrative. The primary focus is on essential economic indicators such as GDP, inflation, money supply, exchange rates, and foreign direct investment (FDI). These factors collectively contribute to assessing and understanding the overall economic well-being of a country.

## EconoInsight Project Setup <br>
### Extract Data Files<br>
Download the Zip Folder of the Project and Unzip the data files into the appropriate folder. Make sure to download the CSV file named finaldata.<br>
### Update File Paths<br>
Update file paths in the Django settings and other relevant files to reflect the location of your data files and any other configurations. Make sure to change the File Path in the views.py file in the app folder.<br>
### Migrate Database<br>
Run the below command in your command prompt in VS Code.<br>
``python manage.py migrate``<br>

### Run the Server<br>

``python manage.py runserver``<br>

### Go to the Site<br>
Visit http://127.0.0.1:8000/data-analysis/data/ in your browser to access the EconoInsight project.<br>

### Additional Instructions<br>
Make sure that you have the following  installed in your system:<br>
Python<br>
Django<br>

Use the below code (in your console) to install libraries like Pandas, ydata_profiling, numpy, matplotlib,scikit-learn , scipy , seaborn.<br>
``pip install pandas``<br>

## Usage Guidelines <br>
Follow the setup steps mentioned above to ensure a smooth installation of the EconoInsight project. <br>
Visit http://127.0.0.1:8000/data-analysis/data/ to explore the main Data Analysis section of EconoInsight.<br>
Explore the interactive map to visualize GDP data across countries.Navigate through the Descriptive Statistics and Data Tab sections to understand the statistical distribution of economic indicators.Leverage the Pandas Data Profiling feature using the ydata_profiling library to gain insights into dataset characteristics.<br>
Understand the Regression Analysis section for insights into the relationships between GDP and key economic indicators.<br>
Experiment with changing variables and countries in the interactive map and plots to gain a deeper understanding of economic trends.Interpret the visualizations and data to draw conclusions about the impact of inflation, money supply, population, FDI, and exchange rates on GDP.<br>
 explore the model predictions and understand how different variables contribute to the predictions.<br>
 Have fun exploring EconoInsight and gaining valuable insights into economic indicators and their impact on GDP.



> Hope You Like our Project<br>
> Thankyou for your time :)



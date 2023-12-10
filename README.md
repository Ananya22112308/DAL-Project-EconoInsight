# DAL-Project-EconoInsight
##EconoInsight Project Setup
###Extract Data Files
Download the Zip Folder of the Project and Unzip the data files into the appropriate folder. Make sure to download the CSV file named finaldata.
###Update File Paths
Update file paths in the Django settings and other relevant files to reflect the location of your data files and any other configurations. Make sure to change the File Path in the views.py file in the app folder.
###Migrate Database
Run the below command in your command prompt in VS Code.
``python manage.py migrate``

###Run the Server

``python manage.py runserver``

###Go to the Site
Visit http://127.0.0.1:8000/data-analysis/data/ in your browser to access the EconoInsight project.

###Additional Instructions
Make sure that you have the following  installed in your system:
Python
Django
Use the below code (in your console) to install libraries like Pandas, ydata_profiling, numpy, matplotlib,scikit-learn , scipy , seaborn.
``pip install pandas``
Hope You Like our Project
Thankyou for your time :)



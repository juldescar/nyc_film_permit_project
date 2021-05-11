# Filming New York

Created for INFO 664 Programming for Cultural Heritage with Matt Miller at Pratt Institute, Spring 2021

This project uses the NYC Open Data Film Permits dataset about to explore filming trends around the city. The dataset contains information on film permits issued from 2012 through early 2021. For my purposes, I looked specifically at permits with the EventType “Shooting Permit” and “DCAS Prep/Shoot/Wrap Permit,” which covers permits on Department of Citywide Administrative Services property. I investigated which areas of the city were filmed most often, what types of productions were filmed where, and how many productions were filmed in each borough annually. 

I created three Python scripts that can be used to analyze the data:

zip_code_count.py 
	Creates a dictionary showing the total count of film permits by zip code
	Exports the dictionary to a CSV file for visualization

category_by_zip_code.py
	Creates a nested dictionary showing the count of film permits for each category of production by zip code
	Using the pandas module, exports the nested dictionary to a CSV file for visualization

category_by_borough.py
	Using pandas, creates a refined CSV file that can be used to visualize annual filming trends
	Uses the refined CSV file and pandas to create a dataframe that shows the count of permits for each category of production by borough
	Uses pandas to export the dataframe to a CSV file for visualization 

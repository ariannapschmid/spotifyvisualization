DESCRIPTION

This package, "Analyzing Popular Music through Spotify and Visualization (Team 157)", is designed to analyze popular music trends from 2012-1022 using Spotify data and visualizations in Tableau. 
It includes data files with Spotify audio features for top tracks and control data for Metal, Opera, and Classical Music tracks. 
The package also contains Python scripts for gathering and processing Spotify data, R Markdown files for Exploratory Data Analysis and Modeling, and a Tableau file for visualization.

INSTALLATION

To run our visualization, we suggest users to download the Tableau Desktop app. Then, simply open the Tableau workbook and interact with the visualization. 
Note: You might already have Tableau from this class’ first assignment. If you do not have Tableau installed, you can request a demo license at https://www.tableau.com/academic/students.
You will have to register and an activation key will be sent to your Georgia Tech email address. 

EXECUTION

The output of the python code will generate the following CSV files:
- Top 50 Songs.csv
- Control Data.csv
- all_songs.csv
- top_100_df.csv

These CSV files were used "behind the scenes" and need not be imported into Tableau for the final visualization. Still, they can be regenerated by running the Python scripts 'parsing-playlists.ipynb' and 'parsing-playlists (Opera).ipynb'. It is not a requirement to re-run this code. 
The R Markdown files 'EDA.Rmd' and 'Modeling and Data Consolidation.Rmd' for Exploratory Data Analysis and Modeling will run based on the CSV files. 

Finally, open the folder titled CODE, and open the subfolder titled Final Visualization. You can now view the final Tableau file 'final.twb'. We recommend viewing and exploring it through "presentation" mode.

The dashboard should work as is since we've provided a hyper file.
However, if you encounter any issues with the data, you will need to import the following 2 CSV files into the workbook: 
- playlists - Sheet2 (1)
- all_songs2 (1)



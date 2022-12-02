# Movie-Data-Cleaning

In this project, I cleaned a dataset concerning Movies and TV shows using Microsoft Excel.

In the excel file, the first sheet (Original Data) is the original dataset. The second sheet (Workspace), is where I performed most of the cleaning/dirty work. The third sheet (Cleaned Data) is the cleaned version of the dataset.

This dataset had many dirty elements in it, making it optimal to clean thoroughly. Among them were:  
&emsp; 1) Duplicate values  
&emsp; 2) Blank lines found before and after cell contents  
&emsp; 3) Some characters were replaced with random characters  
&emsp; 4) A cell's contents formatted in a data type not conducive with analysis  
&emsp; 5) Missing data  

What follows is the steps I took to clean the dataset (all performed in the Workspace sheet):  
&emsp; 1) I deleted duplicate values from the dataset  
&emsp; 2) I changed the label of the 'MOVIES' column to 'TITLES', as the former was misleading given how the dataset also includes TV shows and not just movies  
&emsp; 3) I fixed the formatting of and split the 'YEAR' column into 'START_YEAR' and 'END_YEAR' columns  
&emsp; 4) I fixed the formatting of and split the 'GENRE' column into three columns, each listing a genre of the title  
&emsp; 5) I edited the 'RATINGS' column so that missing values would be replaced by 0.0  
&emsp; 6) I fixed the formatting of the 'ONE-LINE' column and renamed it to 'SYNOPSIS'  
&emsp; 7) I split the STARS column into three columns: a 'DIRECTORS', 'ACTORS_WITH_DIRECTOR', and 'ACTORS_WITHOUT_DIRECTOR' column  
&emsp; 8) From there, using the 'ACTORS_WITH_DIRECTOR' and 'ACTORS_WITHOUT_DIRECTOR' columns, I created four columns, each listing an actor from that movie/TV show  
&emsp; 9) I edited the 'VOTES' column so that missing values would be replaced by 0  
&emsp; 10) I converted the given data in the 'GROSS' column to a number, as well as filled in missing values with 0  
&emsp; 11) Below the table, I calculated the number of 'missing' values in each row, as well as the percentage of 'missing' values in each row  
&emsp; 12) I copied all of the columns that had approximately or less than 15% of 'missing' values into the Cleaned Data sheet.  

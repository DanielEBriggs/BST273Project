Name: Daniel Briggs
Email: dbriggs@hsph.harvard.edu
https://github.com/DanielEBriggs/BST273Project

Experience: 

This was a well-constructed project. It was interesting 
to combine everything we had learned in this class
and present it as a culminating experience. The workload for this project
was reasonable. I completed the majority of the project in a 2-3 hours.
I wish I had used a pandas dataframe rather than reading in each series.
That would have made my workload considerably lighter. 

Project Description:

This project will take a generic .tsv file with numerical data and categorical data
and can create a scatter plot. The script will then save the resulting file as a .png object,
and will send the file to either the current working directory or the user specified directory. 
The resulting plot is shown after saving.

Modules:

os 
sys
argparse
re
numpy as np
pandas as pd
matplotlib.pyplot as plt
matplotlib.patches as mpatches

Sample Input File:

This script will be able to process any reasonable data set that is saved with a .tsv file format. 
The first row of the data set should contain column names.
The header of the data set will also be indicated with a pound symbol (#).

For instance with the iris data set, we have 150 observations of 5 variables. 
The variables are recorded as followed:

1. sepal length (cm) 
2. sepal width (cm) 
3. petal length (cm) 
4. petal width (cm)
5. class: 
-- Iris Setosa 
-- Iris Versicolour 
-- Iris Virginica

Consequently, the first five lines of the data set are shown as such. 

# sepal width (cm)	sepal length (cm)	petal width (cm)	petal length (cm)	class
5.1	3.5	1.4	0.2	Iris-setosa
4.9	3.0	1.4	0.2	Iris-setosa
4.7	3.2	1.3	0.2	Iris-setosa
4.6	3.1	1.5	0.2	Iris-setosa

Command To Produce Output:
	
	figure: scatterplot.png
	command: C:\Users\Daniel\Desktop\BST273> Python scatter.py iris.tsv -x 1 -y 2
	
	figure: stratifiedwithclass.png
	command: C:\Users\Daniel\Desktop\BST273> Python scatter.py iris.tsv -x 1 -y 2 -c 5 -s stratifiedwithclass.png

	figure: scatterplot.png in a new folder named NEW in C:\Users\Daniel\Desktop\NEW\
	command: C:\Users\Daniel\Desktop\BST273>Python scatter.py iris.tsv -x 4 -y 3 -c 5  -o C:\Users\Daniel\Desktop\NEW\
	
	
Output Files:

Scatter plots as a .png file format located in a the corresponding user-given directory. 
Scatter plots can be unstratified, meaning they don't use the class labels. 
Otherwise scatter plots use a color scheme to identify different classes visually. 
Without any appropriate flags, this will save a scatterplot called scatterplot.png at the current working directory.
	
Good:

I enjoyed learning about numerical and OOP. These are useful topics to me that aren't typically discussed at school.
Without much of a CS background beforehand, it was good to experience these subjects.

Bad:	

I felt like the pace of the class was slow. I know there are people who have never thought about programming before,
but I think the class could have moved a little bit faster. The most interesting subjects to me came in the last couple weeks of the course.
Also, I think introducing GitHub early on would be useful. 
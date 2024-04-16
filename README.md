R Shiny App

1.	Edit your Input .csv PSM file to contain only the abundance channels for the two samples you are comparing. Note: make sure there are no spaces in the file name, if your channel ends at say 131 make sure there is an N for the complete channel name, and if you have different number of replicates for the two samples see me about imputation.

2.	To impute missing values before analysis add in the PSM file name, replicate number and starting channel.

3.	Afterwards, apply your PD filters (i.e. high confidence, no contaminants, unique peptides > 2, etc.) by entering your imputed PSM file and your PD Protein file.

4.	Format of your Input File must have the following columns, any other columns are welcome as well. 
 


5.	See example (uni.csv and uni_gn.csv) for details on input Uniprot File and Uniprot and Gene Name File. 

6.	For input of Protein to Normalize to enter the accession. Make sure these are in your uni.csv and uni_gn.csv if they are custom to your experiment.


7.	Change Treatment/Control to the titles of your samples.

8.	Enter in a Protein of Interest, use the Gene name here.


9.	Hit run script, and scroll the zoom out to -2, 2 to see your Volcano, when everything looks good hit Download Plot.

10.	Check the Figures folder for your plots and stats table.	

Description of data analysis is described in MS_Data Analysis.docx.

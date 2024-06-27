# Remove Outliers 

Objectives:
Removal of outliers from a dataframe. Perform aggregation functions on before and after results and compare the results

#Running the Notebook in Google Colab
  1.	Open Google Colab: Go to https://colab.research.google.com/.
  2.	Upload the Notebook:
  3.	Click on "File" -> "Upload notebook" and select "Project_Capstone.ipynb" from your local machine.
  4.	Alternatively, you can upload the entire project directory (including "Project_Capstone.ipynb") to your Google Drive and open the notebook directly from there.

#Methods Used

    •	Data Manipulation (pandas,numpy)
  
    •	Data Visualization(seaborn,matplotlib)
    •	Descriptive statistics (interquartile range (IQR))


#DATA
  •	the datafile (fastfood.csv) was given by my bootcamp instructor

#Results
  • The removal of outliers had a clear impact on our data. As expected, the maximum (MAX) value dropped significantly since we removed values above a certain threshold in all three columns. However, since we didn't remove values below a threshold, the minimum (MIN) value remained unchanged. Interestingly, the median(MEDIAN) changed only slightly, suggesting that removing outliers had minimal influence on the central tendency of the data and was probably a good decision.
On the other hand, we observed significant decreases in the MEAN, standard deviation (STD), and variance (VAR) values. This indicates that the data became more symmetrical, with the MEAN values now closer to the MEDIAN. This observation is further supported by the smaller STD and VAR values, signifying a more compact data set. Consequently, our subsequent analysis is likely to be more reliable as outliers no longer skew the data.

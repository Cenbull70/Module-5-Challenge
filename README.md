# Module-5-Challenge

<p><h1>Background</h1><p></p>
</p>You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.</p>

</p>As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.</p>

</p>The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.</p>

<p><h1>Requirements</h1><p>
</p><h2>Prepare the Data<h2><p>
</p>The datasets are merged into a single DataFrame.</p>
</p>The number of mice are shown from the merged DataFrame.</p>
</p>Each duplicate mice is found based on the Mouse ID and Timepoint.</p>
</p>A clean DataFrame is created with the dropped duplicate mice.</p>
</p>The number of mice are shown from the clean DataFrame.</p>
<p><h1>Generate Summary Statistics</h1><p>
</p>The mean of the tumor volume for each regimen is calculated using groupby.</p>
</p>The media of the tumor volume for each regimen is calculated using groupby.</p>
</p>The variance of the tumor volume for each regimen is calculated using groupby.</p>
</p>The standard deviation of the tumor volume for each regimen is calculated using groupby.</p>
</p>The SEM of the tumor volume for each regimen is calculated using groupby. </p>
</p>A new DataFrame is created with using the summary statistics.</p>
</p><h2>Create Bar Charts and Pie Charts<h2>>p>
</p>A bar plot showing the total number of timepoints for all mice tested for each drug regimen using Pandas is generated.</p>
</p>A bar plot showing the total number of timepoints for all mice tested for each drug regimen using pyplot is generated.</p>
</p>A pie chart showing the distribution of unique female versus male mice using Pandas is generated. </p>
</p>A pie chart showing the distribution of unique female versus male mice using pyplot is generated.</p>
<p><h1>Calculate Quartiles, Find Outliers, and Create a Box Plot<h2><p>
</p>A DatFrame that has the last timepoint for each mouse ID is created using groupby.</p>
</p>The index of the DataFrame is reset.</p>
</p>Retrieve the maximum timepoint for each mouse.</p>
</p>The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin, are put in a list.</p>
</p>An empty list is created to fill with tumor volume data.</p>
</p>A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group </p>
</p>A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group. </p>
<p><h1>Create a Line Plot and a Scatter Plot<h2><p>
</p>A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin.</p>
</p>A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen.</p>
<p><h1>Calculate Correlation and Regression<h2><p>
</p>The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen.</p>

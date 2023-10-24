Pymaceutical Challenge

This assignment involved the use of Pandas, Matplotlib, and SciPy to generate tables and figures from clinical study data on mice identified with squamous cell carcinoma and treated with a range of drug regimens.

Resource information consisted of two Excel files: one containing a list of 249 mice with corresponding gender, age (months), weight (g), and drug regimen received, and the other file containing the results of studies on the mice according to timepoints in a 45-day range and the measures of tumor volumes and number of metastatic sites at those timepoints. The two files were merged into a single data frame through a left join based on a common mouse ID column.

From that, subsequent outputs and data frames were produced to show summary statistics as well as to support the production of bar charts, pie charts, a box plot, and a scatter plot with a regression line modeled on top.

A Jupyter notebook was used to prepare the data frames, employing code learned and 
applied from class sessions as well as code provided in the notebook itself. A number of code lines were also constructed through application from online research using the      references noted below.

Online References:

Jezrael. (2019, August 28). "Pandas group by and make a summary". Retrieved from stackoverflow.com: https://stackoverflow.com/questions/57669146/pandas-group-by-and-make-a-summary

Microsoft Bing. (2023, October). Retrieved from Bing.com: https://www.bing.com/search?q=use+loc+in+pandas+dataframe+to+filter+out+text+in+column&qs=n&form=QBRE&sp=-1&ghc=2&lq=0&pq=use+loc+in+pandas+dataframe+to+filter+out+text+in+column&sc=5-56&sk=&cvid=21CC88E5622D4338B6A064E3FD6D3FA0&ghsh=0&ghacc=0&ghpl=

Microsoft Bing. (2023, October). Retrieved from Bing.com: https://www.bing.com/search?q=generate+summary+table+using+pandas+agg+function&qs=n&form=QBRE&sp=-1&lq=0&pq=generate+summary+table+using+pandas+agg+function&sc=6-48&sk=&cvid=32D4A89A15E6481DA3C32ACED1F9189D&ghsh=0&ghacc=0&ghpl=

Microsoft Bing. (2023, October). Retrieved from Bing.com: https://www.bing.com/search?q=how+color+an+outlier+circle+on+matplotlib+boxplot&qs=n&form=QBRE&sp=-1&ghc=1&lq=0&pq=how+color+an+outlier+circle+on+matplotlib+boxplot&sc=6-49&sk=&cvid=56990562A66B45F396D81EC26DA6EF3C&ghsh=0&ghacc=0&ghpl=

Microsoft Bing. (2023, October). Retrieved from Bing.com: https://www.bing.com/search?q=how+place+labels+on+tick+locations+on+matplotlib+boxplot&qs=n&form=QBRE&sp=-1&ghc=1&lq=0&pq=how+place+labels+on+tick+locations+on+matplotlib+boxplot&sc=6-56&sk=&cvid=88B04CF02178497EB1C37669BB50CE51&ghsh=0&ghacc=0&ghpl=&ntref

Analysis of Data:

Analysis of data yielded from the clinical study showed that of the 10 drugs used in treatment regimens, Capomulin and Ramicane were the most effective. Contrasted to the other eight drugs that were used, Capomulin and Ramicane showed significantly better tumor volume statistics. Looking across results for mean tumor volume, median tumor volume, tumor volume variance, tumor volume standard deviation, and tumor volume standard error, Capomulin and Ramicane had much lower measurements in each of those categories than the other drugs and were also similar with each other.

Final tumor volumes for mice that were administered Capomulin and Ramicane were considerably lower than volumes recorded for two other comparative drugs, specifically Infubinol and Ceftamin. And further efficacy of Capomulin alone was seen in its treatment of one mouse (“l509”), in particular, by way of a line chart showing a dramatic decrease in tumor volume from day 20 to day 35.

Grouping all of the mice in the study - which were about evenly-split between male (51%) and female (49%) - according to their respective weights and average tumor volumes revealed a strong correlation between those two variables as measured by a Pearson R coefficient of .84 and as illustrated in a upward sloping line on a scatter plot graph.

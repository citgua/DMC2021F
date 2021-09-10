## Answers:
**1. Approximately when did we (the human society) enter the Zeta-Byte era?**
Approximately in year 2016
**2. Approximately how much information was exchanged in the first of the zeta-byte era? An order-of-magnitude estimate is enough.
Global IP traffic hit about 1.2 z-bytes for the first time
**3.What is Data Mining? A short one-sentence description is enough.**
The ability to extract knowledge and hidden patterns from massive amounts of data.
**4.What decade did the Structured Query Languages become popular?**
1970s to early 1980s
**5.What decade did the Online Transaction Processing (OLTP) become popular?**
1970s to early 1980s
**6.Which kind of data processing (OLTP vs. OLAP) is specifically optimized for complex historical data analytics?**
OLTP
**7.Which type of data processing is best suited for realtime analysis and data storage?**
OLTP
**8.What data processing technique is mostly used with Data Bases? OLTP or OLAP?**
OLTP
**9.What data processing technique is mostly used with Data Warehouses? OLTP or OLAP?**
OLAP
**10.How is a data warehouse different from a database? How are they similar?**
DB used to collect and store smaller amount of data while DW is best suited to handle and analyze larger data. DW is capable to accomadate to multiple applications while DB is typically constraint to one.
Both manage data in similar formats such as tables and data types.
**11.Name or describe the first three steps of Knowledge Discovery?**
*Data cleaning & integration*
*Data selection and transformation*
*Data Mining*
**12.Name two major flavors (kinds) of Data Mining.**
Descriptive and Predicitive
**13.What kind of Data Mining is more akin to Machine Learning?**
Predicitive Mining
**14.What is an outlier?**
Observation that differs significally from other observations.
**15.Outliers are often discarded as noise. However, one person’s garbage could be another’s treasure. For example, exceptions in credit card transactions can help us detect the fraudulent use of credit cards. Using fraudulence detection as an example, propose two methods that can be used to detect outliers and discuss which one is more reliable.**

**16.How is supervised learning different from unsupervised learning?**
Statistical Modeling (Model-Based Method): Outliers are points that don't fit to the model such as if transaction shows abnormal buying patterns.
DBSCAN (Clustering - ML method): Discriminant method that detects densely packed regions of the space and marks the data points in low-density areas as anomalous.
The DBSCAN algorithm is sensitive to its configuration but performs well after parameter optimization. Unsupervised methods can be useful in situations where there is no prior knowledge of classes of observations.
**17.Name three common synonyms for data attribute.**
Dimension, feauture, variable
**18.What are the possible implications of the presence of outliers in a dataset? (briefly describing two possible scenarios would be enough)**
Something is terrible wrong in data anaylsis or verge of making a significant discovery
**19.Explain the difference and similarity between classification and regression.**
Both classification and regression are tools used to analyze unseen patterns in data (predictive mining). Both are categorized as supervised learning algorithms under Machine Learning as well.
However, classification is disctrete regression (predicts values such as gender) while regression is continuous(values such as temp).
**20.What is a Data Tuple?**
It is a data object stored in a database. Usually described in a table as a single row that holds all the data for an individual object.
**21.How is Binary attribute different from Nominal attribute?**
Nominal attribute has not limit of categories while binary attribute consist of only two categories (0 or 1).
**22.How is Ordinal attribute different from Nominal attribute?**
Ordinal attributes are useful for registering subjective assesments of qualities with meaningful order. Nominal attribute has no meaningful order.
**23.How is Ordinal attribute different from Numeric attribute?**
Ordinal attributes can't show the magnitude between successive values while numeric can.
**24.How is a location attribute different from a scale attribute?**
Location attribute does not have a zero point.
**25.Do continuous attributes take countable values?**
No. Only takes uncountable infinite
**26.Are the possible values for discrete attributes always limited and finite?**
yes
**27.Suppose we have a dataset comprised of an attribute {Xi,i=1,N} with each of which has the corresponding weight {Wi,i=1,N}. Write down the equation for the weighted average of Xi.**
weighted mean= (sum of Wi*Xi)/(sum of Wi)
**28.Which statistic is more robust with respect to outliers? Mode, Mean, Median. Why?**
Median. Mean is senstive to oultliers like variance while mode is also sensitive to noise.
**29.Which measure of dispersion is more robust with respect to outliers? variance, range, interquartile range. Why?**
IQR is less sensitive to the presence of outliers unlike variance and an range.
**30.What statistical property does the skewness statistic measure about data?**
The assymetry of data
**31.What statistical property does the kurtosis statistic measure about data?**
The tailedness of data
**32.An experimental proof of Chebyshev’s inequality**
Shown in Problem 32 notebook in folder.

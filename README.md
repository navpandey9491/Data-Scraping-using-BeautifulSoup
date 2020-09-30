# Data-Scraping-using-BeautifulSoup

# Goal
Working on this project gave me an idea about how data can be scrapped from websites and parsed to get clean data using BeautifulSoup library. Here we will scrap android version history data from wikipedia and work on it.

Task: 
1. To reach the web url, we have used urlopen from urllib.request
2. Reading the html data and printing it to see it.
3. Extracting the table from the html data and printing its length
4. Extracting useful information from HTML table such as Removing undesired tags
5. Now extracting all the data in the rows of the table we have extracted from HTML
6. The next step is to remove the header which is extracted along with all the rows
7. Getting the table data present in all the rows of the table
8. Now in this step we will write and read the data in comma seperated value (csv) file
9. Importing the csv file created using pandas and printing it.

After pre-processing and data cleaning we have got very nice dataset in csv format which is clean.

Name	Version number(s)	Initial stablerelease date	Supported (security fixes)	API level	References
No official codename	1.0	September 23	2008	No	1	[9]
1.1	February 9	2009	No	2	[9][14]	NaN
Cupcake	1.5	April 27	2009	No	3	[15]
Donut	1.6	September 15	2009	No	4	[16]
Eclair	2.0 – 2.1	October 26	2009	No	5 – 7	[17]
Froyo	2.2 – 2.2.3	May 20	2010	No	8	[18]
Gingerbread	2.3 – 2.3.7	December 6	2010	No	9 – 10	[19]
Honeycomb	3.0 – 3.2.6	February 22	2011	No	11 – 13	[20]
Ice Cream Sandwich	4.0 – 4.0.4	October 18	2011	No	14 – 15	[21]
Jelly Bean	4.1 – 4.3.1	July 9	2012	No	16 – 18	[22]
KitKat	4.4 – 4.4.4	October 31	2013	No	19 – 20	[23]
Lollipop	5.0 – 5.1.1	November 12	2014	No	21 – 22	[24]
Marshmallow	6.0 – 6.0.1	October 5	2015	No	23	[25]
Nougat	7.0 – 7.1.2	August 22	2016	No	24 – 25	[26][27][28][29]
Oreo	8.0 – 8.1	August 21	2017	Yes	26 – 27	[30]
Pie	9	August 6	2018	Yes	28	[31]
Android 10	10	September 3	2019	Yes	29	[32]
Android 11	11	September 8	2020	Yes	30	[33]


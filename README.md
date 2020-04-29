# public-k12-data

ed-data_districts_fall2009-spr2017.csv contains the all the data on districts from ed-data for years 2009-spring 2017. I did not download 2017-2018 since it has more updates coming. Even 2016-2017 may still be being updated. A timeline should be established for downloads.

Ask for our CompareK12 Proposal for context.See the data sources document for our assessment of Ed-data, other CDE fields, and next steps. https://docs.google.com/document/d/1e5cjBUxleD9Dtjup8euivPYmJMgypJXaUuViMo-UdqY/edit?usp=sharing

Adding new years of data for districts:

1. download the new excel files from ed-data, selecting both the fields from each category and the CDS number. There is a limit on number of fields downloadable at once, somewhere after 50. I recommend trying to download into 4 files.
https://www.ed-data.org/Comparisons?compType=districts
2. combine the files on district name and cds number
3. add year column
4. add to your dataframe

It will also be possible to download data by school in a similar fashion.

*On college readiness I did not download percentages since it is a calculation and so I could download that category as a single file. The notebook has code I used to make the file.

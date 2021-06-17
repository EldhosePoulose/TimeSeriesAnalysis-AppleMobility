Through this [RMarkdown](www.rstudio.com) I want to present my sample work in Time Series Analysis, which I have done using the [Apple Mobility Trends Data](https://covid19.apple.com/mobility). I found pulling down this file challenging due to the fact that the URL for the CSV file changes daily. I mainly used the "rvest" package to harvest data from html pages and in python I use "beautifulSoup" package to scrape data. Eventhough I have experience in both I found this task challenging because my goal was to automate the entire process by harvesting the data from this page every day, run the job and mail the results to my E-Mail. I found that the URL for dataset is dynamic in some random way or as a function of the version (also dynamic) of the web content management system. Thus I understood that I can’t easily scrape it and just look for the URL embedded in the “Download the Data” button. After couple of days of research I found that the index.json contains the stable/URL of the dataset for each day.


The reason behind selecting this data is becasuse of the importance of this data in this period of Pandemic. I want to explore the activities of the public and see how it is changing everyday.

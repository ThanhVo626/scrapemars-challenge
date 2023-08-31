# scrapemars-challenge
part 1
Imported everything I needed, set the browers/path, then set up the url of the website we are scraping from
Used beautiful soup to extract all text with the class col-md-12
Then I extracted the title and previews of the articles with 'content_title' and 'article_teaser_body'
The I stored them in a dictionary. Then put that dictionary into a list

Part 2
Same early setup
Extracted all the rows from the table of the website from 'tr' and 'data-row'
Put the extracted data into a list by finding all the 'td'
Didn't know why \n was being put into my list so I put in a if statement before appending with my loop
Converted my list into a dataframe
Changed the data types to what I needed them to be
Question 1 - 12
Question 2 - 1867 Martian days worth of data
Question 3 -
1    -77.160920
2    -79.932584
3    -83.307292
4    -82.747423
5    -79.308725
6    -75.299320
7    -72.281690
8    -68.382979
9    -69.171642
10   -71.982143
11   -71.985507
12   -74.451807
Question 4 - 
1     862.488506
2     889.455056
3     877.322917
4     806.329897
5     748.557047
6     745.054422
7     795.105634
8     873.829787
9     913.305970
10    887.312500
11    857.014493
12    842.156627
Question 5 - According to the graph around 700 sols are in a mars year. Mars days are 23.9 hours so almost equivalent to earth days. So 700 terrestial days.

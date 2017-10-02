# Learn about command line, piping

Use the data (fake_news_sites.csv) provided in the data folder.  Use
command line to answer the questions below.  Learn about the command
using either **man**, or just google search for the documentation.

1. Compress the data.

   Use either *gzip* or *bzip2*.  Note: you have either to navigate to
   the right folder first, or alternatively submit the file name with
   folder name.

2. How many factually correct news are there?
>235
hint: use *zcat* or *bzcat* to display the text, use *grep* to search
for a relevant pattern, use *wc* to count the resulting lines

3. How many mostly correct news are there?
>167

4. How many fake news are there?
>There are 48 counts of fake news articles

5. How many different types of news classifications are there?
>There are 5 different classifications

   Hint: add up the types you see (you may use *head* to inspect the
   file).  Do you get the total number of observations?

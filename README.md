# Golang-mini-project
Mini Crawler Project

Write a program about crawler / scrap url

Ensure the following requirements:

1. You choose a link of any news website (bbc,ndtv,telegraph)
2. You must download the content (crawl) and analyze (parse) the article to get: the title, author, date published.
3. From the content of the article, you have to find out which links it has to the article or not, for each path found, continue to steps 1,    and 2.

The output should be written to csv file.

For example:

$ your-program <url>

```
web-crawl https://www.thesaigontimes.vn/121624/Cuoc-cach-mang-dau-khi-da-phien.html

```


Result of the csv file
```
URL, Title, Author, Date
https://www.bbc.com/news/world-us-canada-51394383, Trump acquitted by Senate in impeachment trial, BBC News, 2020-02-05T22:32:07+00:00
```

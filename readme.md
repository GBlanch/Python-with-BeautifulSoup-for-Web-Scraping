# BeautifulSoup and Python for Web Scraping

## Table of contents

## Introduction

The purpose of this repository is to showcase a basic web scraping case and their best practices.



## Before deploying any code

Prior to retrieving any data from any website, we must know whether or not that website allows to do so. Under the terms and conditions of service of the website/service of most websites, it is normally specified if they allow web scraping or not. 

Another way to technically know if we can fetch certain website data is to check whether or not the web directory we’re trying to access is allowed to be scraped. We can check this by adding `robots.txt` at the end of the root directory of their website. For instance, in this case:



Moreover, and since there are server and performance costs for the website owners when their data gets fetched, it is a nice and considered practice to avoid sending a big amount of URL request.

more information about this can be found in this website[ZenRows Blog - Web Scraping Best Practices and Tools 2023](https://www.zenrows.com/blog/web-scraping-best-practices#respect-robots-txt-sitemap)

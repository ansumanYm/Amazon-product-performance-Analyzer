# Amazon-product-performance-Analyzer
Amazon product performance Analyzer using Sentiment analysis of Product Reviews


## What is Web Scrapping?
Web scraping is an automatic method to obtain large amounts of data from websites. Most of this data is unstructured data in an HTML format which is then converted into structured data in a spreadsheet or a database so that it can be used in various applications. There are many different ways to perform web scraping to obtain data from websites. These include using online services, particular API’s or even creating your code for web scraping from scratch. Many large websites, like Google, Twitter, Facebook, StackOverflow, etc. have API’s that allow you to access their data in a structured format. This is the best option, but there are other sites that don’t allow users to access large amounts of data in a structured form or they are simply not that technologically advanced. In that situation, it’s best to use Web Scraping to scrape the website for data.

## Web Scraping — Amazon Customer Reviews

`Scraping product names and ASIN numbers` - Every product in amazon has a unique identification number. This number is called ASIN — Amazon Standard Identification Number. Using the ASIN number, we can directly access every individual product.

The findall() function is used to find all the html tags of the required span, attribute and value as mentioned in the argument. These parameters of a tag will be same for all the product names and asin throughout all the product pages. We just add the data-asin part of the content to a new list. Using this list, we can access individual data-asin numbers and hence their individual pages.

`Scraping customer review links` - Customer reviews will be present in each page of the products. But these are just few. We want all the customer reviews for the products. So, we have to scrape the ‘see all customer reviews’ link.

## What is Sentiment Analysis?
Sentiment Analysis, also known as Opinion Mining, is one of the common research areas which performs Natural Language Processing (NLP) tasks for the purpose to extract subjective information by analyzing text data written by users. In the case of sentiment analysis of review data, the main goal is to identify the user’s subjectivity and classify the statements into different groups of sentiments.

## Why Sentiment Analysis?
Sentiment analysis tools are essential to detect and understand customer feelings. Companies that use these tools to understand how customers feel can use it to improve CX. Sentiment analysis tools generate insights into how companies can enhance the customer experience and improve customer service.

Steps: -
1. Text Preprocessing & Lemmatization
2. Word Vectorization (BOW vs. TF-IDF)
3. Implementing ML Classifiers & Evaluation Metrics
4. Results
5. Hyperparameter Tuning

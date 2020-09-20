# Most-Read-Books

This repository contains the Most read books of 2019 dataset analyzed in the paper:

Title: "A cross-country study on cultural similarities based on book preferences"

Authors: Nazanin Sabri, Sadaf Sadeghian, Behnam Bahrak

DOI: https://doi.org/10.1007/s13278-020-00695-y

If you use this dataset in your work, please cite our paper:


# Dataset

The data was collected from Goodreads. 

## Most Read Books
The most read books of 2019, the following information is available for each book. 

* Country
* crawl_date
* duration_type
* generation_date
* rank
* book_url
* book_title
* book_cover_url
* published_year
* number_of_reads
* average_rating
* number_of_ratings
* author_url


```python
import pandas as pd

most_read_books = pd.read_csv('most_read_books.csv')
most_read_books.head(5)
```


|Country|	crawl_date|	duration_type|	generation_date|	rank|	book_url|	book_title|	book_cover_url|	published_year|	number_of_reads|	average_rating|	number_of_ratings|	author_url|
|----|----|----|----|----|----|----|----|----|----|----|----|----|
|Afghanistan|	December 24 2019|	y|	(Dec 22 2019 11:30AM)|	1|	/book/show/38746485-becoming|	Becoming|	https://i.gr-assets.com/images/S/compressed.ph...|	2018|	10|	4.58|	333941|	https://www.goodreads.com/author/show/2338628....|
|Afghanistan|	December 24 2019|	y|	(Dec 22 2019 11:30AM)|	2|	/book/show/6642715-the-forty-rules-of-love|	The Forty Rules of Love|	https://i.gr-assets.com/images/S/compressed.ph...|	2009|	9|	4.16|	108593|	https://www.goodreads.com/author/show/6542440....|
|Afghanistan|	December 24 2019|	y|	(Dec 22 2019 11:30AM)|	3|	/book/show/38820046-21-lessons-for-the-21st-ce...|	21 Lessons for the 21st Century|	https://i.gr-assets.com/images/S/compressed.ph...|	2018|	9|	4.19|	50164|	https://www.goodreads.com/author/show/395812.Y...|


## Genre

The genre values for each book that have at least 10 votes. 

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
most_read_books.head(10)
```

```
Country	crawl_date	duration_type	generation_date	rank	book_url	book_title	book_cover_url	published_year	number_of_reads	average_rating	number_of_ratings	author_url
0	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	1	/book/show/38746485-becoming	Becoming	https://i.gr-assets.com/images/S/compressed.ph...	2018	10	4.58	333941	https://www.goodreads.com/author/show/2338628....
1	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	2	/book/show/6642715-the-forty-rules-of-love	The Forty Rules of Love	https://i.gr-assets.com/images/S/compressed.ph...	2009	9	4.16	108593	https://www.goodreads.com/author/show/6542440....
2	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	3	/book/show/38820046-21-lessons-for-the-21st-ce...	21 Lessons for the 21st Century	https://i.gr-assets.com/images/S/compressed.ph...	2018	9	4.19	50164	https://www.goodreads.com/author/show/395812.Y...
3	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	4	/book/show/9969571-ready-player-one	Ready Player One (Ready Player One #1)	https://i.gr-assets.com/images/S/compressed.ph...	2011	8	4.27	766023	https://www.goodreads.com/author/show/31712.Er...
4	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	5	/book/show/4865.How_to_Win_Friends_and_Influen...	How to Win Friends and Influence People	https://i.gr-assets.com/images/S/compressed.ph...	1936	8	4.19	490845	https://www.goodreads.com/author/show/3317.Dal...
5	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	6	/book/show/35623545-directorate-s	Directorate S: The C.I.A. and America's Secret...	https://i.gr-assets.com/images/S/compressed.ph...	2018	8	4.23	1829	https://www.goodreads.com/author/show/40651.St...
6	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	7	/book/show/36072.The_7_Habits_of_Highly_Effect...	The 7 Habits of Highly Effective People: Power...	https://i.gr-assets.com/images/S/compressed.ph...	1989	7	4.10	447687	https://www.goodreads.com/author/show/1538.Ste...
7	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	8	/book/show/18144590-the-alchemist	The Alchemist	https://i.gr-assets.com/images/S/compressed.ph...	1988	6	3.86	1854318	https://www.goodreads.com/author/show/566.Paul...
8	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	9	/book/show/40961427-1984	1984	https://i.gr-assets.com/images/S/compressed.ph...	1949	6	4.18	2753233	https://www.goodreads.com/author/show/3706.Geo...
9	Afghanistan	December 24 2019	y	(Dec 22 2019 11:30AM)	10	/book/show/157993.The_Little_Prince	The Little Prince	https://i.gr-assets.com/images/S/compressed.ph...	1943	5	4.30	1172530	https://www.goodreads.com/author/show/1020792.
```

## Genre

The genre values for each book that have at least 10 votes. 

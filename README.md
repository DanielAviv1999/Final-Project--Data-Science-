# Book price prediction On BookDepository
## Created by Daniel Aviv &amp; Omer Itach
This project is a final project for Introduction to data science course at Holon Institute of Technology
## About
Book price prediction project is made under the guidelines of the ‘Introduction to data science’ course as a part of computer science bachelor studies.
The goal of the project is to mainly predict the price of a book on the website, by using Linear Regression.
## Project planing
* Data acquisition using BeautifulSoup **Python Library**
* crawling through the site and collecting all the features we needed, such as:
  * **Title**: name of the book.
  * **Pages-count**: number of pages.
  * **Bestsellers-rank**: rank in the best sellers book in the site.
  * **Rating**: the rating average rating of the book.
  * **Author**: the author of the book.
  * **Back-type**: the kind of the cover.
  * **Price-ILS**: the price of the book in shekels. 
  * **Width**: the width of the book.
  * **Height**: the height of the book.
  * **Thickness**: the thickness of the book.
  * **Weight**: the weight of the book.
  * **Top-categories**: columns of the most frequent categories.
## Data Cleansing
We wanted to focous on relevant books, and the site was selling also games and CD's
So we managed to drop the irrelevant data we mentioned, and some duplications etc.
### For example here we can see the number of pages fluctuate between 1 to 1000
![alt text](https://i.ibb.co/ScGhRLB/download.png) <br>
and we removed over and under paged books.

## Final Prediction
we used the traditional way of using **Linear Regression**,<br>
### Splitting the data to 20% test 80% train
![image](https://user-images.githubusercontent.com/76743397/181753837-7724c8db-f41f-43da-a347-6e91ec5425ba.png)
### Training the model
![image](https://user-images.githubusercontent.com/76743397/181753880-7c2f5499-3ef9-4dd3-95ae-2288cd3a0196.png)
### Prediction evaluation using R squared tool
![image](https://user-images.githubusercontent.com/76743397/181754027-d703c323-f997-4366-b75c-29e76292b37c.png)

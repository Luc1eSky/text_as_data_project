# ECON 630 - Text as Data: Final Project
## Text Analysis of Non-fiction Books

Author: Lucie Schulz
Last Edited: 08/14/2023

The goal of this project is to analyze non-fiction bestsellers. In order to do that this project includes the creation of a corpus of non-fiction book bestseller based on the New York Times Best Sellers lists and aims to answer the following research questions with the underlying data:

Research Question 1: What are the dominant topics in US non-fiction literature over the past ten years? How do those topics change over time?

Research Question 2: Does the gender influence the topics of best-selling books that land on the NYT bestseller list?
Corpus Creation Description

To create the dataset of NYT bestselling non-fiction books the NYT API has been used. The weekly list were scraped from 2014/01/12 - 2023/08/06. Since the bestseller list only includes a one-line description of the book, the dataset has been extended to include the long description of the book. The longer description of the books was scraped via the Google Books API using the isbn number as the unique identifier from the initial NYT list. Last but not least more information about the authors were collected via the Wikimedia API by scraping the infobox of the author's wikipedia page, if it exists.

## Corpus Caveats
The New York Times Non-Fiction Best Seller list is a significant and influential indicator of the popularity of non-fiction books in the United States. It reflects the books that are selling well and capturing the attention of readers across the country. However, it's important to note that while the list provides valuable insights into book sales and trends, it may not be a perfect representation of the absolute most widely read books for several reasons:

Limited Sample Size: The list is based on a specific sample of bookstores, both independent and chain retailers, as well as wholesalers across the United States. While this sample is substantial, it may not capture all sales channels, such as online retailers, libraries, or direct author sales.

Regional Variations: Book sales can vary significantly based on regional preferences and demographics. The New York Times list might not fully capture regional best-sellers or reading habits.

Prominence of Physical Sales: The list traditionally emphasizes physical book sales over digital or e-book sales. With the rise of e-books and digital reading platforms, this could lead to an underrepresentation of certain segments of the reading population.

Marketing and Promotion: Best-seller lists can be influenced by marketing efforts, author tours, media coverage, and promotional campaigns. This means that books with strong marketing backing might have a higher chance of making it to the list, even if they might not reflect the reading preferences of the broader population.

Time Lag: The list is updated weekly, which might not fully capture the long-term popularity of certain books that have a more gradual buildup in sales over time.

Subjectivity of Curation: The list is curated by editors at The New York Times, and their selection process can involve subjective judgment. Some books that are critically acclaimed but might not fit neatly into the categories defined by the list could be left out.

## Improvements opportunities to the corpus (not implemented due to time constraint)
While the New York Times Non-Fiction Best Seller list provides valuable insights into popular non-fiction books, it's important to complement this information with other sources of data and research methods to get a more comprehensive understanding of the most widely read books in the United States. Other sources, such as Amazon best-seller rankings, Goodreads popularity, online reviews, and surveys, can provide additional perspectives on popular reading habits and preferences.

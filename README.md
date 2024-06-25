# SQL PROJECT - INSIGHTFUL READS: UNVEILING TRENDS IN BOOK CONSUMPTION FOR STRATEGIC PRODUCT INNOVATION
# Data
- books:
> - book_id - id of book
> - author_id - id of author
> - title - title of book
> - num_pages - number of pages for the book
> - publication_date - date of books published
> - publisher_id -id of publisher

- authors:
> - author_id - id of author
> - author - name of author

- publishers:
> - publisher_id - id of publisher
> - publisher - name of publisher

- ratings:
> - rating_id - id of rating
> - book_id - id of book
> - username - username
> - rating - rating in number format

- reviews:
> - review_id - id of review
> - book_id - id of book
> - username - username
> - text - text

# Goal
> - To explore the book database to uncover trends, patterns, and insights that will inform the development and marketing of a new book-related product.
> - To examine publication dates, reviews, ratings, publishers, and authors to determine the popularity and critical reception of different books and authors.
> - To create a data-driven value proposition, focusing on features and target audiences to strategically position the new book product in the market.

# Libraries
*pandas , sqlalchemy*

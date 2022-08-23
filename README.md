# Predicting book genre

predicting book genre based on book cover


## Background

“don't judge a book by its cover” is the opposite of what this project initials. As a reader i've noticed that books from the same genre tend to look a like and with this project i wanted to explore if my initial sentiment hold true.

## Data

the dataset was obtained by webscraping "abjjed" using the beautifulsoup python package
initially i web scraped 6332 books but after removing duplicates
i was left with 4160 books

| attribute    | description                            |
|--------------|----------------------------------------|
| Book_title   | title of the book                      |
| Author       | author name                            |
| cover_url    | book cover image url                   |
| genres       | list of genres that a book falls under |
| descriptions | book description                       |

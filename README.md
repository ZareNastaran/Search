# Search
Here are are the search engine projects

I started with the simpleset approache, keyword search as my first project. In this project, I tried to let user saerch for a book title and show them the Top 15 most relevent results. First, I calculated the cosine similarity between the query and all the book titles and then I multiply the similarity score with the log of (average rating * number of rating) so I can display the most relevent results.

This project can be improved in many ways. For example, it's not efficient to calculated all the cosine similarities when there is a new query. In order to improve, I want to look for other approaches to implement a more efficient search system.

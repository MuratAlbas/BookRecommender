# BookRecommender
AI agent for book recommendations

Used a publicly available dataset from Kaggle.com. For book titles, authors, descriptions and ratings.
Sentence-Bert have been used to create the embeddings.
User interacts with a LLM (Llama3) through GroqAPI. LLM extracts the user preferences while establishing user friendly chat with the user.
After the extraction of the user preferences cosine similarity have been used for recommendations. Also, the ratings have been considered while making decisions.
Finally, recommended books displayed on the screen as result.

Dataset link: https://www.kaggle.com/datasets/arnabchaki/goodreads-best-books-ever

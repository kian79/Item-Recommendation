# Item-Recommendation
A simple recommendation system that takes a text and recommends a product from Digikala.

# Intoduction

In this project, I have implemented a simple recommendation system that receives a custom text and offers the user a product that fits the text from Digikala.
This project uses three different datasets:
1) Data set including Persian web pages and its information.
2) The data set includes 20,000 articles from the Persian Wikipedia.
3) Dataset of Digikala products that I have scrapped from its website with the help of  [this code](https://github.com/kian79/Digikala_Crawler).

This project also uses three different methods to offer products:
1) Jaccard similarity
2) Word2Vec
3) TF-IDF   

Depending on the type of activity, any of these 3 methods can be used.

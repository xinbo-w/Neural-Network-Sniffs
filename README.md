# Neural Network Sniffs

## Intro
Neural Network Sniffs is a side project that I do for fun. The project is themed around perfumes with data from nosetime.com, a Chinese perfume lover community. Thanks to the work done by nosetime.com and its users, I am able to get free access to data of more than 30k perfumes from more than 1,000 brands. For most of the perfumes nosetime.com provides well-structured info including gender, [fragrance family](https://en.wikipedia.org/wiki/Aroma_compound), [notes](https://en.wikipedia.org/wiki/Note_(perfumery)) (including top, middle, and base notes), score & duration (rated by users).  

The fragrance notes data is the main reason why I choose to do this project. Notes (such as rose, lemon, ginger, chocolate) are used to describe the scents of a perfume so that the complex smell of each perfume can be described by the combination of top, middle, and base notes. The presence of one note may alter the perception of another—for instance, the presence of certain base or heart notes will alter the scent perceived when the top notes are strongest, and likewise the scent of base notes in the dry-down will often be altered depending on the smells of the heart notes. (wikipedia: [Note (perfumery)](https://en.wikipedia.org/wiki/Note_(perfumery))). **Can we use the notes to help neural networks sniff the perfumes?**

The main body of this repo consists of 3 notebooks:
1. Data Scraper contains my code for scraping the data;
2. Odor Embedding is where I explored the possibility of using Word2Vec to generate a embedding for notes so we can explain notes through vectors, a language that neural networks are comfortable with;
3. In Modelling we use emdeddings to train the neural networks to predict a perfume's gender, fragrance family, and score by its notes.

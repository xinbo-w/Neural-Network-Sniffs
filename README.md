# Neural Network Sniffs
Hubert Wang
  
 <p align="right"><i>In me the tiger sniffs the rose. &nbsp&nbsp&nbsp&nbsp</i></p>
 <p align="right"><i>   -- Siegfried Sassoon</i></p>
  
## Intro
Neural Network Sniffs is a side project that I do for fun. The project is themed around perfumes with data from nosetime.com, a Chinese perfume lover community. Thanks to the work done by nosetime.com and its users, I am able to get free access to data of more than 30k perfumes from more than 1,000 brands. For most of the perfumes nosetime.com provides well-structured info including gender, [fragrance family](https://en.wikipedia.org/wiki/Aroma_compound), [notes](https://en.wikipedia.org/wiki/Note_(perfumery)) (including top, middle, and base notes), score & duration (rated by users).  

The fragrance notes data is the main reason why I choose to do this project. Notes (such as rose, lemon, ginger, chocolate) are used to describe the scents of a perfume so that the complex smell of each perfume can be described by the combination of top, middle, and base notes. The presence of one note may alter the perception of another—for instance, the presence of certain base or heart notes will alter the scent perceived when the top notes are strongest, and likewise the scent of base notes in the dry-down will often be altered depending on the smells of the heart notes. (wikipedia: [Note (perfumery)](https://en.wikipedia.org/wiki/Note_(perfumery))). **Can we use the notes to help neural networks sniff the perfumes?**

The main body of this repo consists of 2 notebooks:
1. Data Scraper contains my code for scraping the data;
2. In Perfume Modeling I try to model the perfumes by training a neural network to predict a perfume's fragrance family. The learned embedding can be used to explore relationships (such as similarities) among the perfumes.

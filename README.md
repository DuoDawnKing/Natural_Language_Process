# Natural_Language_Process
Part 1 Code: 

In order to obtain the necessary information, I imported the newsapi and then use the .env to pull the information of both bitcoin and etherium. When pulling the information I ensured that i was grabbing by articles that had the words with the size limit of 100 per group, because the free newsapi does have a cap on how many articles can be pulled. After the articles are pulled i put them into a sentiment calculator, which went through every article headline and would break it down based on date, text, compound, positive, negative, and neutral. I put those results of both bitcoin and ethereum into their own dataframes, which will be used to display and describe the information

Part 1 Results: 

	The results are as followed:
The highest mean positive score was ethereum, while bitcoin had the highest mean negative
The highest positive score was ethereum, while the highest negative score was bitcoin 

In the graph it shows max that both were negative but if we look at the the mean, std, 50% and 75% that bitcoin had the higher results.


Part 1 Opinion:

This would make sense knowing that bitcoin has been hit recently with the Luna, which had an effect on BTC news. Also, the news of coinbase announcing that investments will not be projects or kept if the company files bankruptcy has left investors scared on quality of investment protection



Part 2 Code:   

Here I used the lemmatizer and more to tokenize the all the article headlines for both bitcoin and etherium.
Instead of breaking it into groups i set up a def tokenizer and put that within def word_counter, it makes it alot easier and i dont have add addition code/additional steps 
The results showed the top 5 words from bitcoin articles to be char, bitcoin, may, cryptocurrencies
The results for the top 5 words in etherium headlines were char, crypto, cryptocurrency, market and bitcoin

You will see common phrases such as char and cryptocurrencies, which is not surprising since majority of articles will usually discuss those terms in relation to crypto
I put the information into a word cloud to give a better idea of words being used 

Part 3 Code:

I loaded spacy and used it display entities in the both bitcoin and etherium and use it to render visualize all they key terms of GPE, ORG, MONEY, PERSON


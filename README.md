# Personal-DReditor-implementation
I will attempt to implement DrEditor (as described in the article above) to improve the retrieval step of embeddings. 
Unlike the approach in the article, I will use both gradient descent and the formula they presented.
I hope this will help others improve their retrievers (although fine-tuning is always the best solution :( ). 
However, for small companies or applications, this improvement is quite sufficient, especially considering the amount of money and resources required for a more substantial enhancement.
Yes, you can train it using just a CPU in under 2 minutes (thanks to the optimizations I made). You can even do it using just NumPy ;) by applying the formula below. 
I used a private dataset, but I won't be sharing it. The only challenge you'll face is creating the special Q&A dataset required for this setup.

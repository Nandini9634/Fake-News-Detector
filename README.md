# Fake-News-Detector

Fake news and hoaxes have been there since before the advent of the Internet. The widely accepted definition of Internet fake
news is: fictitious articles deliberately fabricated to deceive readers. Social media and news outlets publish fake news to increase
readership or as part of psychological warfare. This project detects whether the news is fake or not.

I have used WordCloud to visualize text data. 

Steps involved are :
1. Cleaning (to break text into required format)
2. Tokenization (to extract a list of tokens)
3. Stop Words Removal (to remove words that does not provide any unique information)
4. Applying NLP Techniques (TfidfTransformer, CountVectorizer, TfidfVectorizer)
5. Modelling (Logistic Regression, MultinomialNB, Pipeline)

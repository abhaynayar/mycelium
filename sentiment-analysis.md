# Sentiment analysis
## Feature Extraction

Create a boolean vector (size vocabulary) of words appearing in the Tweet:

```
[1,1,0,1,0,0,...]
```

Create a dictionary of word frequency in positive and negative class:

```
{ (word,class): frequency, }
```

Create the following feature set for a Tweet:

```
[1, sum(positive), sum(negative)]
```

## Preprocessing

Stemming and lowercasing: `tun -> {tune, tuned, tuning}`
Stop words: punctuation or words that are not important (and, are, a, etc.)

http://www.nltk.org/howto/twitter.html

- `process_tweet()`
- `build_freqs()`

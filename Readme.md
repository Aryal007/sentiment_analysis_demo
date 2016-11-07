This is a Readme file for a basic example of sentiment analysis demo


This basic python program uses textblob dependency to calculate subjectivity and polarity of any text.

More at: https://textblob.readthedocs.io/en/dev/

The sentiment property returns a namedtuple of the form Sentiment(polarity, subjectivity). The polarity score is a float within the range [-1.0, 1.0]. The subjectivity is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective.
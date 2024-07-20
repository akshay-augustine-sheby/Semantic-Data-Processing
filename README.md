# Semantic-Data-Processing

## Question Answering System using Stanford Question Answering Dataset
- Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage.
- Dataset contains 100,000+ question-answer pairs on 500+ articles.
- Dataset fields are id, title, context, question, answer dictionary contains text and answer_start.
- I have used a sliding window approach to tokenize the input examples, which allows the model to capture context beyond the maximum sequence length, by creating overlapping windows of tokens that can be processed independently.
- I have used 2 pre-trained models: Bert and XLNet
- XLNet performed better than BERT

## Sentiment Analysis on Twitter posts using Twitter Sentiment Analysis Dataset
- I have use twitter sentiment140 dataset.
- It contains 1,600,000 tweets extracted using the twitter api.
- The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.
- Dataset fields are target, ids, date, flag, user and text, but I considered only target and text for sentiment analysis.
- I have used 2 pre-trained models: Bert and Distilbert
- Distilbert performed better than BERT

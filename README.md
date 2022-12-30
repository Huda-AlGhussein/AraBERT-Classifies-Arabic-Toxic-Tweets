# AraBERT-Classifies-Arabic-Toxic-Tweets
Finetuning ARABERT to classify if a text is toxic (it contains cyberbullying) or safe.

BERT (Bidirectional Transformer Encoder) is widely used for NLP tasks in several languages. However, monolingual BERT provided better performance than multilingual BERT. Therefore, I am using ARABERT for our
Arabic dataset to categorise a tweet into one of the predefined categories (safe or toxic) based on the text of the tweet. To do that, I am finetuning the ARABERT for this specific task. Arabert is a model created by the American University of Beirut (AUB) based on the
BERT model which is a stacked Bidirectional Transformer Encoder. 

I extracted Arabic tweets from twitter tracking the hashtags #QatarWorldCup2022 and #Qatar2022. All tweets were labelled as ‘toxic’ or ‘safe’ depending on the context of each tweet, these tweets are saved in an excel file that is then
called through the Google Collab in a dataframe.

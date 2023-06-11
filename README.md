# SMS_Spam_Detection

I have used the dataset: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

If you are using this dataset then you need to transfom the data and balance the ratio of ham and spam datas.

I have used the nltk library to remove the stopwords and re library to remove the unnecessary symbols and words.
also add a extra column of currrency symbols if used in the dataset.
This model also checks for the word count in the message of the ham and spam.
Takining into account of all the possible threats, you can see in the .ipynb file how i have identified the threats, it will detect whether the message is ham or spam.

I hope it helps!

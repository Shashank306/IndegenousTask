# IndegenousTask
Take any newspaper data through their API and classify the sentiment within the articles. Find the topic of the article and the sentiment. Share the github link to codebase.

Newsapi.org serves as the API for this task. The sentiment analysis and classification are done on the scant content that is accessible because the free edition of the API does not offer the entire article. The findings are not totally accurate when taking into account the aforementioned thresholds, however the method used is 100% accurate.

The news is filtered differently in the code and is arranged by popularity in the newspaper under consideration, BBC News. The results are contained in the attached csv file.

To execute the Python file: Navigate to the code's folder in the terminal in steps 1 and 2. Since this code displays encoded text, run the following commands in the terminal: install win-unicode-console with py -mpip run news_analysis.py with the flags

Output: There are seven columns in the csv file, including description, raw article, article post-processing, Polarity (polarity of the article) (polarity of the article), Sentiment (the overall article's sentiment based on polarity), Category (the news category), and Score (similarity-score with respect to category).

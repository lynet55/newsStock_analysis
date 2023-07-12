# newsStock_analysis

Python and R files used for data- generation and analysis, in a project studying the correlation of news sentiment and the Dow Jones index. The dataset containing the news used in the analysis, is taken from https://www.kaggle.com/datasets/miguelaenlle/massive-stock-news-analysis-db-for-nlpbacktests . Particularly the dataset containing CNBC news. To extract the sentiment from the news data, an NLP model trained on financial news is used to quantify sentiment. The model was accessed through an API found here: https://huggingface.co/mrm8488/distilroberta-finetuned-financial-news-sentiment-analysis

The output from these files is used in a final abstract, attempting to answer if there are any correlation between the sentiment of news articles and the DJI. 

Note. These are project files, which means that not all files are used in the final iteration of the project. Finally, there would be a file for generating data containing sentiment data by calling the Hugging Face model on the news articles. And there would also be R file containing the workflow of analyzing the data.

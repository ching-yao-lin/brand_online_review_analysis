# brand_online_review_analysis

本專案目標是透過分析多家網路服飾品牌的輿論，了解消費者最在意的「點」為何。

網路分飾品牌包含Max&amp;Co., Club Monaco, Joseph, Maje, iCB, ToryBurch六家品牌。

首先，我們將會從網路爬取所需的資料。詳見Webscraping_FashionGuide.ipynb檔案。

再來，我將前處理所爬取的資料，包含濾除停用字(stopwords)、斷詞等等，最後根據詞頻繪製文字雲。此步驟詳見NLP_FashionGuide.ipynb檔案。

This project focuses on knowing our customers through an analysis on online reviews of multiple brands.

These brands includes Max&amp;Co., Club Monaco, Joseph, Maje, iCB, and ToryBurch.

First, I scraped all the data I need from the Internet. (Please refer to Webscraping_FashionGuide.ipynb)

Then, I preprocessed the data, including filtering out stopwords, cutting words using "jieba" module; finally, I create meaningful WordClouds according to term frequencies of the words. (For this step, please refer to NLP_FashionGuide.ipynb)

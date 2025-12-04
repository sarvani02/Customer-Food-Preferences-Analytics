# Facebook Analysis Dataset

## 📌 Overview
This dataset contains customer complaints, reviews, and feedback collected from public Facebook posts.  
It is structured for sentiment analysis, brand analysis, and social media text mining.

The dataset includes:
- User information  
- Post content  
- Engagement metrics  
- Automatically extracted brand names  
- Smart NLP-generated post titles  
- Sentiment scores & sentiment labels  

---

## 📁 Columns Description

| Column Name | Description |
|-------------|-------------|
| **date** | Timestamp of the post/comment extracted from Facebook |
| **facebook id** | Unique ID of the Facebook post/comment |
| **facebook url** | Direct link to the post |
| **profile name** | Name of the Facebook user/page |
| **profile id** | Unique profile identifier |
| **profile url** | Link to the user/page profile |
| **product id** | Auto-generated ID for categorization |
| **product name** | Brand extracted from URL/text (Zomato, Swiggy, Order Issue, etc.) |
| **post id** | Unique post identifier |
| **post title** | NLP-generated short title describing issue category |
| **post text** | Full text of the feedback or complaint |
| **comment count** | Number of comments |
| **likes count** | Number of likes |
| **sentiment score** | Numeric polarity score |
| **sentiment label** | Positive / Neutral / Negative |

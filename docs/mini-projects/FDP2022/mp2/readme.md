<h1 align="center"> Sentiment anaysis For Hindi text</h1>

Mentor: Kusum Lata

Presentation: [Sentiment Analysis](Sentiment%20analysis_kusum.pptx)

## Description

In this new era full of technology, people prefer expressing their opinions and sentiments on social media. The emergence of readily available and improved communications tools has contributed to the extensive use of e-news, blogs, review sites and social networking sites like Twitter, Facebook, and YouTube etc. This way tons of GBs of data is being generated everyday over the internet. Handling such large amount of data becomes an interesting and yet a challenging task for the research communities. Online user reviews gives consumers the power to tell their side of the purchase story. User's today rely on other people's experiences and feedbacks about a product before they themselves experience it.

Here is where Sentiment Analysis (SA) comes into play. Sentiment Analysis is one of the biggest growing research domains in the field of Natural Language Processing (NLP). Growing User Generated Content (UGC) over the internet makes it difficult for the researchers to process this information. **What sentiment analysis does is it classifies a particular text or review into a polarity orientation. The most common polarity categories are positive, negative or neutral. It helps users easily identify whether a review depicts a positive, negative or a neutral sentiment towards the subject.** 
But today, just knowing the sentiment expressed may not be enough. There are reviews which are directed towards a particular aspect of a product. Aspect Based Sentiment Analysis helps here. The purpose of Aspect-Based Sentiment Analysis (ABSA), as contrasted to retrieving the general opinion reflected in a block of content, is to retrieve both the aspect defined in the sentence (in this context, the characteristics or attributes of a service or product) as well as the sentiment conveyed towards such aspects. For example, "The food at that place is good but the location is bad". 

In this particular review for a restaurant there are two aspects that are being talked about. One is "food" and the second is "location" where positive sentiment is depicted towards food and negative sentiment is depicted towards location. This aspect specific analysis gives fine-grained information to the organization or the user. Sentiment Analysis (SA) has proven to be a very helpful research field benefitting lots of businessmen, e-commerce sites, movie makers etc. 

SA refers to the task of identifying the type of opinion (positive, negative, neutral etc.) expressed in a sentence. With the size of data being generated in today’s era of internet, it would take an enormous amount of human effort to analyze the data. SA makes this work easy and simple. But just knowing the sentiment of the sentence might not be helpful in some cases. SA can then be extended to Aspect-based Sentiment Analysis (ABSA). ABSA has gained a huge popularity amongst the researchers. Aspect-based sentiment analysis (ABSA) is a most practical form of sentiment analysis. 

The purpose of Aspect-Based Sentiment Analysis (ABSA), as contrasted to retrieving the general opinion reflected in a block of content, is to retrieve both the aspect defined in the sentence (in this context, the characteristics or attributes of a service or product) as well as the sentiment conveyed towards such aspect
The entire process of ABSA is composed of two main subtasks: 
1. Aspect term extraction and
2. Sentiment classification. 

First step, Aspect term extraction refers to identifying and retrieving the entity being talked about in a review. 
The second step i.e. the sentiment classification deals with classifying various aspects into their polarity categories (positive, negative and neutral).

**Example For English**

- Review: The food is good but the location is bad.
- Aspect: Term Extraction “food”, “location”
- Sentiment classification: food-pos, location-neg 

**Example For Hindi** 

- Review: बैटरी लाइफ बहुत बढिया है
- Aspect Term Extraction: बैटरी लाइफ
- Sentiment classification: बैटरी लाइफ-pos

**Steps**

1. Find dataset for sentiment analysis.
2. Find Aspect Term Extraction
3. classify Sentiment positive, negative, neutral

For more detail study, you can refer this given link: https://monkeylearn.com/sentiment-analysis/

To develop sentiment analysis:

1.	Need dataset for sentiment analysis. (Take any hindi product review dataset)
2.	Train model on train datset
3.	Test model on test data.
The steps are shown in below Figure:
 
![image](https://user-images.githubusercontent.com/39075908/198519346-852a379e-8afc-49bd-9284-bec56c1cb23d.png)

## Data
Use this dataset to train and evaluate the classifier: [Hindi Movie Reviews Dataset](https://www.kaggle.com/datasets/disisbig/hindi-movie-reviews-dataset)

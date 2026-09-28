# Experimental Results


Part C 

Before comparing the two models , lets have an overview of the models selected . Precison , Recall and NDCG.  
Precision was selected to determine if products selected at the top were relevent to the customer query this is increadbly important because Stadiolot customers are mostly to only interact with the first 10 products .Therefore precison measures the quality of the products returned to the customer 
Recall  measures the model ablity to find relevent results within the catalogue 
NDCG was selected for ranking the most relevent product towards the top because as the casestudy had stated Stadioalot has a search ranking problem which we must address. 

91,49  95.65  Semantic is +4.16 

Model 1 BM25 Model Results 
Precision@10 : 91.49
Recall@10 :  5.60   
NDCG@10 : 88.45     


Model 2 Semantic Search
Precision@10 95.65 
Recall@10 : 5.17
NDCG@10 : 88.46

Final 
Precision@10 : Semantic is + 4.16 
Recall@10 :  Semantic  is + 0.11
NDCG@10 :   Sematic is + 0.01 

The recall rate is low but all the metrics are based on the first 10 search results , this is to account for the customer behaviour, as customer dont tend to scroll down and look at all the results making the type of model and rank cricial to the study .additionally in both datasets i used the search queary of boho bed frame to test rank , in BM25 the  exact match for this term ranked 26th while in the Semantic Search the term ranked 1st. From this expirement we can see how Semantic Search is able to recognise the relationship in the terms bed frame and bed platform 

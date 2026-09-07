# STADIOalot-Data-Science-Capstone
Data Science Capstone project for STADIOalot. SS1
# STADIOalot Data Science Capstone Project

## Part A: Motivation

## Part B: Problem Statement

## Part D: Repository Structure

The repository is organised into the following folders:

- `datasets/` – contains datasets used for the project.
- `models/` – contains models developed during the project.
- `experimental_setup/` – contains files related to the setup of experiments.
- `experimental_results/` – contains results produced from experiments.
- `statistical_scripts/` – contains statistical helper and comparison scripts.
- `visualisation_scripts/` – contains scripts used to create data visualisations.
- `data_request/` – contains the data request report for the project.

## Part E: RAAIDD Log




1.Risk

1.1Inconsistency in seller product description and meta data which reduces search relevance.
With over 38million products listed on Stadioalot , the different ways in how sellers list and describe products could make accurate retrieval of relevant products difficult . Furthermore the report does mention that Stadioalot has sited inconsistent and unreliable products categorisations as a problem

1.2 Paid advertising may lead to ranking basis
Larger and better funded brands and sellers may rank higher because they are able to pay for placement this would effect customer relevance in search results

1.3 Customer behaviour may be affected by the search results they are shown. Customers may click on or view products because they appear prominently in the results, even if they are not highly relevant to their search. This could create misleading behavioural data and introduce bias into the model. 

1.4. Relevance labels may be difficult to obtain from Stadioalot.
The final risk is understanding that the project is “two parts “. Firstly understanding the customer’s search terms and secondly retrieving the correct product from sellers product attributes and meta data.

1.5. We are not sure that Stadioalot has data that can tell us what makes a good or bad search result



2. Action 

2.1Investigate the quality and structure of sellers metadata
Assess titles product descriptions, attributes, and search for any missing values

2.2.Investigate the current indexing and ranking process
Establish how products are indexed but the Stadioalot system , are there any sitemaps for sellers or crawlers to index new sellers and new products. The information pack does not contain that information

2.3.Analyse the search from customer over the past 1-2 year to look for any terms which are colloquial terms which result  with null searches results Du Toit (2022) 


2.4.Define how Stadioalot defines and measures product relevance eg will there be a relevance score to train the model eg 1-3 or are sales the only metric that matters Moses (2021) 


3.Assumption

3.1. Product catalogue and indexing infrastructure may contribute to customer search retrievals .
The case study does not mention the infrastructure of Stadioalot and it’s technical indexing process like crawling and indexing this process must be investigated

3.2.Customer Behaviour like clicks , add to charts are sufficient to determine customer search intent and therefore indicate relevant search results

3.3. Different prompting in searches should lead to the same result for example, when two different customers search for “tekkies” or “sneakers”, the searches should them both to training shoes Du Toit (2022) 

3.4. Product search relevance score can help place relevant products from a search in a clear rank order of relevance . Moses (2021) 

4.Issue

4.1.The Stadioalot product catalogue is too large to provide a score for every product, this makes it computational impractical to rank every product on a relevance scale. 

4.2.Reasons for search abandonment is largely unexamined, this might need more user behaviour research, such us interviews to understand the extent and reason for cart and search abandonment


5.Decision

5.1.Decide whether to focus only on the search relevance aspect of the Capstone project or to investigate both the metadata and the customer behaviour aspect as the product information provides. 

5.2. Decide which model to explore that matches to problem statement 


6 .Dependency

6.1.Feedback from relevant stakeholders (lectures) to determine the direction of the research

6.2.Access to metadata like product titles, product attributes, seller information and catalog form Stadioalot

6.3. Access to customer behaviour data , such as search queries, product views , links purchases , abandonment







## References

Reference List Entry
Moses, K. (2021) Modeling Product Search Relevance in e-Commerce: Home Depot Case Study, Medium. Towards Data Science. Available at: https://medium.com/data-science/modeling-product-search-relevance-in-e-commerce-home-depot-case-study-8ccb56fbc5ab (Accessed: 7 September 2026).
Reference List Entry: Du Toit, M. (2022) Improving Product Search using Machine Learning, Medium. Takealot Engineering. Available at: https://medium.com/@matthysdutoit/improving-product-search-using-machine-learning-d6c63ed49aa (Accessed: 7 September 2026). 


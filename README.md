# Spacy-NER-Accuracy-CHECK
Spacy NER Accuracy CHECK ( 10 articles, Spacy vs manual review)


Data - 1. I picked 10 articles from news site
2. Then Looped on them using spacy and extracted all entity types (NER)
3. Generate statistics on the count of each entity type in the full collection (aggregate statistics)
4. Manually label each NER (correct/incorrect and what is the correct entity type if incorrect)
5. Generated statistics on the precision of Spacy on each of the entity types (like on Person, ORG, LOC, GPE...)


The main categories:
![image](https://user-images.githubusercontent.com/53173112/204489499-649b9c3e-50a0-4664-a231-a8b76765b66a.png)

Results:

![image](https://user-images.githubusercontent.com/53173112/204489236-4af48ed1-e8f9-4f8f-8fc5-d00bea3a49aa.png)
![image](https://user-images.githubusercontent.com/53173112/204489296-6a533418-dfbc-4c0d-9248-f67ba4c93830.png)

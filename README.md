This project is to predict how fit the candidate is based on their available information (job title and the number of connection on Linkedin), 
utilizing Doc2Vec, BERT, ELMo embeddings and Learning to Rank model. By calculating the similarity score based on the embeddings of the desired 
job query and job title, scaling the number of connection, and then starring top 10 fittest applicants, LGBMRanker will be deployed to predict 
their ranking using the metric ndcg score.

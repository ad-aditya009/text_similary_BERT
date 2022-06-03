# text_similary_BERT
The project uses three state of the art BERT models to get similarity scores between text and finally takes the average of the similarity scores from 3 models to get final similarity scores. The averaging the scores from different BERT models allows to get a more generallised and accurate similarity  scores.
BERT models and text similarity scores:
       score1 : BERT model 'paraphrase-MiniLM-L3-v2'
       score2 : BERT model 'all-distilroberta-v1'
       score3 : BERT model 'multi-qa-distilbert-cos-v1'
       avg_simi_score : average of the similarity scores from the three models.
       similarity measure used - cosine similarity

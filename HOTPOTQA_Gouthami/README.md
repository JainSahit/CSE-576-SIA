Load this drive on your Google drive:
https://drive.google.com/drive/u/1/folders/17SpWmNSl9dcbyqUFpdvnYlHj1EYXwHju


NOTE: Keep the shared folder 'NLP' under 'My Drive' in your drive.

Google Colab Link:

gouthami_ sia_roberta.ipynb:          https://colab.research.google.com/drive/1fK3ex1krRYM8Zsndp_gouvZCzvmw_IQ8?usp=sharingauthuser=1#scrollTo=r_yAaWrd-_pA

1218506822_EvaluationMetrics_BM25_SIA.ipynb: https://colab.research.google.com/drive/1IqGMctYH6Zl48CL-DSXZkB7jS75ZB_ru?usp=sharing


Use gouthami_ sia_roberta.ipynb to train SIA model on HOTPOTQA or directly use the model that we have trained to re-rank passages using 1218506822_EvaluationMetrics_BM25_SIA.ipynb.

SIA model_path= '/content/drive/MyDrive/NLP/Project/models/sia_trained_roberta_model'

RESULTS:

  BM25:
  
    P@5:        0.175  
    P@10:       0.103
    Recall@5:   0.346
    Recall@10:  0.394
    Recall@20:  0.433
    MAP:        0.451
    MRR:        0.476
    
  SIA: 
  
    P@5:        0.166
    P@10:       0.100
    Recall@5:   0.332
    Recall@10:  0.388
    Recall@20:  0.435
    MAP:        0.416
    MRR:        0.439

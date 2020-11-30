Load this drive on your Google drive:
https://drive.google.com/drive/u/1/folders/17SpWmNSl9dcbyqUFpdvnYlHj1EYXwHju


NOTE: Keep the shared folder 'NLP' under 'My Drive' in your drive.

Google Colab Link:

gouthami_ sia_roberta.ipynb:          https://colab.research.google.com/drive/1fK3ex1krRYM8Zsndp_gouvZCzvmw_IQ8?usp=sharingauthuser=1#scrollTo=r_yAaWrd-_pA

1218506822_EvaluationMetrics_BM25_SIA.ipynb: https://colab.research.google.com/drive/1IqGMctYH6Zl48CL-DSXZkB7jS75ZB_ru?usp=sharing


Use gouthami_ sia_roberta.ipynb to train SIA model on HOTPOTQA or directly use the model that we have trained to re-rank passages using 1218506822_EvaluationMetrics_BM25_SIA.ipynb.

SIA model_path= '/content/drive/MyDrive/NLP/sia_experiment/SIA_OpenBookQA'

RESULTS:

  BM25:
  
    P@5:        0.127  
    P@10:       0.072
    Recall@5:   0.467
    Recall@10:  0.526
    Recall@20:  0.599
    MAP:        0.363
    MRR:        0.370
    
  SIA+BM25: 
  
    P@5:        0.023
    P@10:       0.043
    Recall@5:   0.094
    Recall@10:  0.317
    Recall@20:  0.549
    MAP:        0.081
    MRR:        0.072

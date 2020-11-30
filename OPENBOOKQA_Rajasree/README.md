Load this drive on your Google drive:
https://drive.google.com/drive/u/1/folders/17SpWmNSl9dcbyqUFpdvnYlHj1EYXwHju


NOTE: Keep the shared folder 'NLP' under 'My Drive' in your drive.

Google Colab Link:

SIA Model Training with Roberta.ipynb:          https://colab.research.google.com/drive/1q0VuVG-fwrMybA902xEK-X1E2wG3gmn2?authuser=1#scrollTo=r_yAaWrd-_pA

Evaluation Metric with BM25 and SIA .ipynb: https://colab.research.google.com/drive/1SY375l0eDkPOvRR0CG93u9nnV2Bt1rL7?authuser=1#scrollTo=ZNsvbMzdeych


Use SIA Model Training with Roberta.ipynb to train SIA model on WikiPassageQA or directly use the model that we have trained to re-rank passages using Evaluation Metric with BM25 and SIA.ipynb.

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
    
  SIA: 
  
    P@5:        0.023
    P@10:       0.043
    Recall@5:   0.094
    Recall@10:  0.317
    Recall@20:  0.549
    MAP:        0.081
    MRR:        0.072

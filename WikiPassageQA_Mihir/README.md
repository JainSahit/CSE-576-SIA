Load this drive on your Google drive:
https://drive.google.com/drive/folders/1RRKA-TmNjKpcjtj0-ceq5ons3j1chMmJ?usp=sharing


NOTE: Keep the shared folder 'man_mihit_project' under 'My Drive' in your drive.

Google Colab Link:

sia.ipnyb:          https://drive.google.com/file/d/1Gq1x2tDiZ8_2w8VUQCZCvgZKUqcip97j/view?usp=sharing

final_system.ipynb: https://drive.google.com/file/d/1RP_S75qEv2DZRFKqLTD_2I5sdH6gYhwP/view?usp=sharing

Use sia.ipynb to train SIA model on WikiPassageQA or directly use the model that we have trained to re-rank passages using final_system.ipynb.

SIA model_path= '/content/drive/MyDrive/man_mihir_project/sia_experiment/model'

RESULTS:

  BM25:
  
    P@5:        0.0649  
    P@10:       0.0401
    Recall@5:   0.1981
    Recall@10:  0.2457
    Recall@20:  0.2825
    MAP:        0.2109
    MRR:        0.2188
    
  SIA: 
  
    P@5:        0.0923
    P@10:       0.0540
    Recall@5:   0.2241
    Recall@10:  0.2477
    Recall@20:  0.2645
    MAP:        0.2992
    MRR:        0.3089

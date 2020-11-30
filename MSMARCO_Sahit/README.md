Load this drive on your Google drive:
https://drive.google.com/drive/folders/18OiVDNPf9avJ9I5PSOZkhbsjJEhbubQ-?usp=sharing
NOTE: Keep the shared folder 'Sahit' under 'My Drive' in your drive.

Google Colab Link:

sia roberta.ipnyb:          https://colab.research.google.com/drive/1ZSv3LMCOu86VC4qAE-QSGF3_8bwkIzr2?usp=sharing

final_system.ipynb: https://colab.research.google.com/drive/1C560iSR5tM2o3BD8T-S3NP2LYp6mgPMa?usp=sharing

Use sia.ipynb to train SIA model on WikiPassageQA or directly use the model that we have trained to re-rank passages using final_system.ipynb.

SIA model_path= '/content/drive/My Drive/Sahit/work/project_nlp/sia_experiment/modelMSMARCO/pytorch_modelTrained'

RESULTS:

  BM25:
  
    P@5:        0.0611  
    P@10:       0.0408
    Recall@5:   0.2944
    Recall@10:  0.3916
    Recall@20:  0.4842
    MAP:        0.1937
    MRR:        0.1974
    
  SIA+BM25: 
  
    P@5:        0.0645
    P@10:       0.0423
    Recall@5:   0.3103
    Recall@10:  0.4058
    Recall@20:  0.4981
    MAP:        0.2027
    MRR:        0.2070

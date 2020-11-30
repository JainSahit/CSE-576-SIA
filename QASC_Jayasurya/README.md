Load this shared foler in your Google Drive: https://drive.google.com/drive/folders/1PMRCwBVrFdMJkU197oKtgOIKDGmYbtQC?usp=sharing

NOTE: Keep the shared folder 'man_mihit_project' under 'My Drive' in your drive.

Google Colab Link:

sia_roberta_model_training.ipynb: https://colab.research.google.com/drive/1TxPqEvgNCn4Vbx8dkX_TsticlzovAk3r?usp=sharing

Model_Evaluation_Baseline_And_SIA_Model.ipynb: https://colab.research.google.com/drive/1hzeuaYl170Hmj5itR4G4uNA2cTbF5RTa?usp=sharing

Use sia_roberta_model_training.ipynb to train SIA model on QASC dataset or directly use the model that we have trained to re-rank passages using Model_Evaluation_Baseline_And_SIA_Model.ipynb.

SIA model_path: '/content/drive/My Drive/phase2_experiments/SIA_EXPERIMENT/model_QASCrobertabase_fulltraindataset_10epochs'

RESULTS:

  BM25:
  
    P@5:        0.1594  
    P@10:       0.0863
    Recall@5:   0.7548
    Recall@10:  0.8077
    Recall@20:  0.8466
    MAP:        0.6130
    MRR:        0.6123
    
  SIA+BM25: 
  
    P@5:        0.1704
    P@10:       0.0917
    Recall@5:   0.8077
    Recall@10:  0.8585
    Recall@20:  0.8758
    MAP:        0.6319
    MRR:        0.6289

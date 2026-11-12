# Models for Bidirectional multitask learning for QFD

Model  
SGM.py: seq2seq model  
SGM_BI_DECODER.py: seq2seq + bidirectional decoder  
Transformer.py: transformer model  
Transformer_BI_DECODER.py: transformer with bidirectional decoder mask  

training.py: training process of SGM.py and SGM_BI_DECODER.py  
training_transformer.py:  training process of Transformer.py and Transformer_BI_DECODER.py  



How to train a seq2seq model    
step 1: import either SGM or SGM_BI_DECODER in training.py  
step 2: check hyper parameters in params.py if they are suitable  
step 3: run command python training.py  

How to train a transformer model    
step 1: import either Transformer or Transformer_BI_DECODER in training_transformer.py  
step 2: check hyper parameters in params.py if they are suitable  
step 3: run command python training_transformer.py  


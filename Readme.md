## Initial data
  1) Place contents of model_data [all_districts] in **/data/raw** and rename as train, test and val.
## 1) Ranked_Sentences
  1) Generates ranked sentences.
  2) Cosine similarity ( embedding [facts], embedding [judge opinion] ) 
  3) Ranked-sentences added in df
## 2) Multi-Task Model
  1) Binary classifier + salience of all sentences to predict bail decision.

## TODO:
  1) Hindi word -> Root word **Priority 3**
  2) Clustering **Priority 2**
  3) Summarization **Priority 1**
    a) Direct Hindi
    b) translate to English - Summarize - translate to Hindi
  
  **COMPLETE AT LEAST ONE FULLY BY WEEKEND**
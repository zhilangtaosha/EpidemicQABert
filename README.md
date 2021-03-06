# epidemicQABert

epidemicQA system using BM25+Bert

DataFountain&CCF Big Data Expert Committee Algorithm Competition-Epidemic Government Q&A Assistant

(i): Requirement: 

1.Python 3.6.9
             
2.Torch 1.4.0

(ii): Link: https://www.datafountain.cn/competitions/424

(iii): DataSet: https://www.datafountain.cn/competitions/424/datasets

(iv): Task introduction: Given epidemic-based policy data sets, user questions, and labeled answer fragments. Participants can use the training data set to train intelligent question and answer through the analysis, processing and organization of the policy data.

(v): Project introduction: 

1. Use BM25+Bert to build an information retrieval document matching module to search for matching documents 

2. Use Bert and overlapping text slicing technology for intelligent answer extraction

(vi): Process Training Sample: 

python process_mrc_data.py

python process_class_data.py
                         
(vii): Training information retrieval document matching module: python train_bert_matcher.py

(viii): Matching Document: python use_bm25_link_plus_bert.py

(ix): Training answer extraction module: python train_bert_reader.py

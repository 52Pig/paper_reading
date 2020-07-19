

##################################
########### Base Model ###########
##################################



# FFM
https://github.com/52Pig/paper_reading/blob/master/Field-aware%20Factorization%20Machines%20for%20CTR%20Prediction.pdf

# DeepFM
https://github.com/52Pig/paper_reading/blob/master/DeepFM-0239.pdf


# DIN 阿里深度兴趣网络
https://github.com/52Pig/paper_reading/blob/master/Deep%20Interest%20Network%20for%20Click-Through%20Rate%20Prediction.1706.06978.pdf


# gbdt+lr 融合
https://github.com/52Pig/paper_reading/blob/master/practical-lessons-from-predicting-clicks-on-ads-at-facebook.pdf



####################################
############ NLP ###################
####################################

# DSSM



# Hin2Vec
https://github.com/52Pig/paper_reading/blob/master/2017.%20CIKM%20HIN2Vec.pdf


# Seq2Seq
https://github.com/52Pig/paper_reading/blob/master/1409.3215.seq2seqwithneuralnetwork.pdf


# transformer训练速度，时间复杂度改进
## Reformer
时间复杂度L*log(L); google开源，数据结构上变化，用到bucket桶和hash，self-attention计算的时候做优化。Reformer：The Efficient Transformer。
https://github.com/52Pig/paper_reading/blob/master/2001.04451v1.pdf

## linformer
时间复杂度L; facebook ai开源，矩阵变换。矩阵操作包含x与w点积，w和qkv矩阵运算，是在x与w过程中进行拆解，x和L矩阵相乘，L和w矩阵相乘，这两部分进行优化，将复杂度转成线性的。Linformer：Self-Attention with Linear Complexity
https://github.com/52Pig/paper_reading/blob/master/2006.04768.pdf


# fast_bert
针对推理速度的优化
https://github.com/52Pig/paper_reading/blob/master/2004.02178.pdf

##################################
############ ACL 2020 ############
##################################

https://github.com/52Pig/paper_reading/blob/master/A%20Fine-grained%20Multimedia%20Knowledge%20Extraction%20System.2020.acl-demos.11.pdf
https://github.com/52Pig/paper_reading/blob/master/A%20System%20to%20Support%20the%20Analysis.2020.acl-demos.32.pdf





2020 ACL优质论文
Don't Stop Pretraining: Adapt Language Models to Domains and Tasks.



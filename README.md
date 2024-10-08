# IALP2022
Improving Sentiment Analysis By Emotion Lexicon Approach on Vietnamese Texts

To understand more about the method, please read this paper: https://arxiv.org/abs/2210.02063. 

Please preview and download the datasets used: UIT-VSMEC, UIT-VSFC(https://github.com/undertheseanlp/NLP-Vietnamese-progress/blob/master/tasks/sentiment_analysis.md) and ViHSD(https://github.com/sonlam1102/vihsd). And the Lexicon Emotio used: https://zenodo.org/record/801610#.Y0D9THZBy3A

The source codes are written in python with Jupyter notebook format. It is easy to run by Jupyter notebook or Google colab. Please note that the uploaded source code only runs on one dataset and one task, therefore you need tweak each dataset for the best results. We evaluated it, and it works well for all three datasets.

- Processing method to combine datasets (UIT-VSMEC, UIT-VSFC, ViHSD) with Lexicon emotion: Commbined_with_VnEmolex.ipynb

- The deep learning model (with improvements to combine with VnEmolex): Text-CNN.ipynb

- The transformer model (with improvements to combine with VnEmolex): Transformer_Model.ipynb

Citation:
```
@INPROCEEDINGS{9961318,
  author={Doan, An Long and Luu, Son T.},
  booktitle={2022 International Conference on Asian Language Processing (IALP)}, 
  title={Improving Sentiment Analysis By Emotion Lexicon Approach on Vietnamese Texts}, 
  year={2022},
  volume={},
  number={},
  pages={39-44},
  keywords={Sentiment analysis;Analytical models;Social networking (online);Semantics;Boosting;Task analysis;sentiment analysis;emotion lexicons;text classification;machine learning;deep learning;transformers models},
  doi={10.1109/IALP57159.2022.9961318}}

```

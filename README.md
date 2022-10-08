# IALP2022
Improving Sentiment Analysis By Emotion Lexicon Approach on Vietnamese Texts

To understand more about the method, please read this paper: https://arxiv.org/abs/2210.02063?fbclid=IwAR0VvHt2utCscAqrxLspVvTMRztub8B5BpVLBCsIGfRdz4CozvoCuxAfwi4

Please preview and download the datasets used: UIT-VSMEC, UIT-VSFC(https://github.com/undertheseanlp/NLP-Vietnamese-progress/blob/master/tasks/sentiment_analysis.md) and ViHSD(https://github.com/sonlam1102/vihsd). And the Lexicon Emotio used: https://zenodo.org/record/801610#.Y0D9THZBy3A

The source codes are written in python with Jupyter notebook format. It is easy to run by Jupyter notebook or Google colab. Please note that the uploaded source code only runs on one dataset and one task, therefore you need tweak each dataset for the best results. We evaluated it, and it works well for all three datasets.

- Processing method to combine datasets (UIT-VSMEC, UIT-VSFC, ViHSD) with Lexicon emotion: Commbined_with_VnEmolex.ipynb

- The deep learning model (with improvements to combine with VnEmolex): Text-CNN.ipynb

- The transformer model (with improvements to combine with VnEmolex): Transformer_Model.ipynb

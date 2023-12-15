---
license: cc-by-nc-4.0
language:
- ch
- zh
---

The model used in our paper:
'''bibtex
@article{MU2024122791,
title = {Predicting and analyzing the popularity of false rumors in Weibo},
journal = {Expert Systems with Applications},
volume = {243},
pages = {122791},
year = {2024},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2023.122791},
url = {https://www.sciencedirect.com/science/article/pii/S0957417423032931},
author = {Yida Mu and Pu Niu and Kalina Bontcheva and Nikolaos Aletras},
keywords = {Social media, Rumor popularity, Misinformation analysis},
abstract = {Malicious online rumors with high popularity, if left undetected, can spread very quickly with damaging societal implications. The development of reliable computational methods for early prediction of the popularity of false rumors is very much needed, as a complement to related work on automated rumor detection and fact-checking. Besides, detecting false rumors with higher popularity in the early stage allows social media platforms to timely deliver fact-checking information to end users. To this end, we (1) propose a new regression task to predict the future popularity of false rumors given both post and user-level information; (2) introduce a new publicly available dataset in Chinese that includes 19,256 false rumor cases from Weibo, the corresponding profile information of the original spreaders and a rumor popularity score as a function of the shares, replies and reports it has received; (3) develop a new open-source domain adapted pre-trained language model, i.e., BERT-Weibo-Rumor and evaluate its performance against several supervised classifiers using post and user-level information. Our best performing model (KG-Fusion) achieves the lowest RMSE score (1.54) and highest Pearson’s r (0.636), outperforming competitive baselines by leveraging textual information from both the post and the user profile. Our analysis unveils that popular rumors consist of more conjunctions and punctuation marks, while less popular rumors contain more words related to the social context and personal pronouns. Our dataset is publicly available: https://github.com/YIDAMU/Weibo_Rumor_Popularity.}
}
'''
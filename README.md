
# Reading List for Mental Health Detection and Analysis on Social Media
This project is associated with the survey paper on ***"Social Computing for Mental Health Analysis: A Survey"***. For a decade now, the exponential growth is observed in computational intelligence techniques for mental illness detection and analysis on social media. 

# Available Datasets 

| **Dataset**       | **Title of the Paper** | **Link of the Paper** | **Link of the Dataset** |
| ----------------- | ---------------------- |---------------------- |------------------------ |
| SDCNL | Deep Learning for Suicide and Depression Identification with Unsupervised Label Correction.| [Paper](https://arxiv.org/pdf/2102.09427.pdf) | [Dataset](https://github.com/ayaanzhaque/SDCNL) | 
| RSDD | Depression and self-harm risk assessment in online forums | [Paper](https://arxiv.org/pdf/1709.01848.pdf)| [Dataset](http://ir.cs.georgetown.edu/resources/rsdd.html)|
| SMHD | SMHD: a large-scale resource for exploring online language usage for multiple mental health conditions | [Paper](https://arxiv.org/pdf/1806.05258.pdf) | [Dataset](http://ir.cs.georgetown.edu/resources/smhd.html)|
| MDDL | Cross-domain depression detection via harvesting social media. | [Paper](https://eprints.soton.ac.uk/423226/1/IJCAI18_Shen_et_al_depression_detection.pdf) | [Dataset](https://github.com/sunlightsgy/MDDL)|
| SMM4H | Identifying depression on reddit: The effect of training data. | [Paper](https://aclanthology.org/W18-5903.pdf) | [Dataset](https://files.pushshift.io/reddit/submissions/) |
| Dreaddit |  Dreaddit: A Reddit dataset for stress analysis in social media. | [Paper](https://arxiv.org/pdf/1911.00133.pdf) | [Dataset](http://www.cs.columbia.edu/~eturcan/data/dreaddit.zip) |
|A Reddit and Twitter dataset | Supervised learning for suicidal ideation detection in online user content. | [Paper](https://www.hindawi.com/journals/complexity/2018/6157249/) | [Dataset]( https://github.com/shaoxiongji/sw-detection) |
| eRISK | Overview of eRisk: early risk prediction on the internet. | [Paper](https://tec.citius.usc.es/ir/pdf/eRisk2018LNCS.pdf) | [Dataset](https://erisk.irlab.org/eRisk2021.html) |
| SRAR | Knowledge-aware assessment of severity of suicide risk for early intervention. | [Paper](https://dl.acm.org/doi/pdf/10.1145/3308558.3313698?casa_token=ZI5GX1Cv60IAAAAA:vTvADTR8bxHCOtmI8sqE2zIPL6gdB0M51OlhRJRJfJI34h96TkUVl4-TtMCEJT9vmJsl30YeU0ah) | [Dataset](https://github.com/AmanuelF/Suicide-Risk-Assessment-using-Reddit) |
| A Reddit dataset | Expert, Crowdsourced, and Machine Assessment of Suicide Risk via Online Postings | [Paper](https://aclanthology.org/W18-0603.pdf) | [Dataset: (on request)](http://users.umiacs.umd.edu/~resnik/umd_reddit_suicidality_dataset.html) |
| A Sina microblog dataset | Latent Suicide Risk Detection on Microblog via Suicide-Oriented Word Embeddings and Layered Attention | [Paper](https://aclanthology.org/D19-1181.pdf) | [Dataset:  (on request)](https://github.com/bryant03/Sina-Weibo-Dataset) |
| CAMS | CAMS: An Annotated Corpus for Causal Analysis of Mental Health Issues in Social Media Posts | Paper | Dataset |

# Tools and other Resources

**APIs for Data Extraction**

1. Twitter: [The Tweepy API](https://docs.tweepy.org/en/stable/api.html)
2. Reddit: [Python Reddit API Wrapper (PRAW) API]( https://praw.readthedocs.io/en/stable/index.html)
3. Gab: [The garc API](https://pypi.org/project/garc/)
4. Facebook: [Graph API](https://pypi.org/project/python-facebook-api/)

**Processing Social Media**

1. Human text analysis package for social media and social scientific applications: [DLATK](https://dlatk.wwbp.org/)
2. Social Network Analysis: [Pajek](https://pypi.org/project/pajek-tools/), [Gephi](https://gephi.wordpress.com/tag/python/), [igraph](https://igraph.org/python/) and [NetworkX](https://networkx.org/).

# Recent Advances: Features and Methods


|**Year**| **Title of the Paper**       | **Link of the Paper** | **Link of the Dataset** | **Link of the Code** | **Results** |
|--------| ---------------------------- | --------------------- |------------------------ |--------------------- |-------------|
| 2018| Exploring and learning suicidal ideation connotations on social media with deep learning. | [Paper](https://aclanthology.org/W18-6223.pdf) | _Auth*_ | NA | F1: 82.7% |
| |Exploring the impact of evolutionary computing based feature selection in suicidal ideation detection. | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8858989) | Dataset| Code |  |
| |Deep Learning for Suicide and Depression Identification with Unsupervised Label Correction. | [Paper](https://arxiv.org/pdf/2102.09427.pdf) | Dataset| Code |  |
| |Emotion-Infused Models for Explainable Psychological Stress Detection. | [Paper](https://aclanthology.org/2021.naacl-main.230.pdf) | Dataset| Code |  |
| |Multimodal mental health analysis in social media. | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0226248) | Dataset| Code |  |
|| Feature Attention Network: Interpretable Depression Detection from Social Media. | [Paper](https://aclanthology.org/Y18-1070.pdf)| Dataset| Code |  |
| |Building and using personal knowledge graph to improve suicidal ideation detection on social media. IEEE Transactions on Multimedia.| [Paper](https://ieeexplore.ieee.org/iel7/6046/4456689/09308975.pdf?casa_token=NVcN4VExBigAAAAA:nQG-ZQaKsJcrcTpnsWHUN301Jg9wZapbdy4JUt4gAmdEsEoL0njDvw6hQvS6pbMvWShkNIFF)| Dataset| Code |  |
| |A hybridized feature extraction approach to suicidal ideation detection from social media post. | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9230733&casa_token=TYz9cnMmXssAAAAA:W_YLdEx03k-xN4s67PYticy7t8uYv_D8c0v1IK2FCNRwsws5H-G5NbfbaYit3J4gzLFHdXCC)| Dataset| Code |  |
| |Sensemood: Depression detection on social media. | [Paper](https://dl.acm.org/doi/pdf/10.1145/3372278.3391932?casa_token=qr_9LHm3WNsAAAAA:Ulea6DRqLb2bw9WrBNvA5ejT5MNed2V1aLZQORzY992B26QLdq3R9DWNh22VHoPC8v3kWPjcNryZ) | Dataset| Code |  |
| |Cooperative multimodal approach to depression detection in Twitter. | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/3775) | Dataset| Code |  |
| |A time-aware transformer based model for suicide ideation detection on social media. | [Paper](https://aclanthology.org/2020.emnlp-main.619.pdf) | Dataset| Code |  |
| |PHASE: Learning Emotional Phase-aware Representations for Suicide Ideation Detection on Social Media. | [Paper](https://aclanthology.org/2021.eacl-main.205.pdf) | Dataset| Code |  |
| |DepressionNet: A Novel Summarization Boosted Deep Framework for Depression Detection on Social Media. | [Paper](https://arxiv.org/pdf/2105.10878.pdf) | Dataset| Code |  |
| |Explainable Multi-class Classification of the CAMH COVID-19 Mental Health Data. | [Paper](https://arxiv.org/pdf/2105.13430.pdf) | Dataset| Code |  |
| |Find supports for the post about mental issues: More than semantic matching. | Paper | Dataset| Code |  |
| |Deep learning for depression detection from textual data.| Paper | Dataset| Code |  |
| |Deep learning for depression detection from textual data.| Paper | Dataset| Code |  |
| 2021 | Towards ordinal suicide ideation detection on social media. | Paper | Dataset | Code | |
| 2021 | Depression detection with multi-modalities using a hybrid deep learning model on social media | Paper | Dataset | Code | |
| 2021 |  Detection of depression-related posts in reddit social media forum | Paper | Dataset | Code | |
|  | Dual attention based suicide risk detection on social media | Paper | Dataset | Code | |
| | Latent suicide risk detection on microblog via suicide-oriented word embeddings and layered attention | Paper | Dataset | Code | |
| | SNAP-BATNET: Cascading author profiling and social network graphs for suicide ideation detection on social media | Paper | Dataset | Code | |
| | Cooperative multimodal approach to depression detection in Twitter | Paper | Dataset | Code | |
| | Detection of depression-related posts in reddit social media forum | Paper | Dataset | Code | |
| | Detecting Early Risk of Depression from Social Media User-generated Content | Paper | Dataset | Code | |

# Supporting theories for suicide

1. Klonsky, E. D., & May, A. M. (2015). The three-step theory (3ST):[ A new theory of suicide rooted in the “ideation-to-action” framework. ](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.705.7503&rep=rep1&type=pdf)International Journal of Cognitive Therapy, 8(2), 114-129.
2. Kang, N., You, J., Huang, J., Ren, Y., Lin, M. P., & Xu, S. (2019).[ Understanding the Pathways from Depression to Suicidal Risk from the Perspective of the Interpersonal–Psychological Theory of Suicide.](https://www.researchgate.net/profile/Nan-Kang-2/publication/324012197_Understanding_the_Pathways_from_Depression_to_Suicidal_Risk_from_the_Perspective_of_the_Interpersonal-Psychological_Theory_of_Suicide/links/5e1968c9a6fdcc283768a02a/Understanding-the-Pathways-from-Depression-to-Suicidal-Risk-from-the-Perspective-of-the-Interpersonal-Psychological-Theory-of-Suicide.pdf) Suicide and Life‐Threatening Behavior, 49(3), 684-694.

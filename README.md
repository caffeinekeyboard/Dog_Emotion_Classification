
# A Contrastive Learning Approach for Canine Emotion Analysis.

This repository is in association to a research paper submitted to the Animal-Computer Interaction Conference, scheduled on December 2nd, in Glasgow, UK.

We have experimented with three different contrastive learning frameworks, belonging to two different contrastive learning appraches, namely Simple Contrastive Learning and Momentum Contrast. 

These models were trained on a private original that we assembled over a period of 3 months. The seven labels are directly inspired from the Panksepp Seven Emotions.



## Performance Results:

| Emotion | Supervised ResNet-50 Accuracy | Unsupervised MoCo-v1 Accuracy |
|---|---|---|
| Caring | 94.74% | 34.61% |
| Exploring | 83.75% | 40.40% |
| Fear | 28.95% | 35.51% |
| Lust | 47.05% | 62.79% |
| Playing | 46.34% | 38.88% |
| Rage | 87.09% | 45.91% |
| Sadness | 78.57% | 44.37% |


## Access Locally:

Access our best model with a modified ResNet-34 encoder.

```bash
  wget https://raw.githubusercontent.com/caffeinekeyboard/Dog_Emotion_Classification/master/MoCo_Trials/labeled_Aarya/kaggle_sessions/session_APR11_953_96_R34/example_saved_models/encQ_best.pth
```
    
## Authors:

- [Aarya Bhave](https://github.com/caffeinekeyboard)
- [Alina Hafner](https://github.com/alinahafner)
- [Peter Gloor](https://github.com/pgloor)


## Related Repositories:
Here are some related projects

[Conference Home Page](https://www.aciconf.org/)\
[MoCo](https://github.com/facebookresearch/moco)\
[MoCoV3](https://github.com/facebookresearch/moco-v3)\
[SimCLR](https://github.com/google-research/simclr)


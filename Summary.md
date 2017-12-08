---
title: Summary
notebook: Summary.ipynb
nav_include: 3
---

## Contents
{:.no_toc}
*  
{: toc}


## Meaningful Findings

- (1)This finding can help **better understand the relationship** between **specific area of brian and AD**, and is extremely helpful for **mechanism researches**: The abnormal **Hippocampus** has significant relationship with AD and out-shaped **Gyrus** has a lot to do with AD. The result can be a good guidance for **biomarker selection** when detecting AD (e.g. choose Hippocampus as biomarker for diagnosis).


- (2)The results among different models also indicate that cognitive impairment and brain structure change is more likely to follow a linear relationship.


- (3)Indicating **Age** and **gender** both play an important role in cognitive impairment: **older people** are **more likely** to have **cognitive impairment**; **male** are **more likely** to have **light cognitive impairment**. Which is meaningful to cognitive impairment prevention.

## Future Work

- (1) Perform **second screening**: If time allowed, we would merge more follow-up data sets to longitudinally explore the relationship between cognitive impairment and brain structure change.


- (2) Try **more criterias** to select **important predictors**: the important features are based on tree-methods, if given more time, we would explore top 10 important features based on p-value in other classifiers, we may also try to decompose the proportion of varriance accounted by different predictors via PCA.


- (3) Try more **demension reduction methods** to reduce overfitting effects: because training accuracy are all higher than test accuracy, which is especially obvious in tree-based methods(even we have applied defult demension reduction functions).

- (4) Consider mixed effect model to take individual level variation into consideration, for example, **convert absolute volume** of specific area to **relative volume** (because different people has different size of brain).

- (5) Apply **more weighted methods** to increase the accuracy on AD, since we only tried weighted logistic model.


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

- (1)The top 10 important predictors can be a good guidance for **biomarker selection** when detecting AD (e.g. choose Hippocampus as biomarker for diagnosis). Help **better understand the relationship** between **specific area of brian and AD**, and is extremely helpful for **mechanism researches**: The abnormal **Hippocampus** has significant relationship with AD and abnormal **Gyrus** has a lot to do with AD. 


- (2)Comparison result of accuracy among models indicates that cognitive impairment and brain structure change is more likely to follow a **linear relationship**.


- (3)Both **age** and **gender** are playing an important role in cognitive impairment: **older people** are **more likely** to have **cognitive impairment**; **male** are **more likely** to have **light cognitive impairment**. Which is meaningful to cognitive impairment prevention.

## Future Work

- (1) Perform **second and third screening**: If time allowed, we would merge more follow-up data sets to longitudinally explore the relationship between cognitive impairment and brain structure change.


- (2) Base on **more criterias** to select **important predictors**: the important features are based on tree-methods by now. If given more time, we would explore top 10 important features based on **p-value** in other classifiers, we may also try to decompose the proportion of **varriance** accounted by different predictors in each PCA component.


- (3) Try more **demension reduction methods** to reduce overfitting effects: because training accuracy are all higher than test accuracy, which is especially obvious in tree-based methods(even we have applied defult demension reduction functions).

- (4) Consider **mixed effect model** to take **individual level variation** into consideration, for example, **convert absolute volume** of specific area to **relative volume** (because different people has different size of brain).

- (5) Apply **more weighted methods** to increase the classification accuracy on AD, since we only tried weighted logistic model so far.


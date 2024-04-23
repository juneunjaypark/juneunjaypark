---
title: Poster Presentation
date: '2024-04-06'
summary: Can We Detect Alcohol Intoxication Using The Voice?
---

[**Original Poster (Clear Image) Link Found Here!**](JP_Poster.png)

# <center> Authors </center>


![png](JP.png)

### Juneun Jay Park
- Graduate Student
- University of Illinois, Urbana-Champaign
- Social/Clinical-Community Psychology
- juneunp2@illinois.edu

![png](JH.png)

### Jiaxu Han
- Graduate Student
- University of Illinois, Urbana-Champaign
- Clinical-Community Psychology
- jiaxuh2@illinois.edu


![png](YL.png)

### Yang Lu
- Graduate Student
- University of Illinois, Urbana-Champaign
- Clinical-Community Psychology
- yanglu13@illinois.edu


![png](CF.png)

### Catharine Edith Ann Fairbairn
- Associate Professor
- University of Illinois, Urbana-Champaign
- Clinical-Community Psychology
- Cognitive Neuroscience Psychology
- Social-Personality Psychology
- cfairbai@illinois.edu

## <center> ML Results </center>

### Study 1 (Between-Subjects)
- RepeatedStratifiedKFold (n_splits=3, n_repeats=3)
- 48 groups (3 people nested in one group) x 3 = 144 cases

Fold 1: ROC AUC Score = 0.75
Fold 2: ROC AUC Score = 0.89
Fold 3: ROC AUC Score = 0.84

Repeat 1 Averaged ROC AUC: 0.81
Repeat 1 AUC 95% Confidence Interval: 0.67 - 0.93

Fold 4: ROC AUC Score = 0.77
Fold 5: ROC AUC Score = 0.71
Fold 6: ROC AUC Score = 0.89

Repeat 2 Averaged ROC AUC: 0.79
Repeat 2 AUC 95% Confidence Interval: 0.65 - 0.92

Fold 7: ROC AUC Score = 0.84
Fold 8: ROC AUC Score = 0.88
Fold 9: ROC AUC Score = 0.73

Repeat 3 Averaged ROC AUC: 0.79
Repeat 3 AUC 95% Confidence Interval: 0.63 - 0.92

Average ROC AUC Score Across All Repeats: 0.80
Average AUC 95% Confidence Interval Across All Repeats: 0.65 - 0.92

Sensitivity (True Positive Rate): 0.79
Specificity (True Negative Rate): 0.68

### Study 2 (Within-Subjects)
- StratifiedGroupKFold (n_splits=3)
- n_repeats=3 loop with testing different random states for variability
- 20 groups for alcohol and 20 groups for control (N=40 Groups) x 3 = 120 cases

--- Repeat 1 of 3 ---
  Fold 1: ROC AUC Score = 0.80
  Fold 2: ROC AUC Score = 0.78
  Fold 3: ROC AUC Score = 0.92

Repeat 1 Averaged ROC AUC: 0.83
Repeat 1 AUC 95% Confidence Interval: 0.68 - 0.94

--- Repeat 2 of 3 ---
  Fold 1: ROC AUC Score = 0.84
  Fold 2: ROC AUC Score = 0.78
  Fold 3: ROC AUC Score = 0.92

Repeat 2 Averaged ROC AUC: 0.84
Repeat 2 AUC 95% Confidence Interval: 0.68 - 0.94

--- Repeat 3 of 3 ---
  Fold 1: ROC AUC Score = 0.82
  Fold 2: ROC AUC Score = 0.76
  Fold 3: ROC AUC Score = 0.92

Repeat 3 Averaged ROC AUC: 0.83
Repeat 3 AUC 95% Confidence Interval: 0.69 - 0.95

Average ROC AUC Score Across All Repeats: 0.83
Average AUC 95% Confidence Interval Across All Repeats: 0.68 - 0.95

Sensitivity (True Positive Rate): 0.85
Specificity (True Negative Rate): 0.75

## <center> References </center>

- Fairbairn, C. E., Sayette, M. A., Amole, M. C., Dimoff, J. D., Cohn, J. F., & Girard, J. M. (2015). Speech volume indexes sex differences in the social-emotional effects of alcohol. *Experimental and Clinical Psychopharmacology*, *23*(4), 255–264. https://doi.org/10.1037/pha0000021

- Suffoletto, B., Anwar, A., Glaister, S., & Sejdic, E. (2023). Detection of Alcohol Intoxication Using Voice Features: A Controlled Laboratory Study. *Journal of studies on alcohol and drugs*, *84*(6), 808–813. https://doi.org/10.15288/jsad.22-00375
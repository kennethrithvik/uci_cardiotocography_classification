# uci_cardiotocography_classification
The dataset consists of measurements of fetal heart rate (FHR) and uterine contraction (UC) features on cardiotocograms classified by expert obstetricians.

## Source:

Marques de SÃƒÂ¡, J.P., jpmdesa '@' [gmail.com](http://gmail.com/), Biomedical Engineering Institute, Porto, Portugal.Bernardes, J., joaobern '@' [med.up.pt](http://med.up.pt/), Faculty of Medicine, University of Porto, Portugal.Ayres de Campos, D., sisporto '@' [med.up.pt](http://med.up.pt/), Faculty of Medicine, University of Porto, Portugal.

## Data Set Information:

2126 fetal cardiotocograms (CTGs) were automatically processed and the respective diagnostic features measured. The CTGs were also classified by three expert obstetricians and a consensus classification label assigned to each of them. Classification was both with respect to a morphologic pattern (A, B, C. ...) and to a fetal state (N, S, P). Therefore the dataset can be used either for 10-class or 3-class experiments.

## Attribute Information:

LB - FHR baseline (beats per minute)AC - # of accelerations per secondFM - # of fetal movements per secondUC - # of uterine contractions per secondDL - # of light decelerations per secondDS - # of severe decelerations per secondDP - # of prolongued decelerations per secondASTV - percentage of time with abnormal short term variabilityMSTV - mean value of short term variabilityALTV - percentage of time with abnormal long term variabilityMLTV - mean value of long term variabilityWidth - width of FHR histogramMin - minimum of FHR histogramMax - Maximum of FHR histogramNmax - # of histogram peaksNzeros - # of histogram zerosMode - histogram modeMean - histogram meanMedian - histogram medianVariance - histogram varianceTendency - histogram tendencyCLASS - FHR pattern class code (1 to 10) NSP - fetal state class code (N=normal; S=suspect; P=pathologic)

## Relevant Papers:

Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318

## Citation Request:

Please refer to the Machine Learning [Repository's citation policy.](http://archive.ics.uci.edu/ml/citation_policy.html)

_Source:_ [http://archive.ics.uci.edu/ml/datasets/Cardiotocography](http://archive.ics.uci.edu/ml/datasets/Cardiotocography)

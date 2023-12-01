---
title: Automated detection of artefacts in neonatal EEG with residual neural networks
authors:
- admin
- Minna Kauppila
- James A Roberts
- Sampsa Vanhatalo
- Nathan J Stevenson
date: '2021-01-01'
publishDate: '2023-11-30T04:00:27.295254Z'
publication_types:
- article-journal
publication: '*Computer Methods and Programs in Biomedicine*'

abstract: "Background and objective
To develop a computational algorithm that detects and identifies different artefact types in neonatal electroencephalography (EEG) signals.
Methods
As part of a larger algorithm, we trained a Residual Deep Neural Network on expert human annotations of EEG recordings from 79 term infants recorded in a neonatal intensive care unit (112 h of 18-channel recording). The network was trained using 10 fold cross validation in Matlab. Artefact types included: device interference, EMG, movement, electrode pop, and non-cortical biological rhythms. Performance was assessed by prediction statistics and further validated on a separate independent dataset of 13 term infants (143 h of 3-channel recording). EEG pre-processing steps, and other post-processing steps such as averaging probability over a temporal window, were also included in the algorithm.
Results
The Residual Deep Neural Network showed high accuracy (95%) when distinguishing periods of clean, artefact-free EEG from any kind of artefact, with a median accuracy for individual patient of 91% (IQR: 81%-96%). The accuracy in identifying the five different types of artefacts ranged from 57%-92%, with electrode pop being the hardest to detect and EMG being the easiest. This reflected the proportion of artefact available in the training dataset. Misclassification as clean was low for each artefact type, ranging from 1%-11%. The detection accuracy was lower on the validation set (87%). We used the algorithm to show that EEG channels located near the vertex were the least susceptible to artefact.
Conclusion
Artefacts can be accurately and reliably identified in the neonatal EEG using a deep learning algorithm. Artefact detection algorithms can provide continuous bedside quality assessment and support EEG review by clinicians or analysis algorithms."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- EEG
- Artefact Detection
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0169260721002686
url_code: ''
url_dataset: https://github.com/LockyWebb/NeonatalEEGArtefactDetection
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

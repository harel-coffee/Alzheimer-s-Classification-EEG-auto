# Alzheimer-s-Classification-EEG
Overview:
Alzheimer’s Disease (AD) is the most common neurodegenerative disease. It is typically late onset and can develop substantially before diagnosable symptoms appear. Electroencephalogram (EEG) could potentially serve as a noninvasive diagnostic tool for AD.  Machine learning can be helpful in making inferences about changes in frequency bands in EEG data and how these changes relate to neural function. The EEG data was sourced from 2014 paper titled Alzheimer’s disease patients classification through EEG signals processing by Fiscon et al. There were patients with AD, mild cognitive impairment (MCI), and healthy controls. The data was already preprocessed using a fast fourier transform (FFT) to take the data from the time domain to the frequency domain. There were differing levels of effectiveness in terms of classification but generally, Fisher’s discriminant analysis (FDA), relevance vector machine, and random forest approaches were most successful. Due to inconsistent feature importances in different models, conclusions about important frequency bands for classification were not able to be made at this time. Similarly, different frequencies were not able to be localized to different regions of the brain. Further research is necessary to develop more interpretable models for classification. 

Note:
The models can take a substantial amount of time to run, so I've included figures for those just interested in the results.
  
Results: 
The classification is not nearing the standards for clinical implementation, however, using wavelet feature extraction instead of the fast fourier transform might allow us to get a better results as suggested in the 2018 paper by Fiscon et al.

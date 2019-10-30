# INTERSPEECH 2019

## Spoken Language Processing

### Special Session 1-6: Spoken Language Processing for Children’s Speech

- [x] Fei Wu, Leibny Paola García-Perera, Daniel Povey, Sanjeev Khudanpur. *Advances in Automatic Speech Recognition for Child Speech Using Factored Time Delay Neural Network* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2980.html)]
  - `ASR` `TDNN-F` `Data augmentation` `Vocal tract length normalization (VTLN)`
  - TDNN-F: Subsample + SVD

### Poster 1-A: Speaker Recognition and Diarization

- [x] Zhifu Gao, Yan Song, Ian McLoughlin, Pengcheng Li, Yiheng Jiang, Li-Rong Dai. *Improving Aggregation and Loss Function for Better Embedding Learning in End-to-End Speaker Veriﬁcation System* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1489.html)]
  - `TI-SV` `VoxCeleb` `Multi-stage aggregation (MSA)` `DALoss`

- [x] Hitoshi Yamamoto, Kong Aik Lee, Koji Okabe, Takafumi Koshinaka. *Speaker Augmentation and Bandwidth Extension for Deep Speaker Embedding* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1508.html)]
  - `TI-SV` `VoxCeleb` `SITW` `Data augmentation` `DNN based bandwidth extension`
  - After voice conversion, e.g., speed perturbation, utterances should be assigned with new speaker labels
  - Use DNN to estimate missing filter banks for low-bandwidth features

### Special Session 4-A: The 2019 Automatic Speaker Veriﬁcation Spooﬁng and Countermeasures Challenge: ASVspoof Challenge - P

- [x] Cheng-I Lai, Nanxin Chen, Jesús Villalba, Najim Dehak. *ASSERT: Anti-Spoofing with Squeeze-Excitation and Residual neTworks* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1794.html)]
  - `TI-SV` `Anti-spoofing` `Acoustic features` `Squeeze-and-excitation` `Residual`

- [x] Bhusan Chettri, Daniel Stoller, Veronica Morfi, Marco A. Martínez Ramírez, Emmanouil Benetos, Bob L. Sturm. *Ensemble Models for Spoofing Detection in Automatic Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2505.html)]
  - `TI-SV` `Anti-spoofing` `Ensemble`
  - Ensemble traditional ML models (GMM, SVM) and deep models (CNN, CRNN, Sample-level CNN, Wave-U-Net)

### Oral 3-2: Speaker Recognition 1

- [x] Gautam Bhattacharya, Jahangir Alam, Patrick Kenny. *Seep Speaker Recognition: Modular or Monolithic?*
  - `TI-SV` `VoxCeleb` `AAM-Softmax` `Neural backend`
  - VoxCeleb1 EER 0.55%

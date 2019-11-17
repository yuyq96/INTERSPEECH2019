# INTERSPEECH 2019

## Spoken Language Processing

### Special Session 1-6: Spoken Language Processing for Children’s Speech

- [x] Fei Wu, Leibny Paola García-Perera, Daniel Povey, Sanjeev Khudanpur. *Advances in Automatic Speech Recognition for Child Speech Using Factored Time Delay Neural Network* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2980.html)]
  - `ASR` `TDNN-F` `Data augmentation` `Vocal tract length normalization (VTLN)`
  - TDNN-F: Subsample + SVD

### Oral 1-1: End-to-End Speech Recognition

- [x] Jason Li, Vitaly Lavrukhin, Boris Ginsburg, Ryan Leary, Oleksii Kuchaiev, Jonathan M. Cohen, Huyen Nguyen, Ravi Teja Gadde. *Jasper: An End-to-End Convolutional Neural Acoustic Model* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1819.html)]
  - `ASR` `LibriSpeech` `WSJ` `Hub5'00` `Conv1D` `Dense Residual` `NovoGrad`

### Poster 1-A: Speaker Recognition and Diarization

- [x] Zhifu Gao, Yan Song, Ian McLoughlin, Pengcheng Li, Yiheng Jiang, Li-Rong Dai. *Improving Aggregation and Loss Function for Better Embedding Learning in End-to-End Speaker Veriﬁcation System* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1489.html)]
  - `TI-SR` `VoxCeleb` `Multi-stage aggregation (MSA)` `DALoss`

- [x] Hitoshi Yamamoto, Kong Aik Lee, Koji Okabe, Takafumi Koshinaka. *Speaker Augmentation and Bandwidth Extension for Deep Speaker Embedding* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1508.html)]
  - `TI-SR` `VoxCeleb` `SITW` `Data augmentation` `DNN based bandwidth extension`
  - After voice conversion, e.g., speed perturbation, utterances should be assigned with new speaker labels
  - Use DNN to estimate missing filter banks for low-bandwidth features

### Special Session 4-A: The 2019 Automatic Speaker Veriﬁcation Spooﬁng and Countermeasures Challenge: ASVspoof Challenge - P

- [x] Cheng-I Lai, Nanxin Chen, Jesús Villalba, Najim Dehak. *ASSERT: Anti-Spoofing with Squeeze-Excitation and Residual neTworks* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1794.html)]
  - `TI-SR` `Anti-spoofing` `Acoustic features` `Squeeze-and-excitation` `Residual`

- [x] Bhusan Chettri, Daniel Stoller, Veronica Morfi, Marco A. Martínez Ramírez, Emmanouil Benetos, Bob L. Sturm. *Ensemble Models for Spoofing Detection in Automatic Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2505.html)]
  - `TI-SR` `Anti-spoofing` `Ensemble`
  - Ensemble traditional ML models (GMM, SVM) and deep models (CNN, CRNN, Sample-level CNN, Wave-U-Net)

### Oral 3-2: Speaker Recognition 1

- [x] Gautam Bhattacharya, Jahangir Alam, Patrick Kenny. *Deep Speaker Recognition: Modular or Monolithic?* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/3146.html)]
  - `TI-SR` `VoxCeleb` `AAM-Softmax` `Neural backend`
  - VoxCeleb1 EER 0.55%

- [x] Shuai Wang, Johan Rohdin, Lukáš Burget, Oldřich Plchot, Yanmin Qian, Kai Yu, Jan Černocký. *On the Usage of Phonetic Information for Text-independent Speaker Embedding Extraction* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/3036.html)]
  - `TI-SR` `VoxCeleb` `Multi-task learning` `Phonetic information`
  - Encourage phonetic information at the frame-level stage and suppress it at the segment-level stage

- [x] Mirco Ravanelli, Yoshua Bengio. *Learning Speaker Representations with Mutual Information* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2380.html)]
  - `TI-SR` `TIMIT` `LibriSpeech` `VoxCeleb` `Unsupervised learning` `Mutual information`

- [x] Lanhua You, Wu Guo, Li-Rong Dai, Jun Du. *Multi-Task Learning with High-Order Statistics for X-vector based Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2264.html)]
  - `TI-SR` `SRE` `VOiCES` `Multi-task learning`
  - Use the first- and higher-order statistics as the reconstruction targets

- [x] Zhanghao Wu, Shuai Wang, Yanmin Qian, Kai Yu. *Data Augmentation Using Variational Autoencoder for Embedding Based Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2248.html)]
  - `TI-SR` `SRE` `Data augmentation` `Conditional VAE`
  - Train CVAE on manually augmented samples, then generate more embeddings for training PLDA

- [x] Lanhua You, Wu Guo, Li-Rong Dai, Jun Du. *Deep Neural Network Embeddings with Gating Mechanisms for Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1746.html)]
  - `TI-SR` `SRE` `Gated CNN` `Gated-attention statistics pooling`

### Oral 4-1: Speaker and Language Recognition 1

- [ ] Jee-weon Jung, Hee-Soo Heo, Ju-ho Kim, Hye-jin Shim, Ha-Jin Yu. *RawNet: Advanced End-to-End Deep Neural Network Using Raw Waveforms for Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1982.html)]

- [ ] Wei Rao, Chenglin Xu, Eng Siong Chng, Haizhou Li. *Target Speaker Extraction for Multi-Talker Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1410.html)]

### Oral 5-5: Speaker Recognition Evaluation

### Special Session 7-3: The VOiCES from a Distance Challenge - O

### Special Session 7-A: The VOiCES from a Distance Challenge - P

### Oral 8-5: Speaker Recognition 2

- [ ] Themos Stafylakis, Johan Rohdin, Oldřich Plchot, Petr Mizera, Lukáš Burget. *Self-Supervised Speaker Embeddings* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2842.html)]

- [ ] Andreas Nautsch, Jose Patino, Amos Treiber, Themos Stafylakis, Petr Mizera, Massimiliano Todisco, Thomas Schneider, Nicholas Evans. *Privacy-Preserving Speaker Recognition with Cohort Score Normalisation* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2638.html)]

- [x] Yi Liu, Liang He, Jia Liu. *Large Margin Softmax Loss for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2357.html)]
  - `TI-SR` `VoxCeleb` `AM-Softmax`
  - VoxCeleb1 EER 2.00%
  - A large weight decay at 0.01

- [ ] Amirhossein Hajavi, Ali Etemad. *A Deep Neural Network for Short-Segment Speaker Recognition* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2240.html)]

- [x] Jianfeng Zhou, Tao Jiang, Zheng Li, Lin Li, Qingyang Hong. *Deep Speaker Embedding Extraction with Channel-Wise Feature Responses and Additive Supervision Softmax Loss Function* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1704.html)]
  - `TI-SR` `VoxCeleb` `Conv1D` `Squeeze-and-excitation (SE)` `Additive supervision softmax`
  - Use statistics pooling to replace global average pooling in squeeze-and-excitation

- [ ] Suwon Shon, Hao Tang, James Glass. *VoiceID Loss: Speech Enhancement for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1496.html)]

### Poster 6-A: Speaker Recognition and Anti-Spoofing

- [x] Lei Fan, Qing-Yuan Jiang, Ya-Qi Yu, Wu-Jun Li. *Deep Hashing for Speaker Identification and Retrieval* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2457.html)]
  - `TI-SR` `VoxCeleb` `Deep additive margin hashing (DAMH)`

### Poster 9-A: Speaker and Language Recognition 2

### Poster 10-A: Speaker Recognition 3

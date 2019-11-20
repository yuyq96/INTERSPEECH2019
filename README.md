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
  - `TI-SR` `NIST SRE` `VOiCES` `Multi-task learning`
  - Use the first- and higher-order statistics as the reconstruction targets

- [x] Zhanghao Wu, Shuai Wang, Yanmin Qian, Kai Yu. *Data Augmentation Using Variational Autoencoder for Embedding Based Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2248.html)]
  - `TI-SR` `NIST SRE` `Data augmentation` `Conditional VAE`
  - Train CVAE on manually augmented samples, then generate more embeddings for training PLDA

- [x] Lanhua You, Wu Guo, Li-Rong Dai, Jun Du. *Deep Neural Network Embeddings with Gating Mechanisms for Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1746.html)]
  - `TI-SR` `NIST SRE` `Gated CNN` `Gated-attention statistics pooling`

### Oral 4-1: Speaker and Language Recognition 1

- [ ] Jee-weon Jung, Hee-Soo Heo, Ju-ho Kim, Hye-jin Shim, Ha-Jin Yu. *RawNet: Advanced End-to-End Deep Neural Network Using Raw Waveforms for Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1982.html)]

- [ ] Wei Rao, Chenglin Xu, Eng Siong Chng, Haizhou Li. *Target Speaker Extraction for Multi-Talker Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1410.html)]

### Oral 5-5: Speaker Recognition Evaluation

### Special Session 7-3: The VOiCES from a Distance Challenge - O

### Special Session 7-A: The VOiCES from a Distance Challenge - P

### Oral 8-5: Speaker Recognition 2

- [x] Themos Stafylakis, Johan Rohdin, Oldřich Plchot, Petr Mizera, Lukáš Burget. *Self-Supervised Speaker Embeddings* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2842.html)]
  - `TI-SR` `VoxCeleb` `SITW` `Self-supervised`
  - Reconstruct frames using speaker embedding and ASR outputs

- [ ] Andreas Nautsch, Jose Patino, Amos Treiber, Themos Stafylakis, Petr Mizera, Massimiliano Todisco, Thomas Schneider, Nicholas Evans. *Privacy-Preserving Speaker Recognition with Cohort Score Normalisation* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2638.html)]

- [x] Yi Liu, Liang He, Jia Liu. *Large Margin Softmax Loss for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2357.html)]
  - `TI-SR` `VoxCeleb` `AM-Softmax`
  - VoxCeleb1 EER 2.00%
  - A large weight decay at 0.01

- [x] Amirhossein Hajavi, Ali Etemad. *A Deep Neural Network for Short-Segment Speaker Recognition* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2240.html)]
  - `TI-SR` `VoxCeleb` `Short duration` `Multi-stage aggregation`
  - Apply non-linear aggregator over embeddings from different stage

- [x] Jianfeng Zhou, Tao Jiang, Zheng Li, Lin Li, Qingyang Hong. *Deep Speaker Embedding Extraction with Channel-Wise Feature Responses and Additive Supervision Softmax Loss Function* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1704.html)]
  - `TI-SR` `VoxCeleb` `Conv1D` `Squeeze-and-excitation (SE)` `Additive supervision softmax`
  - Use statistics pooling to replace global average pooling in squeeze-and-excitation

- [x] Suwon Shon, Hao Tang, James Glass. *VoiceID Loss: Speech Enhancement for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1496.html)]
  - `TI-SR` `Speech enhancement (SE)` `VoxCeleb` `Mask` `Conv1D`

### Poster 6-A: Speaker Recognition and Anti-Spoofing

- [ ] Anderson R. Avila, Jahangir Alam, Douglas O’Shaughnessy, Tiago H. Falk. *Blind Channel Response Estimation for Replay Attack Detection* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2956.html)]

- [ ] Ankur T. Patil, Rajul Acharya, Pulikonda Aditya Sai, Hemant A. Patil. *Energy Separation-Based Instantaneous Frequency Estimation for Cochlear Cepstral Feature for Replay Spoof Detection* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2742.html)]

- [x] Victoria Mingote, Antonio Miguel, Dayana Ribas, Alfonso Ortega, Eduardo Lleida. *Optimization of False Acceptance/Rejection Rates and Decision Threshold for End-to-End Text-Dependent Speaker Verification Systems* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2550.html)]
  - `TD-SR` `RSR2015` `approximate DCF loss`

- [x] Lei Fan, Qing-Yuan Jiang, Ya-Qi Yu, Wu-Jun Li. *Deep Hashing for Speaker Identification and Retrieval* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2457.html)]
  - `TI-SR` `VoxCeleb` `Deep additive margin hashing (DAMH)`

- [ ] Mirko Marras, Paweł Korus, Nasir Memon, Gianni Fenu. *Adversarial Optimization for Dictionary Attacks on Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2430.html)]

- [ ] Tharshini Gunendradasan, Eliathamby Ambikairajah, Julien Epps, Haizhou Li. *An Adaptive-Q Cochlear Model for Replay Spoofing Detection* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2361.html)]

- [ ] Sungrack Yun, Janghoon Cho, Jungyun Eum, Wonil Chang, Kyuwoong Hwang. *An End-to-End Text-Independent Speaker Verification Framework with a Keyword Adversarial Network* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2208.html)]

- [x] Soonshin Seo, Daniel Jun Rim, Minkyu Lim, Donghyun Lee, Hosung Park, Junseok Oh, Changmin Kim, Ji-Hwan Kim. *Shortcut Connections Based Deep Speaker Embeddings for End-to-End Speaker Verification System* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2195.html)]
  - `TI-SR` `VoxCeleb` `Multi-stage aggregation (MSA)`

- [ ] Chang Huai You, Jichen Yang, Huy Dat Tran. *Device Feature Extractor for Replay Spoofing Detection* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2137.html)]

- [ ] Hongji Wang, Heinrich Dinkel, Shuai Wang, Yanmin Qian, Kai Yu. *Cross-Domain Replay Spoofing Attack Detection Using Domain Adversarial Training* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2120.html)]

- [x] A. Kanagasundaram, S. Sridharan, G. Sriram, S. Prachi, C. Fookes. *A Study of x-Vector Based Speaker Recognition on Short Utterances* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1891.html)]
  - `TI-SR` `NIST SRE`
  - Low-dimensional embedding from deeper layer performs better in short utterance evaluation
  - Duration of development and evaluation utterances should be matched

- [ ] Nanxin Chen, Jesús Villalba, Najim Dehak. *Tied Mixture of Factor Analyzers Layer to Combine Frame Level Representations in Neural Speaker Embeddings* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1782.html)]

- [ ] Buddhi Wickramasinghe, Eliathamby Ambikairajah, Julien Epps. *Biologically Inspired Adaptive-Q Filterbanks for Replay Spoofing Attack Detection* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1535.html)]

- [ ] Pierre-Michel Bousquet, Mickael Rouvier. *On Robustness of Unsupervised Domain Adaptation for Speaker Recognition* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1524.html)]

- [x] Suwon Shon, Younggun Lee, Taesu Kim. *Large-Scale Speaker Retrieval on Random Speaker Variability Subspace* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1498.html)]
  - `TI-SR` `VoxCeleb` `LSH`
  - Projecting on random speaker-variability subspace (generate transform matrix by applying LDA on random subset of speakers) instead of random subspace

### Poster 9-A: Speaker and Language Recognition 2

- [x] Qing Wang, Pengcheng Guo, Sining Sun, Lei Xie, John H.L. Hansen. *Adversarial Regularization for End-to-End Robust Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2983.html)]
  - `TI-SR` `TIMIT` `GE2E` `Fast gradient-sign method (FGSM)` `Local distributional smoothness (LDS)`

- [x] João Monteiro, Jahangir Alam, Tiago H. Falk. *Combining Speaker Recognition and Metric Learning for Speaker-Dependent Representation Learning* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2974.html)]
  - `TI-SR` `NIST SRE` `Triplet loss`

- [ ] Yang Zhang, Lantian Li, Dong Wang. *VAE-Based Regularization for Deep Speaker Embedding* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2486.html)]


- [ ] Victoria Mingote, Diego Castan, Mitchell McLaren, Mahesh Kumar Nandwana, Alfonso Ortega, Eduardo Lleida, Antonio Miguel. *Language Recognition Using Triplet Neural Networks* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2437.html)]


- [ ] Youngmoon Jung, Younggwan Kim, Hyungjun Lim, Yeunju Choi, Hoirin Kim. *Spatial Pyramid Encoding with Convex Length Normalization for Text-Independent Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/2177.html)]


- [ ] Hee-Soo Heo, Jee-weon Jung, IL-Ho Yang, Sung-Hyun Yoon, Hye-jin Shim, Ha-Jin Yu. *End-to-End Losses Based on Speaker Basis Vectors and All-Speaker Hard Negative Mining for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1986.html)]

- [x] Yiheng Jiang, Yan Song, Ian McLoughlin, Zhifu Gao, Li-Rong Dai. *An Effective Deep Embedding Learning Architecture for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1606.html)]
  - `TI-SR` `VoxCeleb` `DenseNet` `Squeeze-and-excitation`

- [ ] Xiaoyi Qin, Danwei Cai, Ming Li. *Far-Field End-to-End Text-Dependent Speaker Verification Based on Mixed Training Data with Transfer Learning and Enrollment Data Augmentation* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1542.html)]


- [x] Zongze Ren, Guofu Yang, Shugong Xu. *Two-Stage Training for Chinese Dialect Recognition* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1522.html)]
  - `LR`
  - First train an acoustic model then fix the parameters of CNN and replace the RNN to train a language identification model

- [ ] Ryota Kaminishi, Haruna Miyamoto, Sayaka Shiota, Hitoshi Kiya. *Investigation on Blind Bandwidth Extension with a Non-Linear Function and its Evaluation of x-Vector-Based Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1510.html)]


- [ ] Umair Khan, Miquel India, Javier Hernando. *Auto-Encoding Nearest Neighbor i-Vectors for Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1444.html)]


- [ ] Siqi Zheng, Gang Liu, Hongbin Suo, Yun Lei. *Towards a Fault-Tolerant Speaker Verification System: A Regularization Approach to Reduce the Condition Number* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1442.html)]


- [ ] Hassan Taherian, Zhong-Qiu Wang, DeLiang Wang. *Deep Learning Based Multi-Channel Speaker Recognition in Noisy and Reverberant Environments* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1428.html)]


- [ ] Joon-Young Yang, Joon-Hyuk Chang. *Joint Optimization of Neural Acoustic Beamforming and Dereverberation with x-Vectors for Robust Speaker Verification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1356.html)]


- [ ] Xiaoxiao Miao, Ian McLoughlin, Yonghong Yan. *A New Time-Frequency Attention Mechanism for TDNN and CNN-LSTM-TDNN, with Application to Language Identification* [[INTERSPEECH 2019](https://www.isca-speech.org/archive/Interspeech_2019/abstracts/1256.html)]

### Poster 10-A: Speaker Recognition 3

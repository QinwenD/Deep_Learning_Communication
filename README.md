## Papers
* T. J. O’Shea, T. Erpek and T.C. Clancy, Deep learning based MIMO communications. arXiv preprint arXiv:1707.07980, 2017.[link](https://arxiv.org/abs/1707.07980)
  * Single user MIMO communications from code to code
  * Novelty: Introduced a novel scheme for MIMO Channel autoencoder and demonstrated that it is possible to achieve and exceed the performance of the conventional spatial diversity MIMO systems using Deep Learning and autoencoders.
  * Simulation and Results:
    * Baseline Configurations:2*1 Alamouti STBC and 2*2 MIMO systems with QPSK modulation and Rayleigh fading channel with noise
    * The autoencoder exceed the performance of the STBC code when the SNR value is above approximately 15dB
    * They also modified their NN implementation to consider the challenge in real world systems of the case where a compact v-bit representation of the CSI is available at the transmitter instead of perfect real-valued CSI. And the result showed that quantization of the CSI improves the performance of their system for certain values of v.
  * Methods: Autoencoder
  * Comments: This work showed that the autoencoder can perform better than the current day methods. The work needed to continue to evaluate the performance on larger-scale MIMO arrangements and massive MIMO.

* T. J. O’Shea, T. Roy and T. C. Clancy, "Over-the-Air Deep Learning Based Radio Signal Classification," in IEEE Journal of Selected Topics in Signal Processing, vol. 12, no. 1, pp. 168-179, Feb. 2018.[link](https://ieeexplore.ieee.org/document/8267032)
  * Modulation classification
  * The author compared the performance of deep learning based radio signal classification with the baseline method using higher order moments and strong boosted gradient tree classification across a range of configurations and channel impairments.
  * Methods: Convolutional Neural Network, VGG architecture, Residual Neural Network

* C. Zhang, P. Patras and H. Haddadi, "Deep Learning in Mobile and Wireless Networking: A Survey," in IEEE Communications Surveys & Tutorials.[link](https://ieeexplore.ieee.org/document/8666641)
  * A long Survey about the application of Deep Learning in wireless networking.
  * A good index to find papers.
  
* F. Liang, C. Shen and F. Wu, "Exploiting Noise Correlation for Channel Decoding with Convolutional Neural Networks," 2018 IEEE International Conference on Communications (ICC), Kansas City, MO, 2018, pp. 1-6.[link](https://ieeexplore.ieee.org/document/8422290)
  * Decode the LDPC codes under colored noise
  * Novelty: A novel iterative BP-CNN architecture with a new loss function which involves skewness and kurtosis.
  * Method: Belief propagation-convolutional neural network (BP-CNN)
  * Comments: The results show that the BP-CNN with the new loss function has better performance than the baseline BP-CNN and BP decoder. However, the author doesn’t tell us how to find new loss function in other scenarios, which limits the contribution of this paper.

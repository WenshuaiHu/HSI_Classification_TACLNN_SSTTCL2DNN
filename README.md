# Lightweight Tensor Attention-Driven ConvLSTM Neural Network for Hyperspectral Image Classification

Paper web page: [Lightweight Tensor Attention-Driven ConvLSTM Neural Network for Hyperspectral Image Classification.](https://ieeexplore.ieee.org/document/9369839)

Related code will be released gradually.

# Abstract:

Recurrent neural networks, especially the convolutional long short-term memory (ConvLSTM), have attracted plenty of attention and shown promising results due to their ability in modeling long-term dependencies in many research fields. In this paper, a lightweight tensor attention-driven ConvLSTM neural network (TACLNN) is proposed for hyperspectral image (HSI) classification. Firstly, to reduce the trainable parameters and memory requirements of ConvLSTM (specifically, the 2-D version of LSTM, i.e., ConvLSTM2D), a lightweight ConvLSTM2D cell is developed by utilizing tensor-train decomposition, resulting in a TT-ConvLSTM2D cell, with which a spatial-spectral TT-ConvLSTM 2-D neural network (SSTTCL2DNN) is built. However, it is inevitable for SSTTCL2DNN to obtain lower accuracies for HSI classification. To recover the accuracy loss caused by the TT-ConvLSTM2D cell in SSTTCL2DNN, a learnable tensor attention residual block (TARB) module is built to further enhance its geometrical structure. When applied to three widely used HSI benchmarks, the proposed TACLNN model outperforms several state-of-the-art methods for HSI classification. In addition, the proposed TACLNN can effectively reduce the number of parameters and storage requirements achieving higher classification accuracies as compared to other competitive baselines.


# Paper
Please cite our paper if you find the code or dataset useful for your research.

  @ARTICLE{9369839,
  author={Hu, Wen-Shuai and Li, Heng-Chao and Deng, Yang-Jun and Sun, Xian and Du, Qian and Plaza, Antonio},<br>
  journal={IEEE Journal of Selected Topics in Signal Processing}, <br>
  title={Lightweight Tensor Attention-Driven ConvLSTM Neural Network for Hyperspectral Image Classification}, <br>
  year={2021},<br>
  volume={15},<br>
  number={3},<br>
  pages={734-745},<br>
  keywords={Tensors;Feature extraction;Convolution;Computational modeling;Adaptation models;Recurrent neural networks;Logic gates;Attention mechanism;convolutional long short-term memory;hyperspectral image classification;lightweight cell;performance recovery;tensor representation},<br>
  doi={10.1109/JSTSP.2021.3063805}}

# Requirements
  Tensorflow V1
# Note

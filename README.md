# Carrier-Frequency-Offset
Detailed code used for researching machine learning for carrier frequency offset

The main page is a colab journal which includes the process, training, and evaluation of many different models considered for carrier frequency offset estimation, aimed at 5G and 6G applications.

This is in progress, I will update as more information is publicly available.

<b>Please contact and cite our research if you use this code.</b>

@INPROCEEDINGS{Drei2020:DeepCFO,</br>
AUTHOR={Ryan M. Dreifuerst and Robert Heath and Mandar N. Kulkarni and Jianzhong
Zhang},</br>
TITLE={{Deep Learning-based Carrier Frequency Offset Estimation with One-Bit
ADCs}},</br>
BOOKTITLE={2020 IEEE 21st International Workshop on Signal Processing Advances in
Wireless Communications (SPAWC) (IEEE SPAWC 2020)},</br>
ADDRESS="Atlanta, USA",</br>
DAYS=26,</br>
MONTH=may,</br>
YEAR=2020,</br>
KEYWORDS={Carrier frequency offset; millimeter wave; MIMO; deep learning; one-bit
receivers}</br>
}
</br>
<b>
Here is the abstract from our work.</b>
<i>
Low resolution architectures are a power efficient
solution for high bandwidth communication at millimeter wave
and terahertz frequencies. In such systems, carrier synchronization
is important yet has not received much attention. In this
paper, we develop and analyze deep learning architectures for estimating
the carrier frequency of a complex sinusoid in noise from
the 1-bit samples of the in-phase and quadrature components.
Carrier frequency offset estimation from a sinusoid is used in
GSM and is a first step towards developing a more comprehensive
solution with other kinds of signals. We train four different deep
learning architectures each on eight datasets which represent
possible training considerations. Specifically, we consider how
training with various signal to noise ratios (SNR), quantization,
and sequence lengths affects estimation error. Further, we analyze
each architecture in terms of scalability for MIMO receivers. In
simulations, we compare computational complexity, scalability,
and mean squared error (MSE) versus classic signal processing
techniques. We demonstrate that training with quantized data,
drawn from signals with SNRs between 0-10dB tends to improve
deep learning estimator performance across the entire SNR range
of interest. We conclude that convolutional models have the best
performance, while also scaling for massive MIMO situations
more efficiently than FFT models. Our approach is able to
accurately estimate carrier frequencies from 1-bit quantized data
with fewer pilots and lower signal to noise ratios (SNRs) than
traditional signal processing methods. </i>

## DigitalCommunication
 - 이 프로젝트는 digital communication model을 구현하였다.
 
 - AWGN, AWGN+multi path 환경에서의 QPSK, 16-QAM 변조방식을 구현
   
 - BER vs SNR, BER vs Eb/No을 그려 총 8개의 BER curve를 비교하였다.


### Tx model
 ##### - Input data -> Scramble -> Channel enCoding -> Symbol Mapping -> OverSampling -> PulseShaping -> AWGN or AWGN + MultiPath Channel

### Rx model
 #### - Tx data -> Matched Filter -> ADC -> De Modulation -> Channel enCoding -> Scramble

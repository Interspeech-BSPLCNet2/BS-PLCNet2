# BS-PLCNet


Demo clips for "BS-PLCNet 2: Two-stage Band-split Packet Loss Concealment Network with Intra-model Knowledge Distillation".


Abstract:
Audio packet loss is an inevitable problem in real-time speech communication. A band-split packet loss concealment network (BS-PLCNet) targeting full-band signals was recently proposed. Although it performs superiorly in the ICASSP 2024 PLC Challenge, BS-PLCNet is a large model with high computational complexity of 8.95G FLOPS. This paper presents its updated version, BS-PLCNet 2, to reduce computational complexity and improve performance further. Specifically, to compensate for the missing future information, in the wide-band module, we design a dual-path encoder structure (with non-causal and causal path) and leverage an intra-model knowledge distillation strategy to distill the future information from the non-causal teacher to the casual student. Moreover, we introduce a lightweight post-processing module after packet loss restoration to recover speech distortions and remove residual noise in the audio signal. With only 40% of original parameters in BS-PLCNet, BS-PLCNet 2  brings 0.18 PLCMOS improvement on the ICASSP 2024 PLC challenge blind set, achieving state-of-the-art performance on this dataset.
 

The demo page: [BS-PLCNet 2](https://Interspeech-BSPLCNet2.github.io/BS-PLCNet2/)

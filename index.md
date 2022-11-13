# Introduction

This is the demo page of our paper: [On the robustness of non-intrusive speech quality model by adversarial examples](https://arxiv.org/), and the codes can be found [here](https://github.com/hsinyilin19/adversarial_example_speech_quality_predictor).

In the paper we found adversarial examples for DNSMOS, a CNN-based speech quality predictor. In this demo, we share the perturbed and original wav files from three datasets: [*DNS*](https://www.microsoft.com/en-us/research/academic-program/deep-noise-suppression-challenge-interspeech-2020/), [*TIMIT*](https://catalog.ldc.upenn.edu/LDC93s1), and [*Voice-Bank (VCTK)*](https://datashare.ed.ac.uk/handle/10283/2791).

## DNS

###### Sample 1 
<pre>[original: SIG=1.65,BAK=1.58,OVR=1.34],     [perturbed: SIG=4.30,BAK=4.53,OVR=4.02]</pre>
<audio style="width:300px" controls="controls">
	<source src="wavs/DNS/original_DNSMOS_SIG_1.65_BAK_1.58_OVR_1.34_book_00154_chp_0002_reader_05605_39_MCTAYvbXrQg-IQ_mQin_vH0-ZkNr4V4l5rw_snr0_fileid_48796.wav" type="audio/wav" />
</audio>
<audio style="width:300px" controls="controls">
	<source src="wavs/DNS/attacked_DNSMOS_SIG_4.30_BAK_4.53_OVR_4.02_book_00154_chp_0002_reader_05605_39_MCTAYvbXrQg-IQ_mQin_vH0-ZkNr4V4l5rw_snr0_fileid_48796.wav" type="audio/wav" />
</audio>



## TIMIT

###### FELC0_SX36 [original]   FELC0_SX36 [perturbed]
<audio style="width:150px" controls="controls">
	<source src="wavs/DNS/FELC0_SX36.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/DNS/FELC0_SX36.wav" type="audio/wav" />
</audio>


## VCTK

###### FELC0_SX36 [original]   FELC0_SX36 [perturbed]
<audio style="width:150px" controls="controls">
	<source src="wavs/DNS/FELC0_SX36.wav" type="audio/wav" />
</audio>
<audio style="width:150px" controls="controls">
	<source src="wavs/DNS/FELC0_SX36.wav" type="audio/wav" />
</audio>


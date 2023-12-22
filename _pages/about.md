---
permalink: /
title: "Welcome to Sayan's Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently a postdoctoral scholar from the Integrated Power Electronics laboratory at the Electronics and Computer Engineering Department in Hong Kong University of Science and Technology. I was born and brought up in India and completed my undergraduate studies at the National Institute of Technology, Durgapur, India. After my graduation, I briefly worked at Coal India, a Fortune 500 company, for almost two years. There, I understood the demand for a multipurpose wearable device to cope with the increasing degree of automation and reduce manual intervention in the industrial environment. Later, based on that knowledge, I developed my start-up "Wecare Medservice LLP" in the wearable domain and won the top start-up competitions in India. In my startup, I mostly worked on the cardiorespiratory and biochemical signal processing domain and developed a beta prototype for a multiparameter monitoring wearable for performance enhancement in working-class people. I realized my increasing interest in high-end CMOS design during my start-up days. So, I decided to pursue PhD at HKUST under Prof Wing Hung Ki. My thesis topic is “power and data transmission efficacy improvement of the on-chip encrypted implantable medical device”.  My work during PhD opens up avenues for a closely packed encrypted retinal stimulation system. 

My research interest can be broadly classified into four segments.

## Inductive or Ultrasonically Powered Secured Implantable Medical Devices for Neural/Retinal/Auditory Stimulation 
I would like to develop a secured reconfigurable multimodal neurostimulator system on a chip (SoC) design that can record, process, and stimulate deep brain activity in humans/animals. Each recording channel changes its configuration depending on whether the channel is assigned to record voltage {action potentials and single-neuron LFP activity during stationary and ambulatory behavior in humans local field potential (LFP)} or current signal (concentration of neurotransmitters). It can lead to impactful discoveries within the neuroscience field and contribute to the development of novel therapies for neurological and psychiatric disorders. 

## Machine Learning or Deep learning-based Biosignal Processing (ex. - cuffless BP estimation, Signal Quality Estimation)

## Wireless Multimodality System-on-a-chip Design for Biochemical (sweat/urine) and Physiological (ECG, PPG) Signal Acquisition

## Power Management IC Design 

If you are interested in the above areas and want to have a discussion, feel free to send me an email. 

## PhD Thesis Abstract
Implantable Medical Devices (IMDs) have been widely used to tackle different health issues. With the advancement in VLSI technology, sophisticated IMDs have been developed for extending sensing and stimulation capability with low-power wireless data transmissions. The first part of this thesis studies the power-delivering capability of a Class-D power amplifier at different operating conditions when driving either a series-series or a series-parallel (transmitter (TX) - receiver (RX)) resonant tank of a wireless power transfer (WPT) system. The accuracies between analytical and simulated results and between analytical and measured results are better than 98% and 95%, respectively.

Due to loading and coupling variations, the rectified DC voltage at the receiver’s output of the IMD is not steady. Conventionally, a global control loop that combines the power and data transfer links is designed to counteract the above variations. A detection (or tertiary) coil, co-planar with the transmitter coil, is used to receive the backscattered signal at the transmitter side. The second part of this thesis discusses the improvement of a previously designed retinal implant. In the first phase, a framework is designed for improving the tertiary coil through analytical guidelines, and an area-saving inner-tertiary coil structure is developed for a closely packed head-mounted retinal stimulation system. In the second phase, an on-chip embedded encrypted data transmission system is developed using lightweight prince cipher and eFUSE silicon IP provided by the foundry. The standalone eFUSE IP is modified to relax input pin limitations and high current consumption issues during the initialization of the IMD. The proposed divide-and-conquer approach maintains the cipher strength and reduces the area and power consumption of the cipher circuits by 2.7 and 5.1 times, respectively. The whole system with the optical nerve stimulator is fabricated with 0.18 micrometer BCDlite (Bipolar-CMOS-DMOS) process, and measurement results show the proposed encryption scheme is nearly impossible to be cracked by a modern brute-force parallel key-guessing machine. 

In the third part of this thesis, a complete WPT system with transmitter and receiver chips developed in 0.18-micrometer BCDlite is presented. The all-NMOS transmitter has fast high-side level shifters based on the current mirror principle and adaptive dead-time controller, reduces the delay difference between the high-side and low-side gate driving paths. The proposed adaptive digitally controlled active rectifier of the receiver achieved high efficiency by eliminating losses due to turn-on/off delay, reverse current, and multiple pulsing. The adaptive delay compensation circuits prevent degradation of efficiency and link gain at different PVT (process, voltage, temperature) corners. The fast delay control loop adjusts the durations of delay by at least two times faster than state-of-the-art architectures. In closed-loop control of the WPT system, the receiver regulates the output voltage using a local linear current-sink-based regulator. In addition, wireless hysteretic control of a reconfigurable power amplifier achieves global power regulation. The proposed design has a higher level of integration and lower circuit complexity than previous works and achieves a higher operating range and a faster load-transient response. Furthermore, under high coupling conditions, split frequency locations can be used for FSK-based closed-loop control that allow for simultaneous wireless power and data transfer. The frequency-modulated power carrier is processed by a frequency-to-amplitude converter of the receiver and is converted to an amplitude-modulated signal. A rule-based approach is adopted in discussing the trade-off among link gain, bandwidth, and efficiency as a function of distance during split-frequency data transfer.

Thanks for visiting my website. 


======

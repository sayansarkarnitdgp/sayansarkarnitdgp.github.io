---
permalink: /
title: "Welcome to Sayan's Website"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Sayan Sarkar is currently a Postdoctoral Scholar in the Integrated Circuit and System Laboratory at the Department of Electrical Engineering and Computer Science, Penn State University (USA), under the mentorship of Prof. Mehdi Kiani. Originally from West Bengal, India, he completed his undergraduate studies in Electronics and Communication Engineering at the National Institute of Technology (NIT), Durgapur. During his undergraduate years, he gained diverse research and industry experience through internships at CESC, NTPC, and premier academic institutions such as IIT Delhi and IIT Bombay. Following graduation, he briefly worked in the Electrical and Mechanical division of Coal India Limited for nearly two years. During this period, he co-founded Wecare Medservice LLP, where he led the development of a multipurpose wearable device aimed at enhancing the performance and safety of working-class individuals, such as underground miners. This innovation was supported under the Coal India New Initiative Program and received national recognition through prestigious platforms, including EUREKA (Winner, IIT Bombay) and EMPRESARIO (Runner-up, IIT Kharagpur). The initiative was also recognized by SINE, IIT Bombay. Sayan pursued his PhD in the Department of Electronic and Computer Engineering at the Hong Kong University of Science and Technology (HKUST) under Prof. Wing-Hung Ki. His doctoral research focused on enhancing the power and data transmission efficiency of encrypted wireless power transfer systems. He has received several accolades for academic excellence and innovation, including the General Electric Edison Challenge Award and the Air India Rank and Bolt Award. To date, he has authored nearly 40 peer-reviewed publications. His research interests span across biomedical instrumentation—particularly implantable and wearable medical devices—biosignal processing, and power management integrated circuit (IC) design.

No. of tape-outs - 5
H-index - 10
Citation count - 250+

My research interests can be broadly classified into four segments. For ease of understanding, I have added a list of standout papers (not necessarily our work!) in the relevant field, which helped me in learning.

## Inductive or Ultrasonically Powered Secured Implantable Medical Devices for Neural/Retinal/Auditory Stimulation 
I would like to develop a secured reconfigurable multimodal system on a chip (SoC) design that can record, process, and stimulate deep brain activity in humans/animals. Each recording channel changes its configuration depending on whether the channel is assigned to record voltage {action potentials and single-neuron LFP (local field potential) activity during stationary and ambulatory behavior in humans LFP} or current signal (concentration of neurotransmitters). It can lead to impactful discoveries within the neuroscience field and contribute to the development of novel therapies for neurological and psychiatric disorders. Similarly, electrical or optical stimulation for Deep brain stimulation (DBS) has been proven therapeutically effective for neurological disorders such as Parkinson’s disease, epilepsy, and Alzheimer’s disease. DBS involves injecting a designated amount of charge into the target neural tissue to initiate the functional response of neurons in patients unresponsive to pharmaceutical treatment.

![plot](/images/implant.jpg)


#### Reference papers - Jia [TBioCAS'2020]

## Machine Learning or Deep learning-based Biosignal Processing (ex. - cuffless Blood Pressure Estimation, Signal Quality Estimation)
My research interest mostly focuses on cardiorespiratory signal processing. Apart from that, I am interested in Neural Signal Processing to understand neurological and psychiatric disorders. High blood pressure is a significant risk factor that can damage vital organs like the heart, brain, and kidneys and contributes >10 M cardiovascular deaths each year around the world. Physicians widely adopted different techniques to monitor an individual's cardiovascular health. One such technique is the periodic measurement of blood pressure (BP). BP can fluctuate rapidly over time and is influenced by factors like stress, emotions, food, and exercise. Medications can manage hypertension (high BP), but continuous and accurate BP measurement becomes crucial in managing a person’s overall health. Popular Cardiorespiratory signals are Electrocardiography (ECG), Photoplethysmography (PPG) etc. The ECG waveform gives information about the electrical activity of the cardiomyocytes (cells in the heart). The PPG signal is the low-pass filtered version of the Arterial Blood Pressure (ABP) waveform that provides valuable information about the mechanical activity of the heart. However, PPG signal acquisition is relatively easy, and it gives us important information about our heart rate, blood pressure, oxygen levels, breathing rate, and how our blood vessels are aging. PPG signals are sensitive to multiple biological, and environmental factors that impact measurement results. Biosignal processing can be broadly divided into three segments: (a) signal acquisition, (b) parameter estimation, and (c) Post-processing. Analog front end can't differentiate between good or bad quality signals. Therefore, it is important to check the quality of the signal (SQI) before post-processing to prevent false alarms. I would like to focus on lightweight deep-learning algorithms and novel spatiotemporal pattern recognition techniques for SQI, which are suitable to be integrated into edge devices. 

#### Reference papers - Sarkar [EMBC'2022]

Cuff-based BP measurement methods provide intermittent measurements, which are unreliable for continuous monitoring over long periods, resulting in discomfort and inconvenience for the patients. Non-invasive cuff-less methods, which use physiological signals like PPG and ECG to estimate BP, can be a viable alternative to traditional cuff-based techniques. Cuff-less BP estimation methods have gained significant attention in recent years and can be divided into two broad categories: (1) estimators use only photoplethysmography (PPG) signals, and (2) estimators use both PPG and electrocardiography (ECG) signals. The first category involves PPG signals (the entire signal or extracted features) to estimate BP, while the second category combines PPG and ECG signals to estimate BP. I want to focus on only PPG signal-based estimation. Each PPG signal has distinct anacrotic and catacrotic phases corresponding to the rising and falling curve of the PPG, which varies between systolic and diastolic BP (SBP and DBP) in each heartbeat interval. The systolic part of the PPG signal is associated with cardiac contraction, while the diastolic part is related to cardiac expansion. Hence, I would like to focus on feature-driven machine learning techniques and lightweight/ few sort deep learning algorithms for PPG-based BP estimation. Down the line, I would like to go toward 'Explainable AI' and  'Physics-informed neural networks' for explaining feature behavior for BP evaluation for three different categories (Normotensive/Hypotensive/Hypertensive). 

#### Reference papers - Kachuee [TBME'2017], Sarkar [Elsevier-CBM'2023]

## Wireless Multimodality System-on-a-chip Design for Biochemical (sweat/urine) and Physiological (ECG, PPG) Signal Acquisition

For multimodality system-on-a-chip design, I would like to focus on both on-chip and off-chip electroanalysis platforms for biomarker detection and drug analysis. The traditional electrochemical analysis (off-chip) depends on a standalone sampling technique followed by lab-based analysis. It is time-consuming, expensive, and complex due to preservation and shipping issues. Despite its drawbacks, it is widely used for biochemical estimations in low and middle-income countries. Therefore, I would like to extend its capabilities by incorporating novel quantitative and semi-quantitative electrochemical analysis techniques.

![plot](/images/wearable.jpg)

#### Biochemical signal acquisition 

The latest scientific developments in electronics, sensing elements, and wireless data transmission permit real-time and uninterrupted estimations of analytes. A compact electrochemical sensing platform (on-chip) is widely used for its high accuracy, quick response, low cost, small form factors, and low power utilization properties. However, most of the existing electrochemical readout interfaces focus on a single modality constrained to a particular sensing pattern, which can’t offer enough details for a comprehensive diagnosis. Recently, multimodal electrochemistry has drawn substantial attention in wearable healthcare systems to detect biochemical parameters. An electrochemical readout circuit consists of multiple components: (a) input waveform generator, (b) potentiostat architecture, (c) AFE architecture, and (d) digitization architecture. Similar to earlier cases, with the rise of big data and digital medicine, next-generation electroanalysis platforms (ex., smart bandages for wound healing progress measurement) will be able to use AI to optimize their design as well as uncover user-personalized health profiles.

#### Reference papers (off-chip) - Yung-Lu [TBCAS'22],

#### Reference Papers (on-chip) - Ainla (ACS'2018), Jie Wu (Nature'2023),  Gao [Nature'23], Gao [Nature'16]

#### Physiological Signal Acquisition

## Power Management IC Design for Edge Devices 

### Essential block design 

Over the past five decades, we have witnessed technological innovations, thanks to the invention of the integrated-circuit (IC) technology, which makes possible the development of various system-on-chips (SoCs) that, with low power consumption, can pack tremendous computing power into very small footprints. Small but smart and low-power, SoCs are thus essential in most battery-powered portable/wearable devices requiring distributed intelligence, such as in wireless sensor nodes for Implantable or wearable devices. Therefore, there is a surge off integrated DC-DC converter having very low output voltage ripple making it suitable for analog applications, which are sensitive to supply noise. Similarly, hybrid converters and multi-output converters are also gaining attention for coping up with the different requirements. I would like to focus on the broad spectrum of converter-controller design, switch cap., charge pump, BGR etc.

![plot](/images/converter.jpg)

#### Reference papers - Dam [TPEL'2021], Bartolini [JESTPE'2023]

### HV driver design for Piezoelectric (CMUT and PMUT) devices 

Ultrasonic (US) nodes are widely used in industrial [non-destructive testing (NDT)] and health (imaging and neuromodulation applications). Conventionally, the transducer is driven by a simple and compact Class-D pulser. However, this is associated with CV2 losses due to the charging and discharging of the transducer capacitance, which do not contribute to the acoustic output.  During my postdoc., I developed a high-voltage pulser to generate ultrasonic waves by driving an array of piezoelectric transducers. The pulser is powered by boosted voltage generated from thermoelectric and photovoltaic sources through energy harvesting by utilizing a cold-start topology-based Boost converter.  It generated two different voltages for pulser supply and digital control. The supply voltage is further utilized for high-voltage supply generation using a multi-stage charge pump. The analog-assisted digitally controlled novel pulser topology is composed of one low-voltage and four high-voltage power switches to optimize the trade-off between conduction losses, the number of generated pulses, recycling energy amount, and gate-drive losses. The pulser operates in four different modes, namely (a) charging, (b) pulsing, (c) freewheeling, and (d) recycling. One single charging cycle is capable of generating 7-8 14 V pulses for 60 pF CMUT and 20 μH inductance.

If you are interested in the above areas and would like to discuss them, please feel free to email me. 

Thanks for visiting my website.

======

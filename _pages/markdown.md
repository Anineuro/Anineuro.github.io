---
permalink: /markdown/
title: "Research Projects"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---



Projects Completed 
=====

## Projects - 1: Building a whole brain model to understand Functional Connectivity from Structural Connectivity. 

This work proposes a phenomenological whole-brain model in which each brain region is represented by a Hopf oscillator, capturing the transition between noisy and oscillatory neural dynamics. The oscillators are coupled through the underlying structural connectivity network, while interactions between regions are modeled using power-coupling, which enables stable phase relationships among oscillators operating at different intrinsic frequencies. This formulation allows the model to capture cross-frequency phase interactions and large-scale synchronization patterns observed in empirical brain signals. By integrating neuroimaging-derived connectivity with nonlinear dynamical systems, the framework provides an efficient and biologically interpretable approach to modeling whole-brain dynamics and emergent functional connectivity. 

The model has-
* Learnable rule for intrinsic frequences of Hopf-oscillator.
* Introduced an unspervised learning rule- Complex Hebbian learning to decipher the phase relationship among oscillators.
* Impact of Structural prunning on functional information of the brain.
* Modification of the oscillator network parameters can restore the functional alteration, providing possible clinical application of the model.

*Figure: Whole-brain network model using coupled Hopf oscillators with power coupling.*
![Hopf Oscillator Whole Brain Model](/images/fmri_model1.png)
*Taken from [https://doi.org/10.1038/s41598-023-43547-3](https://doi.org/10.1038/s41598-023-43547-3)*

### Related Publication
🔗 Bandyopadhyay, A., Ghosh, S., Biswas, D. et al. A phenomenological model of whole brain dynamics using a network of neural oscillators with power-coupling. Sci Rep 13, 16935 (2023). [https://doi.org/10.1038/s41598-023-43547-3](https://doi.org/10.1038/s41598-023-43547-3)

🔗 Bandyopadhyay, A., Ghosh, S., Biswas, D., Surampudi, R.B., Chakravarthy, V.S. (2023). A Phenomenological Deep Oscillatory Neural Network Model to Capture the Whole Brain Dynamics in Terms of BOLD Signal. In: Tanveer, M., Agarwal, S., Ozawa, S., Ekbal, A., Jatowt, A. (eds) Neural Information Processing. ICONIP 2022. Lecture Notes in Computer Science, vol 13624. Springer,[https://doi.org/10.1007/978-3-031-30108-7_14](https://doi.org/10.1007/978-3-031-30108-7_14)

🔗  Bandyopadhyay, A., Ghosh, S., Biswas, D., Surampudi, R.B., Chakravarthy, V.S. (2023).A trainable oscillatory neural network for modelling BOLD signals, SFN, 2022



## Projects - 2: A Mechanistic model to capture simultaneous EEG-fMRI DATA.

This work presents a mechanistic whole-brain modeling framework designed to simultaneously capture electrophysiological and hemodynamic brain signals. The model integrates neural population dynamics with structural connectivity to generate oscillatory activity consistent with EEG recordings, while a hemodynamic forward model maps the neural activity to BOLD signals observed in fMRI. By jointly modeling these two modalities, the framework provides a unified approach to linking fast neuronal oscillations with slower hemodynamic responses, enabling a deeper understanding of the mechanisms underlying multimodal brain signals and large-scale brain dynamics. 

* This is the first kind of model that intends to capture the contrasting spatiotemporal brain rhythm pattern of BOLD and EEG signal.
* The model discards the traditional Haemodynamic response function (HRF) , as a convolotion operator for neuroal signal, as such HRF has significant variability across regions.
* The model introdcues a learning rule to capture the relationship between low-frequency fMRI and high-frequency EEG signals.
* The model shows the importance of Structural connectivity, and the impact of structural pruning on functional information, modularity, and integration-segregation.

*Figure: An integrated neuro-hemodynamic whole-brain model.*
<p align="center">
<img src="/images/EEG_fMRI.png" width="700"><br>
<em>Figure: Integrated neuro-hemodynamic whole-brain model. Taken from https://doi.org/10.1093/cercor/bhag002</em>
</p>


### Related Publication
 
🔗 Anirban Bandyopadhyay, V Srinivasa Chakravarthy, Dipanjan Roy, A mechanistic whole brain model to capture simultaneous EEG-fMRI data, Cerebral Cortex, Volume 36, Issue 1, January 2026, bhag002, 
[https://doi.org/10.1093/cercor/bhag002](https://doi.org/10.1093/cercor/bhag002)

 🔗 Anirban Bandyopadhyay, V Srinivasa Chakravarthy, Dipanjan Roy, An integrated neuro-hemodynamic whole-brain model with a trainable
network of nonlinear oscillators, COSYNE, 2026.  

Projects Ongoing
====

## Projects - 3: A Mechanistic model to understand relationship between brain rhythm and Heart Rhythm.
*Does the brain operate in isolation?* 

Influnce of brain dynamics by autonomic nervous sytem has been in mystery. We think that Dynamical system can provide the adequate tool to decipher the Heart-Brain aand Gut- Brain Axis. 

I am influenced by the work of Catherine Tallon-Baudry. [https://sites.google.com/view/tallon-baudry-lab/home?authuser=0](https://sites.google.com/view/tallon-baudry-lab/home?authuser=0), and his works regarding in this area.  

Understanding interoception with a pure mathematical framework that can explanin the simultaneous recording data from MEG-ECG, EEG-EGG etc.

Such modelling framework can also explain the functionality of Vegus Nerve stimulation, which is gaining popularity recently.



Earlier Projects 
====

## Projects - 4: Mathematical Model of Neurovascular Coupling.

Computational Analysis of NIRS and BOLD Signals from Neurovascular Coupling Using a Three-Neuron Feedforward Inhibition Network

This work presents a computational framework to investigate neurovascular coupling by modeling the relationship between neuronal activity and hemodynamic signals measured through Near-Infrared Spectroscopy (NIRS) and BOLD fMRI. The model incorporates a three-neuron feedforward inhibition network to capture the interplay between excitatory and inhibitory neural populations that drive vascular responses. By integrating neural dynamics with a hemodynamic response model, the study analyzes how different patterns of neuronal activity give rise to observable NIRS and BOLD signals. The framework provides insights into the mechanisms linking neural circuit activity with vascular responses underlying functional brain imaging signals.

*Figure:*
<p align="center">
<img src="/images/Neurovascular_coupling.png" width="700"><br>
<em>Figure: A biolocial pathway of Neurovascular Coupling. Taken from https://doi.org/10.1016/j.jtbi.2020.110297</em>
</p>

### Related Publication

🔗 Bandyopadhyay, A., Sharma, G., & Chowdhury, S. R. (2020). Computational analysis of NIRS and BOLD signal from neurovascular coupling with three neuron-system feedforward inhibition network. Journal of Theoretical Biology, 498, 110297.[https://doi.org/10.1016/j.jtbi.2020.110297](https://doi.org/10.1016/j.jtbi.2020.110297)

🔗 A. Bandyopadhyay, G. Sharma and S. Roy Chowdhury, "A Computational Model to Analyse E/I (Excitation/Inhibition) Dynamics for Neural Network Integrated with Astrocyte," 2020 IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (CIBCB), Via del Mar, Chile, 2020, pp. 1-8, doi: [https://doi.org/10.1109/CIBCB48159.2020.9277698](https://doi.org/10.1109/CIBCB48159.2020.9277698)


## Projects - 5: System level Analysis of Neurovascular Coupling with tDCS-EEG-NIRS.

These preliminary studies investigate the neural and vascular dynamics associated with ischemic stroke and its rehabilitation. Using anodal transcranial direct current stimulation (tDCS), the work explores methods to differentiate between healthy and lesioned hemispheres based on stimulation-induced neurophysiological responses. In parallel, the studies analyze changes in vascular activity and neurovascular coupling during stroke rehabilitation interventions. Together, these investigations provide early insights into how brain stimulation and rehabilitation techniques influence cortical and vascular responses, with potential implications for improving stroke assessment and recovery strategies.

*Figure:*
<p align="center">
<img src="/images/tdcs-EEG.png" width="700"><br>
<em>Figure: Simultaneius recording of EEG and NIRS with application of tDCS. Taken from https://doi.org/10.1016/j.jneumeth.2016.09.008</em>
</p>

### Related Publication

🔗  Sharma, G., Bandopadhyay, A., & Chowdhury, S. R. (2020). P111 a preliminary study on vascular activity with ischemic stroke rehabilitation technique. Clinical Neurophysiology, 131(4), e73-e75.

🔗 Sharma, G., Bandopadhyay, A., & Chowdhury, S. R. (2020). P41 A Preliminary Study to Classify Healthy and Lesioned Hemisphere of Ischemic Stroke Patients with Anodal Transcranial Direct Current Stimulation Technique. Clinical Neurophysiology, 131(4), e199-e200.














***
**Footnotes**

The footnotes in the page will be returned following this line, return to the section on <a href="#footnotes">Markdown Footnotes</a>.


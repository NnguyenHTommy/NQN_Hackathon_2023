# NQN_Hackathon_2023

# Composite Pulses with IonQ to Correct for Errors and using Composite Pulses for Quantum Signal Processing

I-Tung Chen and Tommy Nguyen

### References
[1] https://arxiv.org/pdf/quant-ph/0404064.pdf

[2] https://arxiv.org/abs/2105.02859

[3] https://journals.aps.org/pra/abstract/10.1103/PhysRevA.84.065404

## Introduction 
The IonQ trapped-ion quantum computer is among the few noisy intermediate-scale quantum (NISQ) computers available via cloud services to the general public.
The ability to test algorithms on NISQ devices is an important tool for the advancement of quantum information science.
Beyond the target application space, there is also much opportunity for the study of inherent noise of NISQ devices which serves as a basic plaform for the development of algorithmic-level approaches towards improving the robustness of quantum information devices overall. Not only this, but in our own research labs, we use RF pulses to intialize our states via spin echo or optically detected magnetic resonance (ODMR) experiments with NV centers and quantum dots, so undergoing this research study at this hackathon is a cool way to try and see what the future of our research might hold in terms of actual quantum hardware.

Our goal for this hackathon is an experimental research study on composite pulses to:
1. Look at the noise from IonQ's native gates and see if they can be corrected for with a BB1 Composite Pulse Sequence 
2. Implement and test different composite pulse sequences (BB and NB and maybe PB) for applications in quantum signal processing (QSP) and see what advantages they might have

These goals will be looked at and compared between a cloud based simulator, IonQ's simulators and IonQ's QPU on actual quantum hardware!

## Background: Composite Pulses
The usefulness of a composite pulse - a sequence of pulses - is that it can correct for systematic errors than just using a single pulse due to strategic cancellation. If you've heard of a spin echo experiment in quantum optics, the idea is essentially the same, thereofore, this technique works very well for RF inhomogenieties, frequency offsets, and imperfect pulse lengths.  

## Instructions on Running the Notebooks 
Since this is like a research study and investigation to see if we can correct the problem of IonQ's native gateset errors, please don't run the notebooks (since it would take a long time) and just read through the notebook looking at the results. Start from the top of the notebook and as you work your way down, you'll see that we have added notes and explanations for everything that we've done. In this way, the notebooks can be viewed as a tutorial/paper and we try to help you build understanding and go through the thought process together! No user inputs are required at all in these notebooks. As you get to the end of the notebook, you'll see our solution to the problem at hand and how we arrived there! 

# Functional Imaging of Coherent Radar Signal with Phase Functions [Attached MATLAB Code]

1. Basic Concepts
\tCoherent radar refers to a radar system where the transmit signal, local oscillator voltage, coherent oscillation voltage, and timing pulses are all provided by the same reference signal, maintaining a definite phase relationship between these signals (i.e., phase-coherent). This type of radar system is known as a full-phase-coherent system. Radars, especially those primarily based on main-amplifying systems, generate various phase-coherent signals through frequency synthesizers, even though they may have different frequencies (even significantly so) but maintain phase-coherent characteristics among them. Full-phase-coherent is the foundation for implementing frequency hopping technology (used for anti-aiming interference) and linear frequency modulation technology (pulse compression), capable of generating complex waveforms. Pulse Doppler radar, which is widely applied, is a full-phase-coherent radar.
2. Advantages of Coherent Radar
\tCoherent radar mainly refers to the system's ability to provide a stable initial phase, which can be either in-band full-phase-coherent or locked-local oscillator phase-coherent, and remains continuous throughout the entire receiving signal period. The initial phase of the system can be used to determine the received signal phase, thereby enabling Doppler information extraction.
3. Coherent Pulse Sequence Signal
\tA coherent pulse sequence signal refers to a signal with a fixed phase relationship between adjacent pulse-modulated sine waves. It can be expressed as:
\t
where Acos(2πf0t + φ0) is a reference sine signal, and the pulse width is tp, the cycle is Tr. It is evident that this is an infinitely long pulse sequence with a carrier frequency of f0 and a pulse period of Tr.
Similarly, the fuzzy function of a coherent pulse sequence signal can be obtained as follows:
\tFrom this formula, it can be seen that the velocity fuzzy function is the envelope of the single pulse spectrum multiplied by the product of N pulse sequences. Assuming tp = 1μs, Tr = 10μs, and the number of pulses N is 4. The delay time range is from -10 to +10μs. Based on the formula, the distance fuzzy function graph and velocity fuzzy function graph of the coherent pulse sequence signal can be obtained. As shown in the figure.
The coherent radar has high resolution in distance and velocity, but when the range and velocity distribution exceeds the clear zone, there is ambiguity in both distance and velocity.
\t4 Simulation Results
Parameter settings: Sample rate: 100; Pulse width: 0.2; Pulse repetition period: 1.
Figure 1: Coherent pulse signal
\t  
Figure 2: Three-dimensional figure of phase-coherent pulse signal blur function
Figure 3: Two-dimensional image of the phase-coherent pulse signal's fuzzy function
Figure 4: Phase-shifted zero frequency cut plane of the coherent pulse train
Figure 5: Phase-coherent pulse train zero delay cross section
MATLAB code:
\n  

## Images

![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](01.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](02.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](03.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](04.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](05.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](06.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](07.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](08.jpg)
![[Fuzzy Function] Phase-coherent radar signal fuzzy function [with MATLAB code]](09.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->

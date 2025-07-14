This source file is the Implementation and Testing of an AM Receiver Prototype.
1. Signal Generation
2. Receiver creation by detecting the envelope of the modulated signal through square law

Plots were made to visulize the signals before and after. The orange is the message signal, the blue is the modulated signal, and the green is the reconstructed (recovered) signal.
It has been concluded, by the graphs, that square law is accurate yet imprecise. The green frequency is appropriate, but its amplitude is magnified. Note that Bias offset has not been removed from it, yet. A notch filter is advised in addition.

Notes:
This creative project was to design an AM Receiver Protoype. It is entirely mine, outside of university. Using square law detection, I am proud that I overcame a challenge by conceiving a lowpass filter in frequency, directly, and sucessfully implementing it with all the nuances involved. This, along with a threading excercise, I engineered for my previous employer's pre-interview sample as I learnt the language and another, outside of uni. 

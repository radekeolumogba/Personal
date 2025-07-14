This source file is the Implementation and Testing of an AM Receiver Prototype.
1. Signal Generation
2. Receiver creation by detecting the envelope of the modulated signal through square law

Plots were made to visulize the signals before and after. The orange is the message signal, the blue is the modulated signal, and the green is the reconstructed (recovered) signal.
It has been concluded, by the graphs, that square law is accurate yet imprecise. The green frequency is appropriate, but its amplitude is magnified. Note that Bias offset has not been removed from it, yet. A notch filter is advised in addition.

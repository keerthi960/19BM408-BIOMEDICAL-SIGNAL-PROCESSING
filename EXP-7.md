# RECTANGULAR WINDOW BASED FIR FILTER DESIGN
# AIM :
To design a Low Pass FIR filter using Rectangular Window and analyze its magnitude and phase response using MATLAB.
# Theory :
Rectangular Window
The Rectangular window is defined as:
        w(n)=1≤n≤N
Characteristics:
Narrowest main lobe

Highest side lobes

High ripple (Gibbs phenomenon)

Sharp transition width

It simply truncates the ideal impulse response.

Design Equations
Ideal Low Pass Impulse Response:

h_d (n)=(sin⁡ω_c (n-α))/(π(n-α))

Where:

α=N/2

Actual filter:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Choose filter order N
2.	Choose cutoff frequency ωc
3.	Generate ideal impulse response
4.	Generate rectangular window
5.	Multiply both
6.	Plot frequency response

# MATLAB CODE :
<img width="1079" height="828" alt="image" src="https://github.com/user-attachments/assets/1bfb34b5-7a03-46c2-87c9-41eeb853305e" />

# OUTPUT GRAPH :
<img width="1201" height="1600" alt="image" src="https://github.com/user-attachments/assets/912cb79d-10b1-4269-8e4b-66bb688a6d6a" />
<img width="1201" height="1600" alt="image" src="https://github.com/user-attachments/assets/238b14e2-8d8c-402b-bde3-5ad45050cb78" />


# RESULT :
The FIR filter was designed using Rectangular window.

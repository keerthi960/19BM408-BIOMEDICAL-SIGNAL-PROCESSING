# HANNING WINDOW BASED FIR FILTER DESIGN

# AIM:

To design a Low Pass FIR filter using Hanning (Hann) Window and analyze its response.
# THEORY :

Hanning window is defined as:

w(n)=0.5-0.5cos⁡(2πn/N)

Characteristics:

1)Smooth tapering at ends

2)Reduced spectral leakage

3)Moderate stopband attenuation (~31 dB)

4)Wider main lobe than Hamming

Design Equation:

h(n)=h_d (n)⋅w(n)

# ALGORITHM :
1.	Select N and ωc
2.	Compute ideal response
3.	Generate Hanning window
4.	Multiply and obtain FIR coefficients
5.	Plot response

# MATLAB CODE :
<img width="1080" height="953" alt="image" src="https://github.com/user-attachments/assets/2de72c2a-46dd-48df-9c28-7173d2b97be7" />

# OUTPUT GRAPH :
<img width="1600" height="1201" alt="image" src="https://github.com/user-attachments/assets/1c4309ab-5bc4-4dc6-b05e-773f55c0cc2b" />
<img width="1600" height="1201" alt="image" src="https://github.com/user-attachments/assets/c7f87e5b-ae42-4b91-8388-0102c15e8ee2" />

# RESULT :
The FIR filter was designed using Hanning window.

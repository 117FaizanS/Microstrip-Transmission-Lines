# Microstrip Transmission Line Design and Simulation

Utilized the Rogers RO4003C substrate, which has a characteristic impedance (ℤ₀) of 75 Ω, to design a microstrip transmission line on ADS. The design frequency was set to 4.9 GHz. 

<h3>
What?
</h3>
A complete end-to-end design and simulation of passive RF components using microstrip transmission lines. This project focuses on optimizing impedance matching, minimizing signal reflection, and analyzing performance across key metrics like return loss and insertion loss.

<h3>
How?
</h3>
Used Keysight ADS to design, tune, and simulate:

<ul>
  <li>75 Ω and 50 Ω microstrip lines</li>

  <li>Low-pass filters</li>

  <li>Transmission line matching networks</li>

  <li>Power dividers and couplers</li>
</ul>

Validated performance through EM simulations, S-parameter analysis, and hands-on lab measurements using a microstrip trainer, VCO, and crystal detector.

<h3>
Results
</h3>
<ul>
  <li>Designed a matched 75 Ω microstrip line at 4.9 GHz with return loss > 21 dB and insertion loss ≈ 0.06 dB</li>

  <li>Built and tested a low-pass filter showing correct passband/stopband behavior</li>

  <li>Achieved impedance bandwidths up to 19.55 for TL-matching circuits</li>

  <li>Designed power dividers and verified output symmetry across 2.5–3.6 GHz</li>
</ul>




<p align="center">
<img width="975" height="610" alt="Line Calc ADS function for K Effective and A_DB" src="https://github.com/user-attachments/assets/568a0a14-2250-4828-b80d-58d7958603f9" />
</p>

<p align="center">
<img width="975" height="817" alt="Layout window of ADS for microstrip tl" src="https://github.com/user-attachments/assets/47a9c1ad-0806-4032-b0bf-3d1bd94a9f22" />
</p>

<p align="center">
<img width="975" height="744" alt="S parameters" src="https://github.com/user-attachments/assets/c954215e-7fad-4199-9e2a-0374e58bc024" />
</p>

<p align="center">
<img width="693" height="793" alt="Microstrip Transmission Line EM setup for simulation" src="https://github.com/user-attachments/assets/150d3a20-4cbd-448a-ae5e-3a37b127f16f" />
</p>

<p align="center">
<img width="815" height="697" alt="ADS Port Editor" src="https://github.com/user-attachments/assets/1b9c6afb-13b3-4d44-bb42-2f3613014fe5" />
</p>




<p align="center">
<img width="897" height="1149" alt="Smith Chart for hand calcs" src="https://github.com/user-attachments/assets/d85c26eb-53f4-41ba-8f90-84856fe283c4" />
</p>

<p align="center">
<img width="894" height="1117" alt="Hand Calculations for design of two tuning circuits to match ZL = 100 +j80 Ω to the characteristic impedance of the chosen substrate." src="https://github.com/user-attachments/assets/ab64dff3-3851-4e39-938b-181bab57ab7a" />
</p>

<p align="center">
<img width="673" height="540" alt="Tuning Parameters window ADS" src="https://github.com/user-attachments/assets/e513da58-e75f-4472-a21b-11c2c4327240" />
</p>

<p align="center">
<img width="647" height="496" alt="Solution 1 S Params" src="https://github.com/user-attachments/assets/2acbd1e5-e55a-4b4e-9317-177ec2e3a1d2" />
</p>

<p align="center">Solution 1 S parameters</p>

<p align="center">
<img width="687" height="465" alt="Solution 2 S Params" src="https://github.com/user-attachments/assets/2ee7b4f7-f082-44f7-b572-7233167057d5" />
</p>

<p align="center">Solution 2 S parameters</p>

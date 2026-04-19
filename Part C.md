# Part C: Modelling the Channel Conditions

## Procedure Summary
The generated QPSK signal was passed through a channel model that introduced noise and phase variations using the noise generator and phase shifter modules.

## Block Diagram
<p align="center">
  <img src="https://github.com/user-attachments/assets/1e5caed1-d43a-40d3-9501-78d8ac1c70f6" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 3.1.</strong> Channel modelling block diagram</em>
</p>

## Documentations
<p align="center">
  <img src="https://github.com/user-attachments/assets/95d4e129-6c0a-40a1-a6ad-ab66d09dd757" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 3.2.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0afaceca-15d2-4664-b055-068b72375b40" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 3.3.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2a822458-bd64-4286-9db0-c2be07ec30ab" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 3.4.</strong></em>
</p>

## Questions

### Question 1  
What is the effect of introducing noise into the QPSK signal?  

**Answer:**  
Introducing noise distorts the signal and affects its amplitude and phase, making accurate recovery of the original data more difficult.

### Question 2  
What is the effect of phase variation on the received signal?  

**Answer:**  
Phase variation causes misalignment between the received signal and the local carrier, leading to improper demodulation and increased errors in the recovered data.

## Observation
The signal showed noticeable distortion due to added noise and phase variation. Improper phase adjustment resulted in imperfect alignment during signal recovery.

## Conclusion
Noise and phase distortion significantly degrade signal quality. Accurate phase synchronization is essential to ensure reliable demodulation and data recovery.

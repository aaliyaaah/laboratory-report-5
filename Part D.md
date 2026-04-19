# Part D: Full demodulation of a QPSK signal 

## Procedure Summary
The received QPSK signal was demodulated by multiplying it with locally generated sine and cosine carriers. The outputs were filtered using low-pass filters and then recombined using a Parallel-to-Serial converter.

Due to the faulty Phase Adjust module, exact phase alignment could not be achieved.

## Block Diagram
<p align="center">
  <img src="https://github.com/user-attachments/assets/dfa0961d-2d5e-423e-8a17-0430149dffe5" width="700"/>
</p>

<p align="center">
  <em><strong>Figure 4.1.</strong> QPSK demodulation block diagram</em>
</p>

## Documentations
<p align="center">
  <img src="https://github.com/user-attachments/assets/746b41c6-0edc-4f47-b5b5-78c519636454" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.2.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2e508760-2ef0-471f-9bba-576ae02e826d" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.3.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bcd47658-d89d-4e5d-bb22-f58e25c3d297" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.4.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8cafa953-1c70-4d7a-ac63-7081a5e3cb76" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.5.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/cb46e00b-a854-4387-a842-f177c5e2b434" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.6.</strong></em>
</p>

## Questions
### Question 3  
What aspect of the signal’s shape indicates that the Tunable LPF module’s output doesn’t correspond with neither the odd nor even bits of the Serial-to-Parallel Converter module’s output?  

**Answer:**  
The waveform does not match a clean digital signal and appears as a mixture of both bit streams, indicating overlapping components due to incorrect phase alignment.

### Question 4  
What are these two digital signals that are recovered by the Tunable LPF module?  

**Answer:**  
The recovered signals correspond to the X1 and X2 outputs of the Serial-to-Parallel converter, representing the even and odd bit streams.

### Question 5  
How is it possible for the Tunable LPF module to recover either of these signals and not just one or the other?  

**Answer:**  
By adjusting the phase of the local carrier, the projection of the received signal changes, allowing either the in-phase (I) or quadrature (Q) component to be isolated.

### Question 6  
Do you think it would matter if the PSK₁ arm recovered the X2 data instead of the X1 data and hence, the PSK₂ arm recovered the X1 data instead of the X2 data?  

**Answer:**  
Yes, it matters because swapping the signals would result in incorrect reconstruction of the original data sequence when recombined.

### Question 7  
Why does it matter that the PSK₁ arm recovers the Serial-to-Parallel Converter module’s X1 output and PSK₂ arm recovers the X2 output and not the other way around?  

**Answer:**  
Correct assignment ensures proper bit ordering. If the outputs are swapped, the reconstructed data will have incorrect bit sequencing, leading to errors.

## Conclusion
The demodulation process was successfully demonstrated. However, due to improper phase adjustment, the recovered signals were not perfectly aligned. This highlights the importance of accurate phase synchronization in QPSK demodulation systems.

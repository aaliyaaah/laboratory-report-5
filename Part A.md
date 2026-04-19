# Part A: Verifying the operation of parallel-to-serial then serial-to-parallel conversion 

## Procedure Summary
The Serial-to-Parallel converter was used to split a serial input data stream into two parallel outputs (X1 and X2). The Parallel-to-Serial converter was then used to recombine these signals back into a single serial stream. Oscilloscope observations were used to verify correctness.

## Block Diagram
<p align="center">
  <img src="https://github.com/user-attachments/assets/64f86cd1-7678-4fbd-b92a-686f86ba707f" width="700"/>
</p>

<p align="center">
  <em><strong>Figure 1.</strong> Digital signal modelling showing Serial-to-Parallel and Parallel-to-Serial conversion</em>
</p>

## Documentations
<p align="center">
  <img src="https://github.com/user-attachments/assets/9c552b17-cd37-42b4-a1b3-938cdaa879be" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 2.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d755609-b478-46d8-a7cb-08114e6f85ab" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 3.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2ddc1f03-4154-48ae-a1c1-9b15c13818b1" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 4.</strong></em>
</p> 

<p align="center">
  <img src="https://github.com/user-attachments/assets/84e51a76-5f79-417b-b866-f7ee228608b8" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 5.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/06c889f4-51d6-4bec-9896-3504c4d375f9" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 6.</strong></em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b50799ce-05ea-400d-90d5-719234579e2c" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 7.</strong></em>
</p>

## Observation
The two parallel outputs correspond to alternating bits of the original signal. When recombined, the output matched the original input, except for a slight delay due to clock timing.

## Conclusion
The conversion process was verified successfully. The observed delay between signals is expected due to synchronization and clocking in digital systems.

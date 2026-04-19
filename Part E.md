# Part E: Observation of channel noise on the recovered digital data 

## Procedure Summary
Noise was introduced into the channel at different levels (-20 dB, -6 dB, and 0 dB). The recovered digital signal was observed for errors over time.

## Setup
<p align="center">
  <img src="https://github.com/user-attachments/assets/4be46f85-3c8d-4711-8a40-0848cc8113b8" width="700"/>
</p>

<p align="center">
  <em><strong>Figure 5.1.</strong> Experimental setup for noise observation</em>
</p>

## Documentation Video
https://github.com/user-attachments/assets/e6d02db6-1562-4880-a4c1-2426d88a5a75

<p align="center">
  <em><strong>Video 5.1.</strong> Demonstration of noise effects on recovered digital signal</em>
</p>

## Documentations
<p align="center">
  <img src="https://github.com/user-attachments/assets/876e33ae-3d0b-49ff-a2c7-532df4383870" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 5.2.</strong> Noise level: -20 dB</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9dc76d12-7f02-443b-afc4-7aa6efc2da1e" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 5.3.</strong> Noise level: -6 dB</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/5ae3a795-e267-4795-b2ef-e043ac96099f" width="700"/>
</p>
<p align="center">
  <em><strong>Figure 5.4.</strong> Noise level: 0 dB</em>
</p>

## Questions
### Question 8  
What’s the qualitative error rate of the recovered digital data signal?  

**Answer:**  
At low noise levels (-20 dB), the error rate is very low, with minimal or no observable errors.

### Question 9  
What’s the qualitative error rate of the recovered digital data signal?  

**Answer:**  
At moderate noise levels (-6 dB), occasional errors occur, and the signal shows noticeable degradation.

### Question 10  
What’s the qualitative error rate of the recovered digital data signal?  

**Answer:**  
At high noise levels (0 dB), the error rate is high, with frequent incorrect bits and unstable signal recovery.

### Question 11  
What circuit can be used between the Low-pass filters and the Parallel-to-Serial Converters to reduce the error rate due to noise?  

**Answer:**  
A decision circuit, such as a comparator or threshold detector, can be used to clean the signal and reduce errors caused by noise.

## Conclusion
The results show that increasing channel noise significantly degrades signal quality and increases the error rate. Reliable communication requires proper noise mitigation and signal conditioning before data reconstruction.

# Introduction-to-Optiperformer


## Aim
Download and install OptiPerformer software on your computer and run a sample file.

## Software required
Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.

The system is *instrumented* with:
- An optical power meter at the input to the receiver (or the output of the fiber)  
- A bit error rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from the [optiwave.com](https://optiwave.com) website.
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.
3. Start OptiPerformer.
4. Use either the **File menu** or the **Open File** button to open the Fiber Optic System File.
5. Study the layout, which includes text and boxes identifying the three components of the fiber optic system:
   - **Transmitter section**: binary source (PRBS generator), electrical pulse generator, laser diode, external modulator  
   - **Receiver section**: photodiode, low-pass filter, decision circuit (with BER analyzer)  
   *(These components will be covered in more detail later in the course.)*
6. Run the simulation by pressing the **Start** button.  
   - Progress will be displayed.  
   - The message *“Calculation Finished!”* will appear when complete.
7. Double-click on the optical power meter and BER analyzer.  
   - Move the windows as necessary for clarity.  
   - In the BER window, check the box **Show Eye Diagram**.  
   - The optical power meter shows power at the photodiode input in both watts and dBm.  
   - The BER window displays the eye diagram and quantities including **Max Q Factor** and **Min BER**.
8. The simulation runs **5 iterations**, with fiber length varying from 50 km to 150 km in 5 steps.  
   - The index is displayed in the upper right corner of the layout.  
   - Use the forward/reverse buttons in the lower left to step through iterations.  
   - Note changes in received power and BER display (eye diagram, Q factor, BER) with fiber length.
---
## Tabulation

| S.No | Fibre Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q-Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
|------|-------------------:|-----------------------:|--------------------:|-------------:|--------:|-----------:|------------------------------------:|
| 1    | 99                 | 4.99E-6                | -23.018             | 38.5364      | 0       | 9.73475E-06  | 0.546875 |
| 2    | 55                 | 37.939E-6              | -14.289             | 103.21       | 0       | 7.711737E-05 | 0.546875 |
| 3    | 66                 | 22.438E-6              | -16.489             | 81.9465      | 0       | 4.61318E-06  | 0.546875 |
| 4    | 145                | 6.9647E-9              | -32.679             | 19.5109      | 1.5175E-123 | 1.07821E-06 | 0.59375 |
| 5    | 100                | 4.844E-6               | -23.147             | 45.1978      | 0       | 9.40001E-06  | 0.546875 |
---
## Output Analysis:
<img width="1280" height="668" alt="638937208-3b07bbc8-cc35-457d-b275-589828ae5271" src="https://github.com/user-attachments/assets/81ed0d7e-8fce-4ec6-8567-05c7d32fd8dd" />

## Result
Thus the Optiperformer software was downloaded and installed and successfully executed a sample file.
---



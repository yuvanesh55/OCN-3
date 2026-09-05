# Introduction-to-Optiperformer

## Aim

Download and install OptiPerformer software on your computer and run a sample file.

## Software required

Optiwave introduces OptiPerformer, a free photonic design automation tool which harnesses the full power of OptiSystem and creates specific dynamic design scenarios which can be used by students.

The system is *instrumented* with:

* An optical power meter at the input to the receiver (or the output of the fiber)
* A bit error rate (BER) analyzer

---

## Procedure

1. Download and install OptiPerformer from the [optiwave.com](https://optiwave.com) website.
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.
3. Start OptiPerformer.
4. Use either the **File menu** or the **Open File** button to open the Fiber Optic System File.
5. Study the layout, which includes text and boxes identifying the three components of the fiber optic system:

   * **Transmitter section**: binary source (PRBS generator), electrical pulse generator, laser diode, external modulator
   * **Receiver section**: photodiode, low-pass filter, decision circuit (with BER analyzer)
     *(These components will be covered in more detail later in the course.)*
6. Run the simulation by pressing the **Start** button.

   * Progress will be displayed.
   * The message *“Calculation Finished!”* will appear when complete.
7. Double-click on the optical power meter and BER analyzer.

   * Move the windows as necessary for clarity.
   * In the BER window, check the box **Show Eye Diagram**.
   * The optical power meter shows power at the photodiode input in both watts and dBm.
   * The BER window displays the eye diagram and quantities including **Max Q Factor** and **Min BER**.
8. The simulation runs **5 iterations**, with fiber length varying from 50 km to 150 km in 5 steps.

   * The index is displayed in the upper right corner of the layout.
   * Use the forward/reverse buttons in the lower left to step through iterations.
   * Note changes in received power and BER display (eye diagram, Q factor, BER) with fiber length.

---

## Result

The OptiPerformer software was successfully installed and the sample fiber optic system file was opened and simulated. The simulation was completed successfully for different fiber lengths ranging from **50 km to 150 km**.

The optical power meter displayed the received optical power at the photodiode input, while the BER analyzer displayed the **eye diagram, Max Q Factor, and Min BER**. As the fiber length increased, the received optical power decreased and the quality of the eye diagram deteriorated, resulting in a reduction in Q factor and an increase in BER.

Thus, the basic operation of OptiPerformer and the effect of fiber length on the performance of a fiber optic communication system were successfully studied.

# DeepSOCIAL
**REFERENCE:**

**[1] Mahdi Rezaei, Mohsen Azarmi. [2020] DeepSOCIAL: Social Distancing Monitoring and Infection Risk Assessment in COVID-19 Pandemic, Applied Sciences, MDPI, 10(21), 7514.** 

**Open access paper:** https://www.mdpi.com/2076-3417/10/21/7514    &    https://doi.org/10.3390/app10217514

<img src = "Images/SocialD-Violations.jpg" width=640>

**How to run the code?**:

The code can be executed in Google colab by followoing the guideline below:
1. Copy or Download the following files and paste them in the **darknet** folder of your Google Colab (\contenct\darknet\...)
     
   * Oxford Town Dataset (OxfordTownCentreDataset.avi): https://drive.google.com/file/d/1UMIcffhxGw1aCAyztNWlslHHtayw9Fys/view
   * Optimised DeepSOCIAL weights (DeepSocial.weights): https://drive.google.com/file/d/1t5OgqRn-s6TFZp1X3L5g4zMfaK0OqcEt/view
   * Sort.py
   * DeepSocial.pyc
 
3. Open and run the file YOLO4_DeepSOCIAL.ipynb in Google colab
4. The program should continuerunning and finish the execution be genering three output files in **darknet** folder as follows:
    * ../darknet/DeepSOCIAL DTC.avi
    * ../darknet/DeepSOCIAL Social Distancing.avi
    * ../darknet/DeepSOCIAL Crowd Map.avi

<img src = "Images/Crowd.gif" width=640>


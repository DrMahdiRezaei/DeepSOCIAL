# DeepSOCIAL
**REFERENCE:**

**[1] Mahdi Rezaei, Mohsen Azarmi. [2020] DeepSOCIAL: Social Distancing Monitoring and Infection Risk Assessment in COVID-19 Pandemic, Applied Sciences, MDPI, 10(21), 7514.** 

**Open access paper:** https://www.mdpi.com/2076-3417/10/21/7514    &    https://doi.org/10.3390/app10217514

<img src = "Images/SocialD-Violations.jpg" width=410> <img src = "Images/Crowd.gif" width=410>

## Guideline to Run the Code:
____________________________________
**Option 1: Live Execution on Colab**

The code can be executed in Google colab by followoing the guideline below:
1. Copy or Download the following files and paste them in the **darknet** folder of your Google Colab (\content\darknet\...)
     
   * Oxford Town Dataset (OxfordTownCentreDataset.avi): https://drive.google.com/file/d/1UMIcffhxGw1aCAyztNWlslHHtayw9Fys/view
   * Optimised DeepSOCIAL weights (DeepSocial.weights): https://drive.google.com/file/d/1t5OgqRn-s6TFZp1X3L5g4zMfaK0OqcEt/view
   * Sort.py
   * DeepSocial.pyc
 
3. Open and run the file YOLO4_DeepSOCIAL-1.ipynb in Google colab
4. The program should continue running and finish the execution by genering three output files in **darknet** folder as follows:
    * /content/darknet/DeepSOCIAL DTC.avi
    * /content/darknet/DeepSOCIAL Social Distancing.avi
    * /content/darknet/DeepSOCIAL Crowd Map.avi
    

____________________________________
**Option 2: Joing Google Driver and Colab Execution**

In this method you can keep large falies in your google driver so, you would noy need to upload them in the google colab in every run. 
1. Copy or Download the following files in the root of your Google Drive:
   * Oxford Town Dataset (OxfordTownCentreDataset.avi): https://drive.google.com/file/d/1UMIcffhxGw1aCAyztNWlslHHtayw9Fys/view
   * Optimised DeepSOCIAL weights (DeepSocial.weights): https://drive.google.com/file/d/1t5OgqRn-s6TFZp1X3L5g4zMfaK0OqcEt/view
   * Sort.py
2. Copy or Download the following files in the root of your **darknet** folde (i.e. \content\darkner\..):
   * DeepSocial.pyc

3. Open and run the file YOLO4_DeepSOCIAL-2.ipynb in Google colab
4. Druring the execution the code requires to access the missing files by monthing your Google Drive. Click on the provided link, copy the generated code by Google, and paste it in the next line within the given box. This way two missing files of Oxford town dataset and Optimised wieghts will be accesed via your google driver.
5. The program would keep running and ends by genering 3 output video files in **darknet** folder, with the following names:
    * /content/darknet/DeepSOCIAL DTC.avi
    * /content/darknet/DeepSOCIAL Social Distancing.avi
    * /content/darknet/DeepSOCIAL Crowd Map.avi

# DeepSOCIAL
**REFERENCE:**

**[1] Mahdi Rezaei, Mohsen Azarmi. [2020] DeepSOCIAL: Social Distancing Monitoring and Infection Risk Assessment in COVID-19 Pandemic, Applied Sciences, MDPI, 10(21), 7514.** 

**Open access paper:** https://www.mdpi.com/2076-3417/10/21/7514    &    https://doi.org/10.3390/app10217514

<img src = "Images/SocialD-Violations.jpg" width=640>

**How to run the code?**:

The code can be executed in Google colab by followoing the guideline below:
1. Copy or Download the following files and paste them in the root of your Google Drive:
   * OxfordTownCentreDataset.avi 
   * Sort.py
   * Oxford Town Dataset https://drive.google.com/file/d/1NFGZ5uyGVQ8uex_UUhLK6mlDTr0bx9Jt/view
   * Improved weights for DeepSOCIAL:  https://drive.google.com/file/d/15mIMe-X48O9OJCohgl-22SBnKoTKAxNP/view

2. Copy the follwing file into the **darnet** folder:
   * DeepSocial.pyc
   
3. Open and run the file YOLOv4_DeepSOCIAL.ipynb in Google colab
4. At the middle of running the code, in section "Mounting Google Drive", click on the given link and grant access to month your google drive.
5. Copy the the generated code by Google and paste in the given section.
6. The program should continuerunning and finish the execution be genering three output files in the **darknet** folder of your google colab as follows:
    * ../darknet/DeepSOCIAL DTC.avi
    * ../darknet/DeepSOCIAL Social Distancing.avi
    * ../darknet/DeepSOCIAL Crowd Map.avi

<img src = "Images/Crowd.gif" width=640>


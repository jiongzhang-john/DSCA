# DSCA
****
📢📢📢 **Introducing DSCA: A Public Digital Subtraction Angiography (DSA) Dataset for Cerebral Artery Segmentation**🧠

<div align="justify" style="text-indent: 40px;">The DSCA dataset consists of 58 patients with 224 DSA sequences, including 1792 images from the left and right hemispheres. Among them are 28 male and 30 female patients, with ages ranging from 9 to 81 years and an average age of 49. Notably, the DSA sequences include three different arteries: the internal carotid artery(ICA), external carotid artery (ECA), and vertebral artery (VA). Specifically, there are 126 sequences for ICA, 55 for ECA, and 43 for VA. These sequences were captured by multiple imaging devices including AXION-Artis-160145 and AXION-Artis-160480 (Siemens, Germany), Azurion-559, Azurion-703844, AlluraXper-722012-2542 and AlluraXper-722038-129 (Philips, Netherlands), and Bransist Safire VC17 (Shimadzu, Japan), with sampling rates ranging from 4 to 7 frames per second. Moreover, these sequences exhibit different resolutions (from 512 × 472 to 1432 × 1432). Each DSA sequence, captured in coronal or sagittal views, was stored in a DICOM file, with 108 DSA sequences in the coronal view and 116 in the sagittal view. All sequences retained arterial phase frames while discarding non-contrast, capillary phase, and venous phase frames, guided by the neurosurgeon’s expertise.

🩺**Expert-Guided Annotation:**
All sequences retain arterial phase frames while excluding non-contrast, capillary, and venous phases, following expert neurosurgical guidance. Pixel-wise vessel annotations were performed by skilled clinicians, distinguishing bifurcated vessels (BV) and main artery trunk (MAT)—critical for clinical decision-making in cerebrovascular disease (CVD) treatment.

We hope DSCA contributes to advancing AI-driven vascular analysis and cerebrovascular research.

📖 **Please cite the following reference:**
J. Zhang; Q. Xie; L. Mou; D. Zhang; D. Chen; C. Shan; Y. Zhao; R. Su; M. Guo. [LINK](https://ieeexplore.ieee.org/abstract/document/10884618) DSCA: A Digital Subtraction Angiography Sequence Dataset and Spatio-Temporal Model for Cerebral Artery Segmentation. IEEE Transactions on Medical Imaging, 2025, DOI: 10.1109/TMI.2025.3540886.</div>

🚀**Download** the DSCA dataset [here](https://zenodo.org/records/11255024). 

****

![image](https://github.com/jiongzhang-john/DSCA/blob/main/images/label.png)
****

The table below describes the specific details of the DSCA.

| Artery | Total | Antero-posterior View | Lateral View | Gender | Age | Diseases | Devices | Sample Rate | Resolution |
|:--------:|:----------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| Internal Carotid Artery | 126 | 62 | 64 | M: 72 <br> F: 54| 52.6&plusmn;12.5 | Stenosis, Moyamoya, Aneurysm | Siemens-AXIONM Artis, Philips-Azurion, Philips-AlluraXper, Shimadzu-Bransist Safire | 4, 6, 7 | 512\*472, 512\*512, 742\*960, 844\*844, 952\*952, 1024\*1024, 1432\*1432 | 
| External Carotid Artery | 55  | 26 | 29 | M: 23 <br> F: 32| 42.9&plusmn;10.7 | Stenosis, Moyamoya           | Siemens-AXIONM Artis, Philips-Azurion, Shimadzu-Bransist Safire                     | 6, 7    | 512\*512, 742\*960, 952\*952, 1024\*1024 | 
| Vertebral Artery        | 43  | 17 | 26 | M: 18 <br> F: 25| 47.9&plusmn;10.3 | Stenosis, Moyamoya, Aneurysm | Siemens-AXIONM Artis, Philips-Azurion, Philips-AlluraXper, Shimadzu-Bransist Safire | 6, 7    | 512\*472, 512\*512, 742\*960, 952\*952, 1024\*1024, 1432\*1432 | 

****


![image](https://github.com/jiongzhang-john/DSCA/blob/main/images/link.png)
****

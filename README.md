# Supervised Deep Learning for Head Motion Correction in PET

Tianyi Zeng<sup>1</sup>, Ph.D.; Jiazhen Zhang<sup>1</sup>; Enette Revilla<sup>5</sup>, M.Sc.; Eléonore V. Lieffrig<sup>1</sup>, M.Sc.; Xi Fang<sup>2</sup>, Ph.D.; Yihuan Lu<sup>6</sup>, Ph.D.; John A. Onofrey<sup>1,3,4</sup>, Ph.D.

[Cite this article](#cite-this-article)

## Abstract

Head movement is a major limitation in brain positron emission tomography (PET) imaging, which results in image artifacts and quantification errors. Head motion correction plays a critical role in quantitative image analysis and diagnosis of nervous system disease. However, to date, there is no approach that can track head motion continuously without using an external device. Here, we develop a deep learning-based algorithm to predict rigid motion for brain PET by leveraging existing dynamic PET scans with gold-standard motion measurements from external Polaris Vicra tracking. We propose a novel Deep Learning for Head Motion Correction (DL-HMC) methodology that consists of three components: (i) PET input data encoder layers; (ii) regression layers to estimate the six rigid transformation motion parameters; and (iii) feature-wise transformation (FWT) layers to condition the network to tracer time-activity. The input of DL-HMC is sampled pairs of one-second 3D cloud representations of the PET data and the output is the prediction of six rigid transformation motion parameters. We trained this network in a supervised manner using the Vicra motion tracking information as gold-standard. We quantitatively evaluate DL-HMC by comparing to gold-standard Vicra measurements and qualitatively evaluate the reconstructed images as well as perform region of interest standard uptake value (SUV) measurements. An algorithm ablation study was performed to determine the contributions of each of our DL-HMC design choices to network performance. Our results demonstrate accurate motion prediction performance for brain PET using a data-driven registration approach without external motion tracking hardware

![DL-HMC Network architecture](/resources/figures/Fig1.png "Text to show on mouseover")

## Author information

**Affiliations**

<sup>1</sup>	Department of Radiology and Biomedical Imaging, Yale University, New Haven, CT, USA 

<sup>2</sup>	Department of Psychiatry, Yale University, New Haven, CT, USA

<sup>3</sup>	Department of Urology, Yale University, New Haven, CT, USA

<sup>4</sup>	Department of Biomedical Engineering, Yale University, New Haven, CT, USA

<sup>5</sup> 	University of California, Davis, CA, USA

<sup>6</sup>  United Imaging, Shanghai, China

## Cite this article

Zeng, T. et al. (2022). Supervised Deep Learning for Head Motion Correction in PET. In: Wang, L., Dou, Q., Fletcher, P.T., Speidel, S., Li, S. (eds) Medical Image Computing and Computer Assisted Intervention – MICCAI 2022. MICCAI 2022. Lecture Notes in Computer Science, vol 13434. Springer, Cham.

### DOI
[https://doi.org/10.1007/978-3-031-16440-8_19
](https://doi.org/10.1007/978-3-031-16440-8_19)



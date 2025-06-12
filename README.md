# Challenges in Segmenting Lesions in Breast Ultrasound Images

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This repository contains poster and code for the project on the challenges of segmenting lesions in breast ultrasound images using deep learning.

## Overview

Breast ultrasound imaging is broadly applied for the early detection and diagnosis of breast lesions. As a result, accurate automated detection and segmentation are essential to aid radiologists and reduce the risk of misdiagnosis. However, despite its diagnostic value, ultrasound imaging presents challenges such as speckle noise and indistinct lesion boundaries which make accurate segmentation difficult. We evaluate four state-of-the-art deep learning models on two public datasets for breast lesion segmentation.

## Models Evaluated

- UNet [^1]
- FPN [^2]
- DeepLabv3+ [^3]
- UNet++ [^4]

Note: ResNet18 [^5] is used as encoder with ImageNet [^6] pretrained weights

## Repo Structure

- `/code`: Code using Python notebook
- `/poster`: Poster in PDF format

## Datasets

- BUSIS [^7]
- UDIAT [^8]

## Authors

- **Ms. Aamal Alghamdi**  
  *PhD Student, Department of Computer and Information Sciences, University of Strathclyde*
  Email: [aamal.alghamdi@strath.ac.uk](mailto:aamal.alghamdi@strath.ac.uk)
  
- **Dr. Mohamed Elawady** — [Supervisor](https://pureportal.strath.ac.uk/en/persons/mohamed-elawady)  
  *Teaching Fellow, Department of Computer and Information Sciences, University of Strathclyde*

- **Dr. Andrew Abel** — [Co-supervisor](https://pureportal.strath.ac.uk/en/persons/andrew-abel)  
  *Lecturer B, Department of Computer and Information Sciences, University of Strathclyde*

## Venues

- [SINAPSE annual meeting](https://www.sinapse.ac.uk/events/sinapse-asm-2025-aberdeen/): 9th, 10th June 2025
- [SICSA PhD Conference](https://www.sicsa.ac.uk/event/sicsa-phd-conference-2025/): 25th, 26th June 2025
- [BMVA Summer School](https://cvss.bmva.org/): 7th-11th July 2025

## Citation

```bibtex
@misc{awady2025buschallenges,
  author       = {Alghamdi, Aamal and Elawady, Mohamed and Abel, Andrew},
  title        = {Challenges in Segmenting Lesions in Breast Ultrasound Images},
  year         = {2025},
  howpublished = {\url{https://github.com/mawady/BUS-Challenges}},
  note         = {Accessed: xxxx-xx-xx}
}
```

---

[^1]: Ronneberger, Olaf, Philipp Fischer, and Thomas Brox. "U-net: Convolutional networks for biomedical image segmentation." Medical image computing and computer-assisted intervention–MICCAI 2015: 18th international conference, Munich, Germany, October 5-9, 2015, proceedings, part III 18. Springer international publishing, 2015.

[^2]: Kirillov, Alexander, et al. "A unified architecture for instance and semantic segmentation." Computer Vision and Pattern Recognition Conference. CVPR, 2017.

[^3]: Chen, Liang-Chieh, et al. "Encoder-decoder with atrous separable convolution for semantic image segmentation." Proceedings of the European conference on computer vision (ECCV). 2018.

[^4]: Zhou, Zongwei, et al. "Unet++: A nested u-net architecture for medical image segmentation." Deep learning in medical image analysis and multimodal learning for clinical decision support: 4th international workshop, DLMIA 2018, and 8th international workshop, ML-CDS 2018, held in conjunction with MICCAI 2018, Granada, Spain, September 20, 2018, proceedings 4. Springer International Publishing, 2018.

[^5]: He, Kaiming, et al. "Deep residual learning for image recognition." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.

[^6]: Deng, Jia, et al. "Imagenet: A large-scale hierarchical image database." 2009 IEEE conference on computer vision and pattern recognition. Ieee, 2009.

[^7]: Y. Zhang, M. Xian, H. D. Cheng, B. Shareef, J. Ding, F. Xu, K. Huang, B. Zhang, C. Ning, Y. Wang, "BUSIS: A Benchmark for Breast Ultrasound Image Segmentation," Healthcare., vol. 10, no. 4, pp. 729, Apr, 2022.

[^8]: Pons, G., Mart ́ı, J., Mart ́ı, R., Ganau, S., Vilanova, J.C., Noble, J.A.: Evaluating lesion segmentation on breast sonography as related to lesion type. Journal of Ultrasound in Medicine 32(9) (2013) 1659–1670

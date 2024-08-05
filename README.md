# MT-CNN
Welcome to the Repository! This repository is dedicated to providing access to datasets and codes related to the paper titled **Automatic assessment of post-earthquake buildings based on multi-task deep learning with auxiliary tasks**
## Abstract
Post-earthquake building condition assessment is crucial for subsequent rescue and remediation and can be automated by emerging computer vision and deep learning technologies. This study is based on an endeavour for the 2nd International Competition of Structural Health 
Monitoring (IC-SHM 2021). The task package includes five image segmentation objectives - defects (crack/spall/rebar exposure), structural component, and damage state. The structural component and damage state tasks are identified as the priority that can form actionable 
decisions. A multi-task Convolutional Neural Network (CNN) is proposed to conduct the two major tasks simultaneously. The rest 3 sub-tasks (spall/crack/rebar exposure) were incorporated as auxiliary tasks. By synchronously learning defect information (spall/crack/rebar 
exposure), the multi-task CNN model outperforms the counterpart single-task models in recognizing structural components and estimating damage states. Particularly, the pixel-level damage state estimation witnesses a mIoU (mean intersection over union) improvement from 
0.5855 to 0.6374. For the defect detection tasks, rebar exposure is omitted due to the extremely biased sample distribution. The segmentations of crack and spall are automated by single-task U-Net but with extra efforts to resample the provided data. 
The segmentation of small objects (spall and crack) benefits from the resampling method, with a substantial IoU increment of nearly 10%.
![image](https://github.com/user-attachments/assets/0c541a13-4cc3-4c13-9cde-028467396d8d)
![image](https://github.com/user-attachments/assets/0d32fd46-2720-496f-accc-a6d94b7c62b5)
## Cite
If you find the repository helpful, please cite our publication: 
Li, Z., Zhu, H., Huang, M., Ji, P., Huang, H. and Zhang, Q., 2023. Automatic assessment of post-earthquake buildings based on multi-task deep learning with auxiliary tasks. Smart Structures and Systems, 31(4), pp.383-392. DOI: https://doi.org/10.12989/sss.2023.31.4.383.

# HyperTea
The Pytorch implementation of the paper HyperTea: A Hypergraph-based Temporal Enhancement and Alignment Network for Moving Infrared Small Target Detection.
<img width="1958" height="678" alt="image" src="https://github.com/user-attachments/assets/f4081780-c4df-4249-ae78-24d5cfc77fec" />

# Prerequisite
python==3.10.14  
pytorch==2.0.0  
torchvision==0.15.1  
numpy==2.1.1  
With CUDA 12.4, and 1x NVIDIA 4090D.

# Results
| Method | Dataset | mAP50 (%) | Precision (%) | Recall (%) | F1 (%) |
|--------|---------|-----------|---------------|------------|--------|
| HyperTea | DAUB    | 95.59     | 98.14         | 98.31      | 98.23  |
| HyperTea | IRDST   | 76.42     | 91.18         | 84.33      | 87.62  |
SOTA weights can be downloaded here(通过网盘分享的文件：weights
链接: https://pan.baidu.com/s/18BezWbztMub-GcMmIm1ZuQ?pwd=2025 提取码: 2025 
--来自百度网盘超级会员v8的分享).
### PR curves on DAUB and IRDST datasets.
<img width="521" height="798" alt="image" src="https://github.com/user-attachments/assets/679e921f-b620-49eb-83a3-641c746a68ae" />

# Contact
If any questions, kindly contact with Zhaoyuan Qi via e-mail: qizhaoyuan24@mails.ucas.ac.cn.


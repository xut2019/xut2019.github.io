---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**Xu Tao (徐 涛 ) is associate professor with the [School of Information Science and Engineering](https://ise.ujn.edu.cn/), [University of Jinan](https://www.ujn.edu.cn/)(济南大学). He received the M.S. degree in computer science from China University of Petroleum(中国石油大学), and the Ph.D. degree in computer science from [IRIP Lab](https://irip.buaa.edu.cn/), Beihang University(北京航空航天大学).**

His research interest includes **remote sensing image analysis**, **deep learning** and **human-computer interaction**. Most recently, he is interested in the following topics:
- **Detection, Segmentation and Change Detection in Remote Sensing**.
- **Multi-Modal based  Human-Robot Interaction**.
- **WebGIS System Development**.


# 🔥 News
- **2024.8.20**: &nbsp;Our paper, "MAMI-CD: Multi-stage Attention Network for Change Detection with Mixed Feature Interaction" has been published by [**IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing**](https://ieeexplore.ieee.org/document/10640231).
- **2023.11.25**: &nbsp;Our paper, "Improving Object Detection from Remote Sensing Images via Self-supervised Adaptive Fusion Networks" has been published by [**IEEE Geoscience and Remote Sensing Letters**](https://ieeexplore.ieee.org/document/10373956).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE JSTARS </div><img src='images/mami-cd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAMI-CD: Multi-stage Attention Network for Change Detection with Mixed Feature Interaction](https://ieeexplore.ieee.org/document/10640231)

Mingzhi Han, **Tao Xu**, Qingjie Liu, Xiaohui Yang, Feng Zhang, and Yongguo Shi
- We introduce the MAM, which extracts spatial information of targets from feature maps across multiple encoding stages and transmits it to the decoding stage, thereby enhancing spatial correlations between targets and the saliency of changed targets in RS images.
- We introduce the MIM, which employs channel-wise feature fusion processing to enhance spatial target correlation between the images. This approach replaces the traditional direct connection operation, effectively maintaining spatial connections between targets in bitemporal RS images.
- Comprehensive experiments were conducted on public datasets, including LEVIR-CD, S2Looking, and CDD. The achieved SOTA performance on most metrics demonstrates the effectiveness of our method for CD tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE GRSLetter</div><img src='images/2023grsl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Object Detection from Remote Sensing Images via Self-supervised Adaptive Fusion Networks](https://ieeexplore.ieee.org/document/10373956)

Qiu Lu, **Tao Xu**, Jiwen Dong, Qingjie Liu, Xiaohui Yang
- A self-supervised adaptive fusion network (SSAFN) is designed to enhance the feature representation of objects by suppressing complex background.
- To validate the generic capability of SSAFN, we integrated SSAFN into multiple detection networks and observe consistent improvements.
- We have conducted comparison experiments with other mainstream detection methods on SSDD, SAR-Ship Dataset and 5M-building dataset respectively, and the
experimental results have demonstrated the effectiveness of our method.
</div>
</div>

- **2024**
1. MAMI-CD: Multi-stage Attention Network for Change Detection with Mixed Feature Interaction[J]. **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing**,2024. (Early Access  SCI)
2. Q. Lu, **T. Xu**, J. Dong, Q. Liu and X. Yang. Improving Object Detection from Remote Sensing Images via Self-supervised Adaptive Fusion Networks[J]. **IEEE Geoscience and Remote Sensing Letters**, 2024, 21: 1-5. (SCI)

- **2023**
1. Huang Z, Liu Q, Zhou H, et al. Building Detection From Panchromatic and Multispectral Images With Dual-Stream Asymmetric Fusion Networks[J]. **IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing(JSTARS)**, 2023, 16: 3364-3377. (SCI)
2. Yu K, Zhang Y, Hou B, et al. Large Window Attention Based Transformer Network for Change Detection of Remote Sensing Images[C]. **International Conference on Image and Graphics(ICIG)**. Cham: Springer Nature Switzerland, 2023: 308-319. (EI)
3. Han M, Liu L, **Xu T**, et al. Non-Agricultural Change Detection in Multi-Scale and Multi-Season Remote Sensing Images[C]. 2023 16th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI). IEEE, 2023: 1-5. (EI)
4. Zang J, Zhang Y, **Xu T**, et al. Introduction and Analysis of M-TSLand: A Multi-Temporal and Multi-Scale Remote Sensing Farmland Dataset[C]. Proceedings of the 2023 6th International Conference on Big Data Technologies(ICBDT). 2023: 151-157. (EI)
5. Xiao C, Liu L, Xie G, et al. A large dataset with CNN-based segmentation analysis for land cover from large river basins[C]. 2023 16th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI). IEEE, 2023: 1-5. (EI)
6. Zhang H, Bi M, **Xu T**, et al. A multi-scale dataset with comprehensive analysis for building detection from remote sensing images[C]. 2023 16th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI). IEEE, 2023: 1-5. (EI)
7. Li M, **Xu T**, Chen X, et al. Design of 120GHZ FMCW Radar Liquid Level Measurement System[C]. 2023 5th International Conference on Intelligent Control, Measurement and Signal Processing (ICMSP). IEEE, 2023: 755-758. (EI)
8. Li M, **Xu T**, Chen X, et al. Research on algorithm of FMCW radar level gauge[C]. 2023 5th International Conference on Electronics and Communication, Network and Computer Technology (ECNCT). IEEE, 2023: 270-274. (EI)
9. SE-UNet: Channel Attention based UNet for Water body Segmentation from SAR Image[C]
10. Variable Scale Gesture Recognition: A Dataset and Comprehensive Analysis[C]

- **2022**
1. Li W, **Xu T**, Wang Y, et al. UJN-SAR: A Large Dataset with Experimental Analysis for Water Body Segmentation from SAR Images[C]. International Conference on Image, Vision and Intelligent Systems. Singapore: Springer Nature Singapore, 2022: 227-238. (EI)
2. Yu K,**Xu T**, Hou B, et al. UJN-CD: A Large Scale Date set for Change Detection with Comprehensive Analysis Based on Deep Learning[C]. International Conference on Image, Vision and Intelligent Systems. Singapore: Springer Nature Singapore, 2022: 432-441.
3. Lu Q, Dong W J, Dong Y, et al. EMN: An Edge Mask based Network for Building Detection from Remote Sensing Images[C]. Proceedings of the 5th International Conference on Big Data Technologies. 2022: 242-247. (EI)
4. Li Y, Han S Y, **Xu T**, et al. Cascade Detector Based on Multi-scale Features for Small Objects in Various Backgrounds of Remote Sensing[C]. International Conference on Image, Vision and Intelligent Systems. Singapore: Springer Nature Singapore, 2022: 310-319. (EI)
5. Shen Y, **Xu T**, Liu L Y, et al. Laplacian Filter Embedding based Attention Network for Land Segmentation from Remote Sensing Images[C]. Proceedings of the 5th International Conference on Big Data Technologies. 2022: 284-290. (EI)

- **2021**
1. Yin H, Zhang C, Han Y, et al. Improved semantic segmentation method using edge features for winter wheat spatial distribution extraction from Gaofen-2 images[J]. **Journal of Applied Remote Sensing**, 2021, 15(2): 028501-028501.(SCI)
2. Qiu X, Feng Z, **Xu T**, et al. Research on Intention Flexible Map Algorithm for Elderly Escort Robot[J]. **Scientific Programming**, 2021, 2021: 1-14.(SCI)
3. Li Y, Han S Y, Shen Y, et al. UJN-traffic: a benchmark dataset for performance evaluation of traffic element classification[C]. Intelligent Equipment, Robots, and Vehicles: 7th International Conference on Life System Modeling and Simulation, LSMS 2021 and 7th International Conference on Intelligent Computing for Sustainable Energy and Environment, ICSEE 2021, Hangzhou, China, October 22–24, 2021, Proceedings, Part III 7. Springer Singapore, 2021: 184-193.(EI)
4. Shen Y, Wang Y, Yang S, et al. UJN-Land: A Large-Scale High-Resolution Parcel of Land of Multi-temporal Dataset with CNN Based Semantic Segmentation Analysis[C]. Intelligent Equipment, Robots, and Vehicles: 7th International Conference on Life System Modeling and Simulation, LSMS 2021 and 7th International Conference on Intelligent Computing for Sustainable Energy and Environment, ICSEE 2021, Hangzhou, China, October 22–24, 2021, Proceedings, Part III 7. Springer Singapore, 2021: 204-213. (EI)
5. Yu P, Yang S, Shen Y, et al. Design and Implementation of Security Labeling System Based on Neighborhood Rough Set[C]//Intelligent Equipment, Robots, and Vehicles: 7th International Conference on Life System Modeling and Simulation, LSMS 2021 and 7th International Conference on Intelligent Computing for Sustainable Energy and Environment, ICSEE 2021, Hangzhou, China, October 22–24, 2021, Proceedings, Part III 7. Springer Singapore, 2021: 462-471. (EI)

- **2020**
1. Lu Z, Liu K, Zhang Y, et al. Building Detection via Complementary Convolutional Features of Remote Sensing Images[C]. **Pattern Recognition and Computer Vision: Third Chinese Conference(PRCV)**, Nanjing, China, October 16–18, 2020, Proceedings, Part I 3. Springer International Publishing, 2020: 638-647. (EI，CCF-C)
2. Wang W, Zhang X, Dong L, et al. Network attack detection based on domain attack behavior analysis[C]//2020 13th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI). IEEE, 2020: 962-965.
3. Chen J, Cao A, Zhang Y, et al. Tumor-assisted diagnosis based on U-Net network[C]//2020 13th International Congress on Image and Signal Processing, BioMedical Engineering and Informatics (CISP-BMEI). IEEE, 2020: 739-742.
- **Other papers**
1. Lu Z, **Xu T**, Liu K, et al. 5M-Building: A large-scale high-resolution building dataset with CNN based detection analysis[C]. **2019 IEEE 31st International Conference on Tools with Artificial Intelligence (ICTAI)**. IEEE, 2019: 1385-1389. (EI，CCF-C)
2. Yu P, **Xu T**, Zheng B, et al. Research and implementation of multiscale dynamic terrain[C]. 2018 International Conference on Security, Pattern Analysis, and Cybernetics (SPAC). IEEE, 2018: 217-222.(**Best Paper Award**)
3. Feng Z, Yang B, **Xu T**, et al. FM: Flexible maping from one gesture to multiple semantics[J]. **Information Sciences**, 2018, 467: 654-669.(SCI)
4. Han R, Feng Z, **Xu T**, et al. Multi-sensors based 3D gesture recognition and interaction in virtual block game[C]. **2017 International Conference on Virtual Reality and Visualization (ICVRV)**. IEEE, 2017: 391-392. (EI，CCF-C)
5. **Xu T**, Feng Z, Dong L, et al. 2D Human Parsing with Deep Skin Model and Part-Based Model Inference[C]. Intelligent Computing Theories and Application: 13th International Conference, ICIC 2017, Liverpool, UK, August 7-10, 2017, Proceedings, Part II 13. Springer International Publishing, 2017: 776-787. (EI，CCF-C)
6. **Xu T**, Zhang Z, Wang Y. Patch-wise skin segmentation of human body parts via deep neural networks[J]. **Journal of Electronic Imaging**, 2015, 24(4): 043009-043009.(SCI)
7. Feng Z, **Xu T**, Lv N, et al. Behavioral Model Tracking of Hand Gestures[C]. **2015 International Conference on Virtual Reality and Visualization (ICVRV)**. IEEE, 2015: 101-108.
8. **Xu T**, Wang Y, Zhang Z. Pixel‐wise skin colour detection based on flexible neural tree[J]. **IET Image Processing**, 2013, 7(8): 751-761.(SCI)
9. **Xu T**, Wang Y, Zhang Z. Towards independent color space selection for human skin detection[C]. Advances in Multimedia Information Processing–PCM 2012: 13th Pacific-Rim Conference on Multimedia, Singapore, December 4-6, 2012. Proceedings 13. Springer Berlin Heidelberg, 2012: 337-346. (EI)
10. **Xu T**, Wang C, Wang Y, et al. Saliency model based head pose estimation by sparse optical flow[C]. The First Asian Conference on Pattern Recognition(ACPR). IEEE, 2011: 575-579. (EI)

# 📖 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/rs2.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

  **Intelligent interpretation of remote sensing images**：Remote sensing images have the advantages of wide observation range, high observation frequency, and objective and realistic observation data. Obtaining useful information from remote sensing images has become an effective means for current social development and governance. The intelligent interpretation of remote sensing images mainly includes research topics such as object detection, object segmentation, change detection, and object and scene classification. The research group has developed research directions such as building detection, water body segmentation, land use classification, and change detection based on actual needs. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/robot.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

**Human-computer interaction**：Human computer interaction is one of the key technologies for robots to assist human life and work. The laboratory has advanced equipment such as mobile robots and robotic arms, and conducts multimodal human-computer interaction research for elderly care and virtual experiments, with a focus on gesture recognition, multimodal fusion, and understanding of interaction intentions. 
</div>
</div>

# 🎖 Members
- **Faculty** : Feng Zhiquan(PI), Xu Tao, Yang Xiaohui, Si Tongzhen, Guo Qingbei, Zhang Feng. 
- **Master Candidates**:
  1. Xiao Chenxin, Zhang Han, Han Mingzhi, LiZhaoyu, Zang Junyuan;
  2. Zhu Guangze, Sun Jiahui, Zhai Yijing;
  3. Tian Qizong, Zhang Hao, Zhiyu Guo.

# 💬 Invited Talks
- *2022.11.23*, Research on the Application and Intelligent Interpretation Technology of High Resolution Satellites in Shandong Province, Mount Taishan Meteorological Forum.

# 💻 Datasets

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/hand.png' alt="sym" width="70%"></div></div>
<div class='paper-box-text' markdown="1">

**UJN-3M-HANDS**：Large-scale dataset is necessary for training of deep neural network-based hand gesture classification models. According to the requirements of human-interaction in virtual reality-oriented teaching environment, a large-scale depth-based hand gesture dataset was proposed. The dataset, named UJN-3M-HANDS, contained more than 3 million depth gesture samples. There are 17 static gestures and 34 dynamic gestures in UJN-3M-HANDS. Some static gesture samples were demonstrated in Figure. Compared with other data sets, UJN-3M-HANDS proposed is designed for specific teaching application scenarios, and the categories of gestures are consistent with those used in experimental teaching. In the stage of gesture collection, the distance between the camera and the collector is set to more than 2 meters. The advantage of UJN-3M-HANDS is that the gesture samples were acquired from 2000 individuals, while there are many replication samples in other datasets.
</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/5m.jpg' alt="sym" width="65%"></div></div>
<div class='paper-box-text' markdown="1">

**5M-Buildings**：Buildings dataset is constructed via manually annotation based on GaoFen satellite, which images are with high spatial resolution. In our work, the building categories are divided into house buildings, factory buildings and other buildings, etc. Compared with existing annotation methods, the proposed annotation process is more efficient and accurate, because we annotate panchromatic images with high spatial resolution, and then fuse panchromatic and multispectral images. The traditional annotation process is divided into two parallel sub-processes, i.e., fast panchromatic image annotation and multi-spectral image fusion. Buildings now consists of three distinct categories building categories, i.e., house buildings, factory buildings and other buildings. The number of categories continues to increase. The dataset contains more than 10,000 images. The spatial resolution of sample images is less than 1 meter, which covering various types of buildings on the mainland. Images under various conditions of different weather, seasons and imaging conditions are selected for buildings annotation. Sample images of Buildings have the characteristics of large-scale, multi-scale, intra-class diversity and inter-class similarity in terms of building. Although existing remote sensing datasets contains more scenarios, the number of samples cannot meet the needs of model training for CNN based target detection or classification. To the best of our knowledge, the Buildings dataset proposed in this paper is the largest high-resolution remote sensing dataset for building detection. 
</div>
</div>

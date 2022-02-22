---
title: "CDNet: A Real-Time and Robust Crosswalk Detection Network on Jetson Nano Based on YOLOv5"
collection: publications
permalink: /publication/2020-CDNet
excerpt: 'This is an improved neural network for crosswalk detection, including datasets.'
date: 2022-2-22
venue: 'Neural Computing and Applications'
paperurl: 'http://doi.org/10.1007/s00521-022-07007-9'
citation: 'Zheng-De Zhang, Meng-Lu Tan, Zhi-Cai Lan, Hai-Chun Liu, Ling Pei and Wen-Xian Yu. CDNet: A Real-Time and Robust Crosswalk Detection Network on Jetson Nano Based on YOLOv5 [J]. <j>Neural Computing and Applications</i>, 2020, 1(1):1-1.'
---

# Info / 信息
YEAR&ensp;&ensp;&ensp;&ensp;&ensp;&thinsp;&thinsp;:
2022
<br>AUTHORS&ensp;&ensp;: 
**Zheng-De Zhang**, Meng-Lu Tan, Zhi-Cai Lan, Hai-Chun Liu, Ling Pei and Wen-Xian Yu
<br>TITLE&ensp;&ensp;&ensp;&ensp;&ensp;&thinsp;: 
CDNet: A Real-Time and Robust Crosswalk Detection Network on Jetson Nano Based on YOLOv
<br>中文标题&ensp;&ensp;&ensp;: 
CDNet: 一个基于YOLOv5的在Jetson Nano上实时、鲁棒的斑马线检测网络
<br>JOURNAL&ensp;&ensp;: 
Neural Computing and Applications
<br>DOI&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&thinsp;&thinsp;: 
[10.1007/s00521-022-07007-9](https://doi.org/10.1007/s00521-022-07007-9)
<br>CODE&ensp;&ensp;&ensp;&ensp;&ensp;: 
[https://github.com/zhangzhengde0225/CDNet](https://github.com/zhangzhengde0225/CDNet)
<br>DOWNLOAD: 
[CDNet](https://doi.org/10.1007/s00521-022-07007-9) or [View_fulltxt_online](https://rdcu.be/cHuc8)

# Abstract / 摘要
Realizing real-time and robust crosswalk (zebra crossing) detection in complex scenarios and under limited computing power is one of the important difficulties of current intelligent traffic management systems (ITMS). Limited edge computing capabilities and real complex scenarios such as in cloudy, sunny, rainy, foggy and at night simultaneously challenge this task. In this study, the crosswalk detection network (CDNet) based on YOLOv5 is proposed to achieve fast and accurate crosswalk detection under the vision of the vehicle-mounted camera, and real-time detection is implemented on Jetson nano device. The powerful convolution neural network feature extractor is used to handle complex environments, the squeeze-and-excitation (SE) attention mechanism module is embedded into the network, the negative samples training (NST) method is used to improve the accuracy, the region of interest (ROI) algorithm is utilized to further improve the detection speed, and a novel slide receptive field short-term vector memory (SSVM) algorithm is proposed to improve vehicle-crossing behavior detection accuracy, the synthetic fog augmentation algorithm is used to allow the model adaptable to foggy scenario. Finally, with a detection speed of 33.1 FPS on Jetson nano, we obtained an average F1 score of 94.83% in the above complex scenarios. For better weather condition such as sunny and cloudy days, the F1 score exceeds 98%. This work provides a reference for the specific application of artificial neural network algorithm optimization methods on edge computing devices. The datasets, tutorials and source codes are available on GitHub.



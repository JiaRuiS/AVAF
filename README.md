# Automatic video analysis framework for exposure region recognition in X-ray imaging automation
We propose an automatic video analysis framework (AVAF) for exposure region recognition in X-ray examination. In this work, we have constructed a large dataset including body keypoint and body Bbox annotation images. Currently, we are further expanding the annotation categories of the basic version dataset so that it can be close to the real clinical scenario in the X-Ray imaging process.
# Dataset
The following are some samples in basic version dataset.
## Annotation categories
<img src="https://github.com/JiaRuiS/AVAF/blob/main/Annotation/combination.PNG" width="532" height="312" alt="微信小程序"/><br/>
## Annotion Demo
<img src="https://github.com/JiaRuiS/AVAF/blob/main/Data/demo.PNG" width="600" height="620" alt="微信小程序"/><br/>


# Results
In the work, we propose a new solution to recognize the exposure region better for X-ray imaging protocols and conduct extensive experiments to test the performance of the proposed method. We present qualitative visualization results of Body Structure Detection and video detection. Among them, Body Structure Detection gives the performance evaluation of the two body detection models, and video detection is used to evaluate the overall performance of the proposed framework. Finally, we also hope to help optimize the workflow in conventional X-ray imaging and facilitate decreasing the radiographer's workload.
## Result of Body Structure Detection
<img src="https://github.com/JiaRuiS/AVAF/blob/main/Results/frame.PNG" width="900" height="373" alt="微信小程序"/><br/>
## Result of video detection
![image](./Results/standing.PNG)
![image](./Results/lying.PNG)

# Citation
If you find our approaches useful in your research, please consider citing:
```
@article{sun2022automatic,
  title={Automatic video analysis framework for exposure region recognition in X-ray imaging automation},
  author={Sun, Jiarui and Wu, Zhan and Yu, Zechen and Chen, Huanji and Du, Changping and Xu, Liang and Zhong, Jian and Feng, Juan and Coatrieux, Gouenou and Coatrieux, Jean-Louis and others},
  journal={IEEE Journal of Biomedical and Health Informatics},
  volume={26},
  number={9},
  pages={4359--4370},
  year={2022},
  publisher={IEEE}
}
```

# Estimating-lower-extremity-joint-angles-during-gait-using-reduced-number-of-sensors-count-
Estimating lower extremity joint angles during gait using reduced number of sensors count via deep learning

In this paper, we proposed a deep learning model Kinematics-Net to predict hip, knee, and ankle joint angles using foot-mounted IMU sensors. In the "ICDIP_Kinematics_Net.ipynb" notebook, we provided the models used in the paper. The provided dataset in google drive is slightly different than the one implemented in the paper. It has additional trials and we did not segment any of the gait cycles. We rather take all the walking strategies including turning.

## Download the files from the following google drive link

A detailed protocol of the data collection can be found in Moniruzzaman et. al. {\cite{moniruzzaman2021wearable}}.


https://drive.google.com/drive/folders/1nNotE2vVi0zEVXPmYzSC3NVl2aLD63Ob?usp=sharing


### Data Collection Procedures
![image](https://github.com/Sanzid-Priam/Estimating-lower-extremity-joint-angles-during-gait-using-reduced-number-of-sensors-count-/assets/81487150/39802365-3635-4473-a588-87e8ae996c42)

### Kinematics-Net
![image](https://github.com/Sanzid-Priam/Estimating-lower-extremity-joint-angles-during-gait-using-reduced-number-of-sensors-count-/assets/81487150/d472c3bd-6abb-4e48-8e48-c0d29fb48526)


### Fundamental Units
![image](https://github.com/Sanzid-Priam/Estimating-lower-extremity-joint-angles-during-gait-using-reduced-number-of-sensors-count-/assets/81487150/344c79b4-1541-465c-839b-88327d3b615d)



## If you use the dataset in your research, please cite the following paper:


@inproceedings{hossain2022estimating,
  title={Estimating lower extremity joint angles during gait using reduced number of sensors count via deep learning},
  author={Hossain, Md Sanzid Bin and Choi, Hwan and Guo, Zhishan},
  booktitle={Fourteenth International Conference on Digital Image Processing (ICDIP 2022)},
  volume={12342},
  pages={1116--1123},
  year={2022},
  organization={SPIE}
}

@article{moniruzzaman2021wearable,
  title={Wearable Motion Capture: Reconstructing and Predicting 3D Human Poses from Wearable Sensors},
  author={Moniruzzaman, Md and Yin, Zhaozheng and Hossain, Md Sanzid Bin and Guo, Zhishan and Choi, Hwan},
  journal={TechRxviz. Preprint},
  year={2021}
}


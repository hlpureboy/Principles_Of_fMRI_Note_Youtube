# Principles of fMRI (part 1)

[TOC]



## 1: 介绍fMRI

PET：blood flow、neurochemistry(神经化学)、opioids、dopamine

fMRI: brain strcuture、brain dynanmics、Whole brain in < 1s

![多学科交叉](http://file.sdnu.tech/54c3274d-fc24-bde3-5ef5-4da5ec890e8c.png)





![产生新的研究方向](http://file.sdnu.tech/a6ce3a6f-e9a5-a154-8d94-48a65ee14898.png)

![](http://file.sdnu.tech/b944a288-fdc0-1d04-807b-b707ace59ff7.png)

T1 : 能看 灰质 白质  脑脊液

DTI/DWI: 水分子运动

MRA: 明确心血管解剖和结构以及组织组成特点

**brain image：**

- **structural brain imaging**  -> 结构研究、疾病诊断、损伤 

  - CAT 
  - PET
  - MRI (T1/T2 )

- **Functional brain imaging**-> 认知、情感

  - PET
  - fMRI 4D 图像 
  - EEG  [Electroencephalography](https://en.wikipedia.org/wiki/Electroencephalography)
  - MEG

  **不同类型的功能成像在空间分辨率、时间分辨率、invasiveness（侵袭性）不同、fMRI在各方向比较平衡（近10年主流）**

  ![](http://file.sdnu.tech/fc57cf6b-a3d3-5f83-3c62-e0a6ff193755.png)

## 2.Analysis of fMRI Data

  fMRI 非入侵、无害。

  每一个图像大概包括100,000个体素。分布在3D空间，体素的值

  大概每2s获取一次 可以观察一个体素的强度在时间轴上的变化。

  **fMRI常用的测量方法**

  - Blood Oxygenation Level Dependent（BOLD） 
    - 测量 血液中含氧的血红蛋白与脱氧的比例
    - blood fMRI 不直接测量神经性活动、测量的是neurons活动的metabolic(新陈代谢的)demands
    - hemodynamic response function (HRF)  -> changes in fMRI信号 

  **fMRI data -> massive data**

  - 100,000 voxel measurements
  - hundreds of brain volumes
  - each experiment may be repeated for mutiple subjects

  Statistical analysis of fMRI

  - massive data
  - signal of interest is relatively weak
  - temporal and spatial noise structure

  fMRI pipeline

  ![](http://file.sdnu.tech/1ab378ee-71f0-39b1-236f-de37db869274.png)

  main goals of fMRI data

  - localization 
    - ![](http://file.sdnu.tech/1cf5a458-904d-3404-2f1d-9b7212996461.png)
  - connectivity
    - ![](http://file.sdnu.tech/5f030e7e-5ba0-3049-d0df-7540486c8d28.png)
  - prediction 
    - ![](http://file.sdnu.tech/53d8048a-0190-c8fc-0911-684e6f9f8ee2.png)

补充内容

  1. [youtube  Principles of fMRI (part 1)](https://www.youtube.com/watch?v=ZL-Tr1KSMKY&list=PLfXA4opIOVrGHncHRxI3Qa5GeCSudwmxM)



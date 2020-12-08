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

## 3.fMRI Data Structure & Terminology

Spatial and Temporal Resolution

- Temportal Resolution 

  - how quickly each individual image is acquired （TR）

- Spatial Resolution

  - distinguish changes in an image across different spatial locations

- T1

  - 高空间分辨率
  - 低时间分辨率
  - 可区分不同的组织

- T2

  - 低空间分辨率
  - 高时间分辨率
  - 实验过程中的信号改变

![](http://file.sdnu.tech/a475bb24-5a7a-0e00-46e6-6dafcce89949.png)

 MRI/fMRi -> axial slices -> 顺序扫描、间隔扫描

![3fc2c476-c334-1346-3998-4f04393a29ae.png](http://file.sdnu.tech/3fc2c476-c334-1346-3998-4f04393a29ae.png)



![1f8a71e5-3e29-2383-5de1-defda4adb205.png](http://file.sdnu.tech/1f8a71e5-3e29-2383-5de1-defda4adb205.png)

## 4. Psychological Questions and Inference

![5d76c0c8-32c7-5cf6-021e-c004aafa0298.png](http://file.sdnu.tech/5d76c0c8-32c7-5cf6-021e-c004aafa0298.png)

![f1b8e4ee-05bb-43f5-d27a-cd0b29568c3b.png](http://file.sdnu.tech/f1b8e4ee-05bb-43f5-d27a-cd0b29568c3b.png)



 

  ![b090f0e0-6ffb-bedd-f0e8-3c462509fbe8.png](http://file.sdnu.tech/b090f0e0-6ffb-bedd-f0e8-3c462509fbe8.png)

## 5. Basic MR Physics

**what mri Measures**

- MRI is an extremely versatile imaging modality that can be used to study both brain strcuture and brain function
- Both structural and functional MRI images are acquired using the same scanner
- Different types of brain image can be generated to emphasize contrast related to different tissue characteristics

**Principles of MRI**

- All magnetic resonance imaging techniques rely on a core set og physical principles
- single atomic nuclei -> hydrogen

![2c24bae9-24da-9c26-f292-329c68097e60.png](http://file.sdnu.tech/2c24bae9-24da-9c26-f292-329c68097e60.png)

![1f45f617-ddc0-cd9f-b541-c1ee5a389814.png](http://file.sdnu.tech/1f45f617-ddc0-cd9f-b541-c1ee5a389814.png)

![e34922b2-07c3-d19a-aa7b-dd396c1ef40e.png](http://file.sdnu.tech/e34922b2-07c3-d19a-aa7b-dd396c1ef40e.png)

![53c25157-a557-e79c-a1b0-e40ae399301f.png](http://file.sdnu.tech/53c25157-a557-e79c-a1b0-e40ae399301f.png)

![bad6767c-d9b0-60c0-a89b-46584b6907b8.png](http://file.sdnu.tech/bad6767c-d9b0-60c0-a89b-46584b6907b8.png)

![b853dcc4-9041-7120-bcc8-77df46a96540.png](http://file.sdnu.tech/b853dcc4-9041-7120-bcc8-77df46a96540.png)



补充内容

  1. [youtube  Principles of fMRI (part 1)](https://www.youtube.com/watch?v=ZL-Tr1KSMKY&list=PLfXA4opIOVrGHncHRxI3Qa5GeCSudwmxM)



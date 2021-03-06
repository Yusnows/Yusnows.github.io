---
layout: page
title: 梁宇钦
---

<center>
Email: YusnowsLiang@gmail.com ~ Phone: 15380994351
</center>



## 教育经历

- 南京大学  视觉/三维重建    硕士   2019.09~2022.06
- 南京大学  电子信息科学技术    学士    2015.09~2019.06

## 项目经历

### **基于人体背部表面信息的脊柱三维重建和姿态估计** *项目负责人* 2019.10–-2021.05

- **项目技术**: Python/Pytorch/C++; 三维重建;SMPL variant; 链式运动;优化算法。
- **项目简介**: 实现一种基于人体背部表面信息的人体脊柱三维重建和姿态估计方法。
  - 根据人体脊柱解剖学关系,脊柱力学特性等先验知识建立标准人体脊柱三维运动模型。
  - 根据人体背部表面信息 (RGBD) 重建人体背部表面三维模型,提取人体脊柱相关信息。
  - 根据提取的信息以及标准人体脊柱三维运动模型,优化得到真实的人体脊柱模型,进行脊柱姿态估计。
- **项目创新**: 首次实现依据人体背部表面信息而非 X 光等重建人体脊柱三维模型,估计人体脊柱姿态。
- **项目成果**: 建立了标准人体脊柱模型,实现了人体背部模型重建,能够根据人体背部标注的脊柱相关信息优化得到真实人体脊柱姿态。

### [**人体摔倒识别(检测)**](https://github.com/Yusnows/tumblerElf) *技术负责人* 2019.12--2020.05
- **项目技术**: Python/Pytorch; Detection; faster rcnn variant.
- **项目简介**: 利用人工智能技术实现高准确率的人体摔倒检测器。
  - 把人体摔倒检测问题从直觉上的姿态估计问题建模为视觉目标检测问题。
  - 使用两阶段目标检测框架,使用 DCN, FPN, Cascade 等技术手段提升检测准确度。
- **项目创新**: 将直觉上的姿态估计问题建模为视觉目标检测问题,解决了摔倒姿态的歧义问题。
- **项目成果**: 实现了高准确率的人体摔倒检测器。
  1. 参加并获得中国华录杯人体摔倒识别算法赛第一名。
  2. 参加并获得 OPPO TOP 高校创新科技大赛 5G 赛季三等奖。

### [**深度学习图像分类**](https://github.com/Yusnows/imcls) *项目负责人*  2019.10--2020.03

- **项目技术**: Python/Pytorch; Classification; CNN.
- **项目简介**: 借鉴已有的网络框架，设计并实现一个灵活方便的图像分类框架。%方便选择不同骨干网络，方便各种tricks的消融实验。
  - 软件框架分层设计，主要分为BackBone, Neck 和 Head 三个部分，层次清晰，方便增加或者修改。
  - 可以通过 yaml 配置文件完成大部分配置，不需要修改代码。
- **项目成果**: 实现了大部分预期功能，代码开源: [代码](https://github.com/Yusnows/imcls)。
    1. 参加并获得[世界人工智能创新大赛-菁英挑战赛](https://www.cvmart.net/race/8/rank)第一名。

## 获得奖项

- [**中国华录杯人体摔倒识别算法赛**](https://www.kesci.com/home/competition/5df99c5aea206700353c5de8/leaderboard) *第一名* 2020.04
- [**世界人工智能创新大赛-菁英挑战赛**](https://www.cvmart.net/race/8/rank) *第一名* 2020.07
- **OPPO TOP 高校创新科技大赛 5G 赛季** *三等奖* 2020.06
- [**首届全国“云状识别”算法大赛**](https://www.datafountain.cn/competitions/357/ranking?isRedance=0\&sch=1437) *第三名* 2019.11
- **南京大学优秀毕业生** *Top 15%* 2019.06
- **2018 年全国大学生模拟电子邀请赛** *全国 三等奖* 2018.08
- **2016 年江苏省大学生电子设计大赛 — TI 杯** *江苏省 一等奖* 2016.08
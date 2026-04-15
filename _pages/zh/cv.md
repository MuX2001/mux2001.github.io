---
layout: archive
title: "简历"
permalink: /zh/cv/
author_profile: true
lang: "zh-CN"
locale: "zh-CN"
lang_ref: "cv"
redirect_from:
  - /zh/resume
---

{% include base_path %}

<iframe
  src="{{ '/files/cv.pdf' | relative_url }}"
  style="width:100%; height:900px;"
  loading="lazy">
</iframe>

<p>如 PDF 无法加载，请<a href="{{ '/files/cv.pdf' | relative_url }}">点击此处下载</a>。</p>

---

## 研究方向

机器人学 · 机器人学习 · 控制与优化 · 强化学习

---

## 教育背景

**宾夕法尼亚大学**，费城，宾夕法尼亚州
电气工程 工程理学硕士（M.S.E.）　2024.01 – 2025.05
GPA：3.78/4.0
相关课程：机器人学习、现代凸优化、高级机器人学、F1TENTH 自主竞速

**浙江大学**，杭州，中国
电气工程 工学学士（与伊利诺伊大学厄巴纳-香槟分校联合学位）　2019.09 – 2023.06
GPA：3.56/4.0
相关课程：本科数学系列、信号与系统、机器学习、数值分析

**伊利诺伊大学厄巴纳-香槟分校（UIUC）**
电气工程 理学学士（与浙江大学联合学位）　2019.09 – 2023.06
GPA：3.26/4.0
相关课程：数字信号处理、数字系统、电子电路、线性与反馈控制系统

---

## 论文发表

**A Hybrid Learning-to-Optimize Framework for Mixed-Integer Quadratic Programming**
V.-A. Le, **M. Xie**, and R. Mangharam, 2025.
已被 Learning for Dynamics and Control（L4DC）录用，预印本见 [arXiv:2511.19383](https://arxiv.org/abs/2511.19383)。

**A Learning-to-Optimize Framework for Real-Time Mixed Integer Nonlinear Programming**
**M. Xie**, V.-A. Le, and R. Mangharam，投稿中。

---

<!--
## 科研经历

**科研助理，xLab**　2025.05 – 至今
宾夕法尼亚大学，费城，宾夕法尼亚州
导师：Rahul Mangharam 教授
- 从事面向自主系统的安全学习控制与学习优化方法研究。

**项目：混合整数非线性规划的学习加速框架**
- 提出 L2O-MISQP 框架，将神经网络嵌入信赖域 MISQP 求解器，加速复杂 MINLP 问题的在线求解。
- 设计了基于可微优化层的端到端混合训练流程。

**项目：混合整数 MPC 的混合学习优化**
- 针对参数化 MIQP 提出混合学习优化框架，目标是加速混合整数 MPC 的实时求解。
- 将神经整数预测、可微 QP 层与有监督/自监督损失整合为统一框架，同步提升可行性与最优性。

**项目：高斯过程动力学与 MPPI 控制**
- 基于 F1TENTH 实车数据训练 GP 动力学模型，并将预测不确定性融入 MPPI 控制框架。
- 系统考察了 GP 残差修正在不同模型失配程度下的效果，厘清了其改善性能与引发不稳定的边界条件。

---

## 代表性项目

**BeamNG 车辆 MPC 控制器**（课外项目）　2026.01 – 至今
宾夕法尼亚大学
- 在 BeamNG 中搭建了面向轨迹跟踪与高速自主驾驶的车辆控制流程。
- 实现并评估了 LTV-MPC 跟踪人类驾驶航点的效果，在 Spa 赛道上达到人类圈速的 80%。
- 进行中：在同一环境下搭建基于 Actor-Critic 强化学习的 DiffMPC 与 Vanilla MPPI 方案。

**F1TENTH 自主竞速**（课程项目）　2025.01 – 2025.05
宾夕法尼亚大学
- 基于 ROS 2 搭建了涵盖感知、规划与控制的完整自主赛车系统。
- 实现了墙壁跟随、间隙跟随、纯追踪与 MPC 控制器，集成动态避障与赛线优化。
- 开发了基于 LiDAR 的定位方案与基于视觉的车辆检测模块。
- 完成两场计时赛与一场对抗赛的实车硬件部署。工具：ROS 2、Python、C++。

**四旋翼控制论文复现**（课程项目）　2025.01 – 2025.05
宾夕法尼亚大学
- 复现了基于级联姿态/位置控制器的非线性四旋翼控制系统。
- 分析了参数不确定性与外部扰动下的鲁棒性，实现了传感器融合与轨迹生成模块。

**基于 LLM 的 F1TENTH 自然语言导航**（课程项目）　2025.03 – 2025.05
宾夕法尼亚大学
- 构建了将自然语言指令映射为驾驶原语的 LLM 规划器，融合符号推理与经典控制。
- 在仿真与真实 F1TENTH 平台上完成了端到端验证。

---
-->

## 教学与工作经历

**助教，仿真建模与分析（ESE 5030）**　2025.01 – 2025.05
宾夕法尼亚大学，费城
- 每周开设答疑课，为约 80 名研究生提供随机建模与仿真作业的指导。
- 批改作业与考试，就概率推理与建模步骤提供详细反馈。

**实习生，融阵科技有限公司**　2023.07 – 2023.12
杭州，浙江
- 为 ADC 芯片测试系统开发 FPGA 逻辑与测试台，涉及高速接口与数据采集流程。
- 使用 Verilog HDL、Quartus 与 Cadence SPB 验证芯片在多种工作条件下的性能指标。

---

## 技术技能

**编程语言：** C/C++、Python、LaTeX、MATLAB  
**工具与框架：** ROS 2、PyTorch、JAX  
**仿真平台：** Gym、MuJoCo

<!--
以下为模板原有内容，暂时保留备用：

## 出版物
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## 报告与演讲
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>

## 教学
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
-->

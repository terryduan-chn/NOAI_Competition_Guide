# NOAI 人工智能竞赛课程

> 基于 NOAI 2026 学术大纲 V1.5 | 14 个模块 | 50 节课 | 共 92 课时

## 简介

本仓库是 **NOAI（National Olympiad in Artificial Intelligence）** 竞赛的完整备考课程，涵盖竞赛全部考点。课程设计覆盖四大考核区域（A/B/C/D），包含详细理论讲解与可运行的编程实践代码。

## 竞赛结构

| 轮次 | 考查范围 | 对应模块 |
|------|----------|----------|
| **第一轮**（水平测试） | A 区（一般计算机技能）+ B 区（人工智能基础知识） | 模块 1-9 |
| **第二轮**（应用实践） | C 区（进阶计算机技能）+ D 区（人工智能进阶知识与技能） | 模块 10-14 |

## 课程总览

| 模块 | 内容 | 考核区域 | 课时 | 格式 |
|------|------|----------|------|------|
| 模块一 | 课程导论与竞赛概述 | 综合 | 2 | 📝 Markdown |
| 模块二 | Python 编程基础 | A 区 | 6 | 📓 Jupyter |
| 模块三 | 人工智能伦理与概述 | B 区 | 2 | 📝 Markdown |
| 模块四 | 数学基础（概率/统计/距离/线性） | B 区 | 6 | 📓 Jupyter |
| 模块五 | 机器学习方法范式 | B 区 | 8 | 📓 Jupyter |
| 模块六 | 监督学习核心算法 | B 区 | 10 | 📓 Jupyter |
| 模块七 | 模型评估与优化 | B 区 | 6 | 📓 Jupyter |
| 模块八 | 神经网络基础 | B 区 | 8 | 📓 Jupyter |
| 模块九 | 卷积神经网络 | B 区 | 6 | 📓 Jupyter |
| 模块十 | 数据处理与可视化工具 | C 区 | 8 | 📓 Jupyter |
| 模块十一 | PyTorch 深度学习实践 | D 区 | 10 | 📓 Jupyter |
| 模块十二 | 计算机视觉 | D 区 | 6 | 📓 Jupyter |
| 模块十三 | 自然语言处理 | D 区 | 6 | 📓 Jupyter |
| 模块十四 | 语音处理与大语言模型 | D 区 | 6 | 📓 Jupyter |

## 目录结构

```
NOAI课程/
├── README.md                          # 本文件
├── NOAI竞赛授课大纲_完整版.md           # 完整授课大纲（可编辑）
│
├── 模块一_课程导论/
│   ├── 1.1_NOAI竞赛介绍.md
│   ├── 1.2_人工智能发展简史.md
│   └── 1.3_课程学习方法与备考策略.md
│
├── 模块二_Python编程基础/
│   ├── 2.1_Python基本语法.ipynb
│   ├── 2.2_程序控制结构.ipynb
│   ├── 2.3_基本数据结构.ipynb
│   ├── 2.4_函数模块与包.ipynb
│   └── 2.5_算法基础与第三方库.ipynb
│
├── 模块三_AI伦理与概述/
│   ├── 3.1_人工智能的基本概念.md
│   └── 3.2_AI伦理与安全.md
│
├── 模块四_数学基础/
│   ├── 4.1_概率论基础.ipynb
│   ├── 4.2_统计学基础.ipynb
│   ├── 4.3_距离度量.ipynb
│   └── 4.4_线性与非线性.ipynb
│
├── 模块五_机器学习方法范式/
│   ├── 5.1_监督学习.ipynb
│   ├── 5.2_无监督学习.ipynb
│   ├── 5.3_强化学习.ipynb
│   └── 5.4_数据基础.ipynb
│
├── 模块六_监督学习核心算法/
│   ├── 6.1_线性回归.ipynb
│   ├── 6.2_逻辑回归.ipynb
│   ├── 6.3_其他常见算法概述.ipynb
│   └── 6.4_集成学习.ipynb
│
├── 模块七_模型评估与优化/
│   ├── 7.1_分类评估指标.ipynb
│   ├── 7.2_交叉验证.ipynb
│   └── 7.3_过拟合欠拟合与正则化.ipynb
│
├── 模块八_神经网络基础/
│   ├── 8.1_感知机与神经网络概述.ipynb
│   ├── 8.2_误差反向传播.ipynb
│   ├── 8.3_梯度下降与优化方法.ipynb
│   ├── 8.4_激活函数损失函数与决策函数.ipynb
│   └── 8.5_大语言模型概述.ipynb
│
├── 模块九_卷积神经网络/
│   ├── 9.1_卷积神经网络基本原理.ipynb
│   └── 9.2_神经网络常用层原理与计算.ipynb
│
├── 模块十_数据处理与可视化/
│   ├── 10.1_NumPy数据处理.ipynb
│   ├── 10.2_Pandas数据分析.ipynb
│   ├── 10.3_Matplotlib数据可视化.ipynb
│   └── 10.4_特征工程技术.ipynb
│
├── 模块十一_PyTorch深度学习实践/
│   ├── 11.1_PyTorch基础语法.ipynb
│   ├── 11.2_神经网络定义与训练.ipynb
│   ├── 11.3_CPU与GPU训练.ipynb
│   ├── 11.4_权重初始化与批量归一化.ipynb
│   └── 11.5_RNN与GAN基础.ipynb
│
├── 模块十二_计算机视觉/
│   ├── 12.1_图像分割.ipynb
│   ├── 12.2_目标检测.ipynb
│   └── 12.3_特征提取与迁移学习.ipynb
│
├── 模块十三_自然语言处理/
│   ├── 13.1_文本预处理与词法分析.ipynb
│   ├── 13.2_文本分类与词嵌入.ipynb
│   └── 13.3_Transformer与预训练模型.ipynb
│
└── 模块十四_语音与大语言模型/
    ├── 14.1_语音信号处理.ipynb
    ├── 14.2_生成式AI与大语言模型.ipynb
    └── 14.3_综合实践与竞赛模拟.ipynb
```

## 课程内容特色

- **理论 + 实践双轨制**：Markdown 文件覆盖纯理论内容，Jupyter Notebook 包含可运行的 Python 代码
- **从零实现核心算法**：线性回归、逻辑回归、感知机、自注意力机制等均提供 NumPy/PyTorch 原生实现
- **工业级工具链**：Scikit-learn、PyTorch、OpenCV、Pandas、Matplotlib、Hugging Face Transformers
- **公式与可视化**：LaTeX 数学公式 + Matplotlib 图表，直观理解算法原理
- **竞赛导向**：每节包含练习题与竞赛模拟题，紧扣 NOAI 考试大纲

## 快速开始

### 环境要求

```bash
# 推荐使用 Python 3.9+
# 创建虚拟环境
python -m venv noai-env
source noai-env/bin/activate  # Linux/Mac
# noai-env\Scripts\activate   # Windows

# 安装核心依赖
pip install numpy scipy matplotlib pandas scikit-learn jupyter
pip install torch torchvision  # PyTorch（模块 9-14 需要）
pip install jieba nltk         # NLP（模块 13 需要）
pip install opencv-python      # 计算机视觉（模块 12 需要）
pip install transformers       # 预训练模型（模块 13 需要）
```

### 使用方式

```bash
# 启动 Jupyter Notebook
jupyter notebook

# 或使用 JupyterLab
jupyter lab
```

打开任意 `.ipynb` 文件即可运行代码。Markdown 文件可用任意文本编辑器查看和编辑。

## 知识路线图

```
Python 基础 (模块2)
    │
    ▼
数学基础 (模块4) ── AI伦理 (模块3)
    │
    ▼
机器学习方法 (模块5) ── 数据工具 (模块10)
    │
    ▼
监督学习算法 (模块6)
    │
    ▼
模型评估优化 (模块7)
    │
    ▼
神经网络基础 (模块8)
    │
    ├──▶ CNN (模块9) ──▶ 计算机视觉 (模块12)
    │
    ├──▶ PyTorch实践 (模块11)
    │
    ├──▶ NLP (模块13)
    │
    └──▶ 语音与大模型 (模块14)
```

## 参考资源

| 资源 | 说明 |
|------|------|
| [NOAI 2026 学术大纲 V1.5](https://noai.org) | 竞赛官方考纲 |
| [动手学深度学习 (d2l-zh-pytorch)](https://zh.d2l.ai) | PyTorch 版深度学习教材 |
| [IAIO Training Guide](https://iaio-official.org) | 国际人工智能奥林匹克训练指南 |
| [IOAI Syllabus 2025](https://ioai-official.org) | 国际奥林匹克 AI 竞赛大纲 |

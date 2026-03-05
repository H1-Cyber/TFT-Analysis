# TFT Masters Meta Analysis

TFT大师段位对局数据分析项目  
作者：TFT大师段位玩家（3年经验），使用数据验证游戏直觉（运营、北伐、撞车、阵容选择等）。

## 项目目标
- 分析高分段（大师/宗师）对局数据，量化“后期翻盘/稳运营”优势。
- 探索阵容胜率、撞车影响、等级运营规律。
- 作为个人数据分析练习，未来扩展到游戏数值/数据岗求职。

## 技术栈
- Python 3.11
- pandas（数据处理）
- matplotlib/seaborn（可视化）
- Jupyter Notebook（分析流程）
- 环境：Miniconda + 虚拟环境

## 关键发现（已完成）
- **等级 vs 吃鸡率**：大师局中，8级吃鸡率最高，证明后期运营更稳（图见下方）。
- **其他待扩展**：Top阵容胜率、撞车率影响、英雄三星概率等。

![吃鸡率 vs 等级](tft_eat_chicken_rate.png)  
*(截图示例：把你笔记本里生成的图保存为 png，上传到 repo，再把文件名改成 tft_eat_chicken_rate.png，贴链接)*

## 如何运行
1. 克隆仓库：
   ```bash
   git clone https://github.com/HI-Cyber/TFT-Analysis.git
   cd TFT-Analysis

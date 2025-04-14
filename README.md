

# 子序列 DTW 引导下的残缺轨迹补全系统


**本项目可支持个性化修改与交付，如有项目需求可联系我**

**⭐️ 如果你觉得这个项目有帮助，欢迎 Star 支持！**

**📬 项目合作或定制开发欢迎联系我～**

📧 Email: linyuli642@gmail.com 

本项目通过 MATLAB 实现一种基于子序列动态时间规整（Subsequence DTW）和 LSTM 深度学习模型的轨迹补全方法，解决 AIS 船舶数据中因信号中断导致的轨迹缺失问题。

## 📌 项目特色

- MATLAB R2023a 环境开发
- 使用 Deep Learning Toolbox 构建 LSTM 网络
- 引入子序列 DTW 匹配机制提供轨迹引导
- 支持轨迹分类、贝叶斯优化调参、并行训练
- 可复现、可视化、多模块清晰划分

## 📁 文件说明

| 文件名 | 说明 |
|--------|------|
| `研究报告.pdf` | 项目完整背景、模型设计与实验结果 |
| `程序运行环境说明.pdf` | 操作步骤、脚本说明与复现环境需求 |
| `/源代码_(.mlx)/` | 包含核心 `.mlx` 脚本，模块化结构 |
| `/data/` | 可选示例数据 |

## 🔧 使用环境

- MATLAB R2023a+
- 工具箱：
  - Deep Learning Toolbox
  - Statistics and Machine Learning Toolbox
  - Parallel Computing Toolbox

## 📄 如何运行

1. 设置当前路径为项目主目录  
2. 打开 `/源代码_(.mlx)/LSTM_PAR.mlx` 运行残缺轨迹补全脚本  
3. 可根据运行环境说明文档进行完整流程执行

## 📢 License & Copyright
## 📢 版权声明


This is an original work by the author. All contents—including code, documentation, and research report—are for academic display and non-commercial purposes only. Unauthorized copying, citation, or commercial usage is strictly prohibited. For collaboration or permission, please contact the author.
All rights reserved. Unauthorized reproduction or distribution of this project, in whole or in part, is strictly prohibited.

本项目为原创作品，所有内容（包括代码、报告、模型设计与说明文档）均由作者独立完成，仅用于学习展示与学术交流用途。未经作者允许，禁止转载、引用或用于任何形式的商业用途。若需引用或使用本项目成果，请联系作者获取授权。
本项目不开放源代码授权，禁止转载、复制、传播或用于教学、培训、竞赛或商业用途。本项目仅用于作者个人展示，保留一切权利。

⚠️ 本项目已于 2025-04-09 22:47:21 提交至 船视宝杯第二十届全国交通运输科技大赛 比赛，仅作为个人开发展示之用途，未用于任何其他平台参赛、发布或评奖。









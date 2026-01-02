# Aether Sight

**FFXIV 装备图片匹配项目**

[![GitHub](https://img.shields.io/badge/GitHub-AetherSight-181717?style=flat-square&logo=github)](https://github.com/AetherSight)
[![License](https://img.shields.io/badge/License-AGPL--3.0-green?style=flat-square)](LICENSE)

## 关于我们

Aether Sight 是一个个人兴趣驱动的 FFXIV 装备图片匹配项目。

## 项目展示

### 🔮 [Unveil](https://github.com/AetherSight/Unveil)

**FFXIV 装备识别前端服务**

基于 Next.js 的前端服务，整合装备识别和分割功能。

[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)](https://nextjs.org/)

### 🔎 [Revelation](https://github.com/AetherSight/Revelation)

**FFXIV 装备识别微服务**

基于深度学习的 Web 服务，从图片中识别 FFXIV 装备并返回 top-K 识别结果和相似度分数。

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)

### ✂️ [Dissector](https://github.com/AetherSight/Dissector)

**FFXIV 幻化装备分割微服务**

用于从角色图片中分割出头部、上身、下身、鞋子和手部等装备部位。

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)

### 🚀 [Ascension](https://github.com/AetherSight/Ascension)

**装备图片匹配模型训练框架**

用于训练装备图片匹配模型的训练框架。

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)

### 🛠️ [FFXIV_TexTools_Exporter](https://github.com/AetherSight/FFXIV_TexTools_Exporter)

**装备纹理导出工具**

用于导出 FFXIV TexTools 的纹理数据。

## 开发规划

1. 接入光之收藏家（ffxivsc）的数据进行重新训练
2. 前端重构，增加 icon 支持、同模查询支持
3. 正式上线部署，需要解决 GPU 机器问题
4. 增加反馈接口，接受用户提交的正确数据，迭代进行模型训练

## 团队成员

<a href="https://github.com/RicterZ">
  <img src="https://github.com/RicterZ.png" width="80" height="80" alt="RicterZ">
</a>

**⭐ 如果项目对您有帮助，欢迎 Star 支持！**

Made with ❤️ by [Aether Sight](https://github.com/AetherSight)

## 版权声明

**FINAL FANTASY XIV © 2010 - 2026 SQUARE ENIX CO., LTD. All Rights Reserved.**

**© SQUARE ENIX CO., LTD. All Rights Reserved.**

本项目与 Square Enix 无任何关联，仅用于学习和研究目的。


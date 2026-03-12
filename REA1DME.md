# Rice Blast Resistance Analysis Tools

本项目包含用于分析水稻抗稻瘟病基因编辑实验数据的自动化脚本。

## 功能介绍
- **数据统计**：自动计算不同敲除株系（如 D1301, D2302）的病斑面积均值与标准差。
- **显著性分析**：基于 T-test 自动计算突变体与野生型（WT）之间的差异显著性。
- **可视化**：生成符合学术出版标准的柱状图，直观展示抗性提升效果。

## 研究背景
通过 CRISPR/Cas9 技术协同敲除水稻感病基因（如 *OsBsr-d1*, *OsPi21* 等），创制高抗、广谱的稻瘟病抗性新种质。

## 环境要求
- Python 3.x
- pandas, matplotlib, seaborn, scipy

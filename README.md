# zcq-visualization

交互式数据可视化仓库，基于 Plotly 构建，支持多种可视化类型。

## 功能

- **t-SNE 3D 可视化**：高维数据降维后的三维散点图（分类 / 组合 / RPM 三种视图）
- **混淆矩阵热力图**：模型分类结果的可视化分析
- **ROC 曲线**：模型性能评估
- **箱线图**：数据分布统计

## 运行

```bash
# 生成交互式可视化页面
python html_zcq.py

# 输出
# docs/index.html - 交互式可视化入口页面
```

## 在线预览

访问 Sites版：[https://zcq-visualization-sites.zcq991029.chatgpt.site/](https://zcq-visualization-sites.zcq991029.chatgpt.site/)

## 文件结构

| 文件/目录 | 说明 |
|---|---|
| `html_zcq.py` | 主入口脚本，生成可视化页面 |
| `docs/index.html` | 生成的交互式页面（Sites版入口源） |
| `tsne_3d_class.html` | t-SNE 分类视图 |
| `tsne_3d_combined.html` | t-SNE 组合视图 |
| `tsne_3d_rpm.html` | t-SNE RPM 视图 |
| `beifen.html` | 备用可视化页面 |
| `zuhui.html` | 组会展示页面 |

## 技术栈

- Python + Plotly
- HTML / JavaScript (SheetJS, Plotly.js)
- Sites版托管；GitHub 仅保存源码与生成文件

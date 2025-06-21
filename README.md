# Suntec REIT 双语分析报告

## 📊 项目简介

这是一个专业的Suntec REIT投资分析报告，支持中英文双语切换，包含完整的财务数据分析、图表可视化和ESG评估。

## 🌐 在线预览

- **GitHub Pages**: [在线查看报告](https://aji-q.github.io/Product/suntec-reit-analysis-bilingual.html)
- **直接下载**: 从GitHub下载ZIP文件

## ⚠️ 重要说明：本地运行 vs GitHub下载

### 问题描述
当您从GitHub下载ZIP压缩包并在本地打开HTML文件时，可能会遇到以下问题：
- 图片无法显示
- 图表无法加载
- 样式显示异常

### 原因分析
1. **相对路径问题**: HTML文件中的图片路径使用了相对路径 `photo/SuntecCity.jpg`
2. **外部资源依赖**: 图表库依赖CDN资源，需要网络连接
3. **文件结构**: ZIP解压后的文件结构可能与原始结构不同

### 解决方案

#### 方案1：使用GitHub Pages（推荐）
1. 访问 [https://aji-q.github.io/Product/suntec-reit-analysis-bilingual.html](https://aji-q.github.io/Product/suntec-reit-analysis-bilingual.html)
2. 直接在浏览器中查看，所有功能正常

#### 方案2：本地服务器运行
如果您想在本地运行，请使用本地服务器：

**使用Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**使用Node.js:**
```bash
npx http-server
```

**使用Live Server (VS Code扩展):**
1. 安装Live Server扩展
2. 右键点击HTML文件
3. 选择"Open with Live Server"

#### 方案3：修复文件结构
确保下载后的文件结构如下：
```
suntec-reit-analysis-bilingual.html
photo/
  ├── SuntecCity.jpg
  └── 1725624.png
```

## 📁 文件结构

```
Product/
├── suntec-reit-analysis-bilingual.html    # 双语版本（推荐）
├── suntec-reit-analysis-enhanced.html     # 中文版本
├── suntec-reit-analysis.html              # 基础版本
├── photo/                                 # 图片文件夹
│   ├── SuntecCity.jpg                     # 新达城照片
│   └── 1725624.png                        # 分析图表
└── README.md                              # 说明文档
```

## 🚀 功能特点

### 双语支持
- 中英文无缝切换
- 专业金融术语对照
- 完整的数据本地化

### 数据可视化
- 投资组合地理分布饼图
- ESG进展时间线图
- 可筛选的财务数据表格

### 专业分析
- 16步产品定位分析法
- 可持续竞争优势评估
- 问题解决能力分析
- 完整的财务指标

### 数据来源
- Suntec REIT官方披露
- SGX交易所数据
- 第三方ESG评级
- 权威财经媒体

## 📊 主要数据指标

| 指标 | 数值 | 来源 |
|------|------|------|
| 投资组合价值 | SGD 12.1B | 2024年度报告 |
| 办公入住率 | 98.8% | 2024财年结果 |
| 购物中心入住率 | 98.4% | 2024财年结果 |
| 杠杆率 | 42.4% | 2024财年结果 |
| 绿色贷款比例 | 70% | 可持续发展报告 |

## 🔧 技术栈

- **前端**: HTML5, CSS3, JavaScript
- **图表库**: Chart.js
- **数据处理**: DataTables
- **样式**: 响应式设计，支持移动端

## 📞 联系方式

如有问题或建议，请通过以下方式联系：
- GitHub Issues: [提交问题](https://github.com/Aji-Q/Product/issues)
- Email: [您的邮箱]

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

---

**注意**: 本报告仅供学习和研究使用，不构成投资建议。投资有风险，决策需谨慎。 
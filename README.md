# 仓库管理系统

## 项目简介

仓库管理系统是一个基于Python Flask框架开发的Web应用，用于管理仓库商品的库存信息。系统提供了商品的添加、编辑、删除、搜索等功能，并通过图表直观展示库存数据。

## 技术栈

- 后端：Python、Flask框架
- 前端：HTML、CSS、JavaScript、Bootstrap 5
- 数据存储：JSON文件
- 数据可视化：Chart.js
- 拖拽功能：Sortable.js

## 功能特性

- 商品管理：添加、编辑、删除商品
- 商品搜索：按名称和分类搜索商品
- 数据统计：显示商品总数、库存总量、分类数量
- 数据可视化：商品分类分布饼图、库存数量柱状图
- 拖拽排序：支持长按商品ID进行拖拽排序
- 响应式设计：适配不同屏幕尺寸

## 安装与运行

1. 下载项目到本地
2. 安装依赖：`pip install flask`
3. 运行应用：`python app.py`
4. 在浏览器中访问：`http://127.0.0.1:5000`

## 项目结构

```
仓库管理系统/
├── app.py          # 主应用文件
├── main.py         # 命令行版本（备用）
├── warehouse_data.json  # 数据存储文件
├── templates/      # HTML模板
│   ├── index.html  # 首页
│   ├── add.html    # 添加商品页面
│   ├── update.html # 更新商品页面
│   └── search.html # 搜索商品页面
└── README.md       # 项目说明
```

# "惠聚"电商平台用户行为分析及品类优化策略研究

## 项目背景

本项目旨在模拟一次真实电商平台的数据分析过程，背景设定为"惠聚"电商平台在2022年的运营数据。目标是通过对用户交易数据的分析，深入理解用户构成、消费习惯及品类偏好，为平台的品类发展战略、精准营销和提升用户体验提供数据洞察和决策支持。

该项目也作为个人数据分析能力与经验的展示，部分思路参考了在腾讯实习期间参与的电商项目。

## 数据来源

数据集基于 Kaggle 上的 "Walmart Sales Dataset"，并假设其为"惠聚"平台2022年经过脱敏处理的用户交易记录。

原始数据集链接：[https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset)

## 项目目标

1.  **用户画像分析：** 识别不同用户群体的特征及其消费行为模式。
2.  **品类销售与偏好分析：** 挖掘热销品类、潜力品类，以及不同用户群体对品类的偏好差异。
3.  **购买行为模式分析：** 分析用户的消费能力、高价值用户特征等。
4.  **策略建议：** 基于分析结果，为"惠聚"平台在品类策略、用户运营等方面提供可落地的建议。

## 技术栈

*   **编程语言：** Python 3.x
*   **核心库：** Pandas, NumPy, Matplotlib, Seaborn
*   **开发环境：** Jupyter Notebook / JupyterLab
*   **版本控制：** Git

## 项目结构

```
huiju_ecommerce_analysis/
├── data/
│   └── huiju_sales_data_2022.csv
├── notebooks/
│   ├── 00_project_setup_and_data_overview.ipynb
│   ├── 01_data_cleaning_and_preprocessing.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_user_segmentation_analysis.ipynb
│   ├── 04_product_category_analysis.ipynb
│   └── 05_conclusions_and_recommendations.ipynb
├── src/
│   └── utils.py
├── reports/
│   └── huiju_analysis_report_q3_2022.md
├── images/
├── venv/                    # Python虚拟环境
├── requirements.txt         # 项目依赖包列表
└── README.md
```

## 环境设置

### 1. 激活虚拟环境

项目已配置了独立的Python虚拟环境，使用前请先激活：

```bash
# 在项目根目录下
source venv/bin/activate
```

### 2. 安装依赖包

如果是首次使用或需要重新安装依赖：

```bash
pip install -r requirements.txt
```

### 3. 配置Jupyter内核

项目已为虚拟环境创建了专用的Jupyter内核，名称为"惠聚电商分析"。

## 如何运行

1.  **激活虚拟环境：**
    ```bash
    source venv/bin/activate
    ```

2.  **启动Jupyter Notebook：**
    ```bash
    jupyter notebook
    ```
    或者使用JupyterLab：
    ```bash
    jupyter lab
    ```

3.  **选择正确的内核：** 在Jupyter中，确保选择"惠聚电商分析"内核。

4.  **按顺序运行Notebooks：** 进入 `notebooks/` 目录，按文件名顺序运行各个分析文件。

## 主要发现与结论（待填充）

## 业务建议（待填充）

## 注意事项

- 请确保在激活虚拟环境的状态下运行所有代码
- 如果遇到包导入问题，请检查是否选择了正确的Jupyter内核
- 数据文件路径为相对路径，请确保在正确的目录下运行代码 
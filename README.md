<div align="center">

# Hi, I'm lusikai172 👋

**Python · Django · 数据分析与可视化**

把课程作业和论文实验，做成别人 `git clone` 下来就能跑通的项目。

[![Repos](https://img.shields.io/badge/项目-4-4A90D9?style=flat-square)](https://github.com/lusikai172-sys?tab=repositories)
[![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-5.1-092E20?style=flat-square&logo=django&logoColor=white)](https://www.djangoproject.com/)

</div>

---

## 🚀 精选项目

| 仓库 | 这个项目在做什么 | 技术栈 |
| :--- | :--- | :--- |
| **[ad-ctr-prediction](https://github.com/lusikai172-sys/ad-ctr-prediction)** | 广告曝光/点击日志 → 数据清洗 → 多维统计大屏 → 随机森林模型实时预估单条广告点击率 | `Django` `scikit-learn` `pandas` `pyecharts` |
| **[ride-hailing-analytics](https://github.com/lusikai172-sys/ride-hailing-analytics)** | 2.7 万条网约车行程记录 → 时段分布、热点小时、车辆周转 → 柱状图/饼图/箱线图/旭日图/地图 | `Django` `pandas` `pyecharts` |
| **[python-learning-archive](https://github.com/lusikai172-sys/python-learning-archive)** | 本科四年 200+ 个 Python 脚本归档：数据分析实训、数据仓库、机器学习、文本挖掘、LDA 主题建模 | `pandas` `sklearn` `BERTopic` `gensim` `pyLDAvis` |

---

## 💡 这些仓库有什么不一样

大部分课程作业仓库的问题，是别人点进来之后**跑不起来**——数据缺失、路径写死、依赖没写。这三个仓库专门针对这几点做了处理：

- **数据缺失也能跑**：原始数据体积过大不入库，仓库内置 2000 行示例数据；更大的数据用 `python tools/simulate_data.py --dataset all` 一键生成结构一致的合成数据
- **配置不写死**：数据库、密钥、数据目录全部走环境变量，附 `.env.example`，克隆后复制改名即可
- **开箱有账号**：Django 项目自带 `fixtures/demo_user.json`，`loaddata` 后直接登录看界面
- **每条路都验证过**：`manage.py check`、迁移、登录、全部路由 200 响应，逐项实测

---

## 🛠 技术栈

<div align="center">

**语言与框架**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**数据分析**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

**可视化与 NLP**

![ECharts](https://img.shields.io/badge/pyecharts-AA344D?style=for-the-badge&logo=apacheecharts&logoColor=white)
![jieba](https://img.shields.io/badge/jieba-FF6B6B?style=for-the-badge)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

</div>

---

## 📚 学习轨迹

```
数据分析实训  →  数据仓库与关联规则  →  机器学习  →  文本挖掘 / 主题建模
   爬虫+可视化       Apriori / RFM        回归 / 聚类      BERTopic / LDA / 情感分析
```

一路上踩过的坑都记在仓库的 README 里，包括 pyecharts 2.x 的 API 变更、pyLDAvis 在 numpy 2.x 下的 PCoA 报错这类具体问题——搜到的人可以直接绕过。

---

## 📫 联系

- 有问题欢迎直接在对应仓库提 **Issue**，我会看
- 如果某个项目帮到了你，点个 ⭐ 就是最好的鼓励

<div align="center">

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=lusikai172-sys.lusikai172-sys&left_text=Profile%20Views)

</div>

## Портфолио проектов
<!---
your comment goes here
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>

<a rel="noreferrer"> <img src="" alt="python" width="40" height="40"/> </a>
-->





<h3 align="left">Языки, билиотеки и технологии:</h3>

<!---
PostgreSQL
-->
<p align="left">   
</a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a>
<!---
Clickhouse
-->
<a rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Clickhouse.png" alt="CH" width="40" height="40"/></a>
<!---
Python
-->
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
<!---
pandas
-->
<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>   
<!---
sklearnn
-->
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> 
<!---
seaborn
--> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> 
<!---
matplotlib
-->
<a rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Created_with_Matplotlib-logo.svg/2048px-Created_with_Matplotlib-logo.svg.png" alt="python" width="40" height="40"/></a> 
<!---
scipy
-->
<a target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/1200px-SCIPY_2.svg.png" alt="scipy" width="40" height="40"/> </a>
<!---
git
-->
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
<!---
GitHub
-->
  <a target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png" alt="github" width="40" height="40"/> </a> 
<!---
GitLab
-->
<a target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/25181517/192108376-c675d39b-90f6-4073-bde6-5a9291644657.png" alt="gitlab" width="40" height="40"/> </a>
<!---
Jupiter
-->
<a target="_blank" rel="noreferrer"> <img src="https://user-images.githubusercontent.com/25181517/183914128-3fc88b4a-4ac1-40e6-9443-9a30182379b7.png" alt="jupiter" width="40" height="40"/> </a>
<!---
Airflow
-->
<a target="_blank" rel="noreferrer"> <img src="https://static-00.iconduck.com/assets.00/airflow-icon-512x512-tpr318yf.png" alt="arflow" width="40" height="40"/> </a></p>

*	**BI**: PowerBI (DAX + Power Query), Superset, Redash, дашбоды в Excel и Google Sheets.
*	**SQL**: запросы, подзапросы, джоины, оконные функции; PostgreSQL, ClickHouse.
*	**Python**: numpy,  pandas,  seaborn,  matplotlib, plotly, scipy.stats,  statsmodels, sklearn, GXBoost.
*	**Excel**: функции, ВПР, анализ данных, массивы, сводные таблицы, срезы, графики, дашаборды, Power Query.
*	Git, GitHub, Jupiter, GoogleCollab, airflow.
*	Статистика, маркетинг, поведенческая экономика, юнит-экономика, продуктовые метрики.


---

### 1. [Аналитика для приложения социальных сетей](https://github.com/AlinaEvgenevna/AppAnalytics) 


| Проект   |     Описание      |  Инструменты |
|----------|---------------|-------|
| [Дашборды](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/dashboards) |  Подготовка системы дашбордов, отражений основных метрик в динамике (dau, wau, mau, ctr, разрезы пользователей, поведение пользователей, качество трафика), исследование оперативных данных в реальном времени. | Superset, SQL, Clickhouse |
| [Анализ  Retention](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/Retention) |    Анализ удержания пользователей, сравнение рекламного и органического трафика. |   Suprset, SQL, Python |
| [Анализ ad-hoc гипотез](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/AdHocResearch) | Изучение необычного скачка и необычного падение трафика в определенные дни. |    Superset, SQL |
| [A/B тесты](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/AB_tests) | Проверка влияния нового алгоритма показа в ленте новостей на CTR. Сплитование хэшированием с солью, A/A тест, A/B тесты с помощью t-test, mann-whitney, bootstrap, бакетное преобразование и линеаризации метрик перед тестами. Цель - решить, стоит ли выкатывать новый алгоритм на всех пользователей. |   Python |
| [Выгрузка автоматической отчетности в таблицы](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/etl_dag_to_table) | Настройка ETL-pipeline для отчетности в Airflow. Формирование отчета и выгрузка его в ClickHouse таблицы.|    Python, Airflow, Clickhouse, git, Redash |
| [Выгрузка ежедневного сводного отчета в чат через телеграм бота](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/dag_report_chat_bot) | Формирование отчета и графиков по метрикам за прошедший день, отправка автоматических сообщений. |    Python, Airflow, Telegram |
| [Поиск аномалий и автоматизация рассылки алертов в телеграм-чат](https://github.com/AlinaEvgenevna/AppAnalytics/tree/main/dag_anomaly_alerts) | Написание алгорита поиска аномалий в данных, формирование алерта с текстом и графиками, отправка автоматизированных сообщений в телеграм при возникновении аномалии. |    Python, Airflow, Telegram |



#### 2. [Репозиторий - Маркетинговая и продуктовая аналитика](https://github.com/AlinaEvgenevna/MarketingDA)
| Проект   |      Описание     |  Инструменты |
|----------|---------------|--------|
| [Когортный анализ супермаркета](https://github.com/AlinaEvgenevna/MarketingDA/tree/main/CohortAnalysis) |  Цель - проанализировать динамику удержания клиентов. Разбить клиентов на когорты и исследовать retention rate динамику. | Python, pandas, seaborn heatmap,  |
| [RFM анализ клиентов супермаркета](https://github.com/AlinaEvgenevna/MarketingDA/tree/main/RFM_in_online_market)|    Анализ покупателей по их потребительского поведению, дата последней покупки, частота покупок, монетарная ценность; разделение на кластеры.  |   Python, seaborn, pandas, sklearn |
| [A/B тест для сравнения двух типов рекламного объявления](https://github.com/AlinaEvgenevna/MarketingDA/tree/main/AB_test) | Сравнение конверсий после просмотра двух разных типов объявлений. | Python, pandas, seaborn, statsmodels, proportions_ztest |
| [Отчеты по сервису доставки](https://github.com/AlinaEvgenevna/MarketingDA/tree/main/Delivery_reports) | 1. Обзорный отчет по основным показателям сервиса доставки. 2. Отчет об удержании клиентов по дням (сравнение ушедших и удержанных, декомпозиция пользователей на новых/ удержанных/ вернувшихся/ воскресших, когортный анализ) 3. Сравнение двух маркетинговых кампаний (CAC, ROI, AOV, Retention, ARPPU и т.п.)| SQL, Redash |
| [Отчеты в Power BI](https://github.com/AlinaEvgenevna/MarketingDA/tree/main/PowerBIDashboards) | 1. Отчет по рынку труда в США в области науки о данных. 2. Отчет для отдела кадров (статистика, анализ инклюзивности, анализ текучки, результаты ревью| PowerBI, Power Query, DAX |


#### 3. [Репозиторий - Классические задачи DS](https://github.com/AlinaEvgenevna/DS)
| Проект   |      Описание     |  Инструменты |
|----------|---------------|------|
| [Линейная регрессия](https://github.com/AlinaEvgenevna/DS/tree/main/LinearRegression) | Цель проекта - исследовать ценообразование машин на китайском рынке (не предсказание цены). Проверены допущения для линейной регрессии, исследованы взаимосвязи между переменными, построена модель с 91% коэффицинтом детерминации, дана интерпретация коэффициентам.| Python, scipy.stats, sklearn и др.|
| [Предсказание выбывания сотрудника ml алгоритами](https://github.com/AlinaEvgenevna/DS/tree/main/Churn_classification)|    Цель - построить модели, которые предскажут выбывания сотрудника. Использованы модели логистической регрессии с разными thresholds, RandomForestClassifier, GXBoostClassifier. | Python, sklearn, GXBoost, GridSearchCV |
| [Кластеризация покупателй шопинг-центра](https://github.com/AlinaEvgenevna/DS/tree/main/Customer_clusters) | Разделить покупателей по кластерам на основе пола, возраста, доходам и уровням трат для составления кастомизированных под каждый кластер маркетинговых стратегий и политик. |    Python, sklearn, scipy, KMeans, Hierarchical clustering |

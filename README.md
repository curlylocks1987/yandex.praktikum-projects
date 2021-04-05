# yandex.praktikum-projects

Данные проекты были выполнены на Python в Jupyter Notebook в ходе обучения в Яндекс.Практикуме профессии "Аналитик данных".

| Название проекта | Описание | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- |
|[Game Market Analysis](Game_market_analysis_cumulative_1)|Для компании-разработчика игр проанализировал рынок, сделал предобработку. В ходе EDA посчитал продажи по платформам, корреляции оценок критиков и пользователей, выделил топ жанры по регионам и платформам, срок жизни платформы и т.п. Сформировал портреты пользователей разных регионов. Провел статистический тест с использованием t-критерия Стьюдента. Дал рекомендации компании по развитию на разных рынках.|*pandas*, *Matplotlib*, *numpy*, *skipy.stats*|
| [AAB-test for food market app](cumulative_2-food_startup_app_script_test) | Для продуктового стартапа проанализировал поведение пользователей приложения, построил воронку событий и провел A/A/B-тест для выявления эффекта от введения нового шрифта.|*pandas*, *seaborn*, *Matplotlib*, *Plotly*, *numpy*, *datetime*, *scipy.stats*, *math*|
|[Business Metrics for Yandex.Afisha](Business_Metrics_for_Yandex.Afisha_(project_5))|Для отдела маркетинга Яндекс.Афиши расcчитал основные бизнес метрики по продукту, продажам и маркетингу в разбивках по времени и источникам трафика и проанализировал эффективность инвестиций по этим источникам трафика.|*pandas*, *seaborn*, *Matplotlib*, *numpy*, *datetime*.|
|[Data Viz with Seaborn. Moscow public catering market.](Data_viz_seaborn-Moscow_restaurant_market_(project_7))|Проанализировал открытые данные об объектах общественного питания города Москвы, выявил топ улиц по количеству заведений, узнал районы для этих улиц с помощью API Яндекс.Геокодер и дал рекомендации о районе и типе заведения инвесторам, желающим открыть кафе с официантами роботами.|*pandas*, *seaborn*, *Matplotlib*, *Plotly*, *numpy*, *re*, *Mystem*, *requests*, *BeautifulSoup*, *BytesIO*|
|[Tableau Dashboard for Yandex.Zen newsboard](Tableau_Dashboard_Yandex_Zen_(project_8))|Проанализировал разбивку событий по темам карточек и источников, выявил взаимосвязь между темами карточек и источников. Данные выгрузил с облачного сервера Yandex.Cloud при помощи SQLAlchemy. Для анализа построил дашборд в Tableau Public.|*pandas*, *SQLAlchemy*, *Tableau Public*|
|[ML Churn model for fitness network](ML_Churn_model_for_gym_(project_9))|Для моделирования оттока клиентов построил и обучил модели логистиской регрессии и случайного леса, оценил эффективность моделей с помощью метрик accuracy, presion и recall. Предварительно признаки были исследованы на линейную корреляцию, лишние отброшены. Затем применил кластеризацию при помощи матрицы расстояний и дендрограммы (библиотека skipy.cluster.hierarchy) а также кластеризацию алгоритмом K-Means. Сделал выводы по полученным результатам, дал рекомендации менеджементу.|*pandas*, *seaborn*, *Matplotlib*, *numpy*, *sklearn*, *skipy.cluster.hierarchy*|
|[Final Project A/B test](Project_Final_AB_test)|Проверил корректность проведения, а также проанализировал результат A/B теста для сравнения конверсий по событиям в интернет магазине после введения новой рекомендательной системы. Посмотрел на пересечение аудитории с конкурирующим тестом, выделил реальное количество участников теста. Построил воронку событий, провел исследовательский анализ данных, определил среднее число событий на пользователя в целом и по событиям. По итогам исследования графиков накопительной конверсии, а также после проведенных статистических тестов Манна-Уитни стало ясно, что результаты в контрольной группе существенно лучше, а потому изменения сайта не оправданы. |*pandas*, *matplotlib*, *seaborn*, *plotly*, *datetime*, *numpy*, *scipy*, *math*|
|[Final Project Bank Churn](Project_Final_Bank_Churn)|Для банка "Метанпром" составил портреты типичных пользователей, которые уходят и тех, которые остаются. Также были проведены два статистических теста: гипотеза о различии доходов по оттоку не подтвердилась, а гипотеза о различии долей ушедших клиентов среди лояльных и нелояльных подтвердилась. Предварительно был произведен анализ всех данных, построены необходимые графики для всех параметров в разбивке по оттоку и без нее. Дополнительно при помощи Tableau Public подготовил дашборд, отображающий распределения параметров возраст, доход и баланс с возможностью фильтрации по оттоку, а также с индикатором процента клиентов, использующих кредитные карты.|*pandas*, *seaborn*, *Matplotlib*, *numpy*, *scipy*, *math*, *Tableau Public*|


## Extras
В ходе обучения по рекомендации наставников выполнил упражнения по SQL на сайте sql-ex.ru. На самом сайте выполнял упражнения в PostgreSQL, той версии SQL, которой нас обучали в Яндекс.Практикуме, но в Google Colab эти же упражнения сделаны в SQLite 3 c незначительными естественными модификациями.  Вот ссылка на эти упражнения с моими решениями: https://colab.research.google.com/drive/1X5WgWLThI9p7zhhUkeMNxYKV4V5Gn35W?usp=sharing.

# 👋 Привет! Я Роман, Data Engineer

Я специализируюсь на построении масштабируемых ETL/ELT пайплайнов, проектировании хранилищ данных (DWH) и оптимизации высоконагруженных систем обработки данных.

## 🛠 Технологический стек

* **Languages:** Python (Asyncio, Multiprocessing), SQL (Advanced), Bash.
* **Data Processing:** Apache Spark (Optimization, Skew handling), Pandas, NumPy.
* **Orchestration:** Apache Airflow (Dynamic DAGs, Datasets, Custom Operators).
* **Databases & Storage:** PostgreSQL, MongoDB, ClickHouse, Snowflake, Delta Lake.
* **Data Modeling:** Data Vault 2.0, Star/Snowflake Schema, Medallion Architecture.
* **Tools:** dbt (Core/Cloud), Docker & Compose, Kafka (Schema Registry, Idempotency).
* **DevOps:** CI/CD, Git, Pre-commit hooks, SQLFluff.

---

## 🏛 Избранные проекты

### [DataVault](https://github.com/Roman197619/datavault)
**Инфраструктурный шаблон DWH.** Реализация современной архитектуры хранилища данных.
* **Стек:** Airflow, dbt, Snowflake, Docker.
* **Ключевая особенность:** Демонстрация методологии **Data Vault 2.0** и **медальной архитектуры** (Bronze -> Silver -> Gold). Настроены автоматические тесты качества данных (DQ) и CI/CD пайплайны.

### [Airflow + MongoDB Pipeline](https://github.com/Roman197619/airflow_mongo)
**Dataset-aware ETL пайплайн.**
Автоматизированная система обработки отзывов из Google Play.
* **Стек:** Airflow, MongoDB, Pandas, Docker.
* **Ключевая особенность:** Использование **Data-aware scheduling** (Airflow Datasets). Реализован сенсор файлов, очистка данных и загрузка в NoSQL хранилище с оптимизированными индексами.

### [BOM Analysis (Python & SQL)](https://github.com/Roman197619/numpy_pandas)
**Алгоритмическая задача: Разузлование спецификаций.**
Решение классической промышленной задачи Bill of Materials (BOM).
* **Стек:** Python (Pandas/NumPy), PostgreSQL (Recursive CTE).
* **Ключевая особенность:** Сравнение двух подходов к обходу иерархических структур — рекурсивные запросы в БД против итеративной обработки в памяти через Pandas.

### [JDF Test Pipeline](https://github.com/Roman197619/JDF_test)
**ELT пайплайн для ClickHouse.**
* **Стек:** ClickHouse, dbt, Python.
* **Ключевая особенность:** Реализация быстрой загрузки данных в колончатую СУБД с последующей трансформацией через dbt.

---

## 📚 Теоретический бэкграунд

Я глубоко понимаю внутреннее устройство используемых технологий:
* **Архитектура:** Lakehouse (Delta/Iceberg), выбор между Inmon и Kimball, проектирование OLAP-кубов.
* **Spark Internals:** Управление памятью, борьба со Spill и OOM, оптимизация джойнов, понимание планов выполнения (Physical/Logical plans).
* **Database Theory:** Уровни изоляции ACID, CAP-теорема, нормализация vs денормализация, стратегии шардирования и партиционирования.
* **Системы обмена сообщениями:** Гарантии доставки в Kafka, работа с Dead Letter Queues, Schema Registry.
* **Data Governance:** Внедрение RBAC, контроль качества данных (Great Expectations/dbt tests) и обеспечение Usability данных.

---

## 📫 Как со мной связаться

* **Telegram:** [@Roman197619](https://t.me/Roman197619)

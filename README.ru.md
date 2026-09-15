# Артур Мухутдинов

**Tech Lead · Потоковые платформы данных · Java / Flink / Kubernetes**

Создаю системы, с помощью которых дата-инженеры загружают данные и сопровождают интеграции. В **X5 Tech** спроектировал и реализовал стриминговую основу корпоративной платформы. Сейчас руковожу командой её развития и продолжаю писать код.

Сейчас платформа обслуживает **200+ production-пайплайнов**, обрабатывающих **около 20 ТБ за семь дней**. На предыдущем этапе развития сократил выделенные CPU **с 450 до 250 ядер — на 44%**.

[Резюме на русском (PDF)](resume/Artur_Mukhutdinov_CV_RU.pdf) · [CV in English (PDF)](resume/Artur_Mukhutdinov_CV_EN.pdf) · [Telegram](https://t.me/CatOrLeader) · [Почта](mailto:arturmuxutdinov@gmail.com)

[English profile](README.md)

## Что я создаю

- **Стриминговые платформы:** архитектуру на Apache Flink, модель развёртывания и эксплуатации в Kubernetes для нескольких Data Hubs.
- **Инструменты для дата-инженеров:** переиспользуемые загрузчики и платформу настройки, развёртывания и сопровождения потоковых пайплайнов с интеграцией GitLab CI/CD и HashiCorp Vault.
- **CDC и lakehouse-интеграции:** захват изменений PostgreSQL, эволюцию схем, сигнальные таблицы, загрузку Kafka → Iceberg и восстановление потоков с checkpoint/savepoint.
- **Эксплуатацию:** распределение ресурсов, работу с секретами и сертификатами, мониторинг и диагностику Flink, Kubernetes и связанных сервисов.

С апреля 2026 года руковожу четырьмя инженерами, развивающими стриминговые загрузчики, backend-сервисы, инфраструктуру и мониторинг. Работаю с пользователями платформы и продакт-менеджерами, определяю приоритеты, провожу архитектурные ревью, развиваю сотрудников и организую поставку изменений.

## Вклад в open source

Мои изменения приняты в **Apache Amoro** и **Apache Flink CDC**:

- Обработка UUID при компакции Iceberg-таблиц в Amoro.
- Рекурсивный поиск JAR-файлов для classpath при развёртывании Flink CDC.

Также разрабатывал внутренние расширения PostgreSQL CDC для эволюции схем и работы с сигнальными таблицами. Доступные к обсуждению технические подробности и ссылки на изменения — по запросу.

## Публичные проекты

- [**titan-pulse**](https://github.com/CatOrLeader/titan-pulse) — личный инфраструктурный стенд для streaming, в разработке: Flink Kubernetes Operator, мониторинг и локальный стек с Kafka, MinIO, Iceberg REST и Trino на Helm.
- [**Tinkoff Link Tracker**](https://github.com/CatOrLeader/Tinkoff_Link_Tracker) — учебный Java backend-проект на основе шаблона курса: уведомления в Telegram об обновлениях отслеживаемых ссылок; Spring Boot, PostgreSQL, опциональный Kafka и Docker Compose.

## Технологии

**Основные:** Java, Python, SQL · Apache Flink, Flink CDC, Kafka, Iceberg, Amoro, PostgreSQL.

**Платформа:** Kubernetes, Docker, Helm, GitLab CI/CD, HashiCorp Vault, MinIO, Grafana, Prometheus.

**Backend:** Spring Boot, JUnit, Testcontainers. Дополнительный опыт: Apache NiFi и разработка SAP HANA CDC.

## Работа и сотрудничество

Рассматриваю роли **Senior Data Platform / Software Engineer** и **Tech Lead** с сохранением не менее 40% времени на написание кода. Интересны удалённая работа, позиции в России, релокация при поддержке работодателя, контрактная и частичная занятость.

Окончил Университет Иннополис в 2026 году. Русский — родной; английский — B2, самооценка.

Связаться: [Telegram](https://t.me/CatOrLeader) или [почта](mailto:arturmuxutdinov@gmail.com).

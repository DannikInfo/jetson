# METIDA MLops - Machine Learning Operations
В репозитории хранится описание проекта

Децентрализованная система автоматизации процессов машинного обучения

## Модули
### Клиент
- <a href="/kozlovskiy-di/METIDAClient">Detector</a> (с++?, доработка)
- <a href="/kozlovskiy-di/dataCacher">DataCacher</a> (Go, поддержка)  
- Включает: все универсальные
### Кластер
- ClusterBroker (Базируется на Kubernetes)
- <a href="/kozlovskiy-di/DataProcessor">DataProcessor</a> (?, проектирование)
- <a href="/kozlovskiy-di/metida-Learner">Learner</a> (?, проектирование)
- <a href="/kozlovskiy-di/metida-Tester">Tester</a> (?, проектирование)  
- <a href="/kozlovskiy-di/modelCacher">ModelCacher</a> (?, Проектирование стоит использовать DVC)  
- Включает: все универсальные
### Универсальные
- <a href="/kozlovskiy-di/SQLCacher">SQLCacher</a> (с++, поддержка)  
- <a href="/kozlovskiy-di/metida-Telemetry">Telemetry</a> (с++, разработка ведется)
### Веб
- <a href="/kozlovskiy-di/front-end">Frontend</a> (Control/stats) (ReactJS, разработка ведется)
- <a href="/kozlovskiy-di/METIDA-back-end">Backend</a> (Control/stats) (Go, разработка ведется)
- Storage
- PostgreSQL
- CI/CD

## Библиотеки
- <a href="/kozlovskiy-di/tinyLogger">tinyLogger</a> (с++, поддержка)
- <a href="/kozlovskiy-di/tinyConfig">tinyConfig</a> (с++, доработка и улучшения)
- <a href="/kozlovskiy-di/tinyUtils">tinyUtils</a> (с++, разработка ведется)
# Отчет по лабораторной работе №3

> **University:** [ITMO University](https://itmo.ru)
> 
> **Faculty:** [FTMI] (https://ftmi.itmo.ru/)
> 
> **Course:** [Введение в веб технологии] (https://itmo-ict-faculty.github.io/introduction-in-web-tech/)
> 
> **Year:** 2026/2027
> 
> **Group:** U4225
> 
> **Author:** Seregin Artem Aleksandrovich
> 
> **Lab:** Lab3
> 
> **Date of create:** 05.09.2026
> 
> **Date of finished:** _Ожидается выполнение_

---

## # 1. Создание конфигурации Prometheus

Сначала создал папку prometheus для конфигурации, а потом создал файл prometheus/prometheus.yml с содержимым global: scrape_interval: 15s.

<img width="785" height="249" alt="image" src="https://github.com/user-attachments/assets/8d899848-791d-4e67-8c76-af9b2505010c" />

---

## # 2. Запуск Node Exporter

Запустил контейнер Node Exporter для сбора системных метрик, после чего проверил его на http://localhost:9100/metrics.

<img width="758" height="629" alt="image" src="https://github.com/user-attachments/assets/e5a95cdb-3a9f-4214-b0ca-7ece378b1b61" />
<img width="1863" height="779" alt="image" src="https://github.com/user-attachments/assets/13639766-ed9f-4216-8a33-3493d23b87b7" />
<img width="1893" height="816" alt="image" src="https://github.com/user-attachments/assets/01f46d0b-1a67-47fb-9d6d-b247c5407227" />
<img width="1658" height="998" alt="image" src="https://github.com/user-attachments/assets/e3d72987-17d7-4338-8c0d-1fd9101c7d0e" />

---

## # 3. Запуск Prometheus

**Prometheus** - приложение, которое отвечает за сбор метрик. Для их визуализации позже будет запущено другое приложение - Grafana

Перед запуском был создан том для данных Prometheus, после чего создал общую сеть, для совместной работы Grafana и Prometheus. Потом запустил контейнер Prometheus и в докере увидел работающий контейнер.

<img width="622" height="61" alt="image" src="https://github.com/user-attachments/assets/252c73db-c019-4f12-8aed-644267f6a62d" />
<img width="729" height="576" alt="image" src="https://github.com/user-attachments/assets/5f577b74-b660-4e98-89eb-992236bc6e71" />
<img width="1892" height="694" alt="image" src="https://github.com/user-attachments/assets/88abd109-332a-4873-ae4b-c68debeb4a89" />

---

## # 4. Запуск Grafana

Для визуализации метрик будем использовать **Grafana**. Для этого создал том и запустил контейнер Grafana

<img width="768" height="505" alt="image" src="https://github.com/user-attachments/assets/cb9b416b-adef-4ad3-944b-d7a726e58bce" />
<img width="1895" height="802" alt="image" src="https://github.com/user-attachments/assets/295abdeb-259b-410b-b42a-f380bdbaee73" />

---

## # 5. Настройка Grafana и тестирование системы

После запусков всех нужных контейнеров нужно было для Grafana добавить источник Prometheus через настройки и добавить дашборды по отслеживанию метрик:

>CPU

>Память

>Диск


<img width="1414" height="117" alt="image" src="https://github.com/user-attachments/assets/dacae966-89b9-4b3e-a58f-6c0d5218ff6b" />
<img width="1919" height="513" alt="image" src="https://github.com/user-attachments/assets/0b4dcfc8-8df4-4644-873c-1af2477651db" />
<img width="1913" height="810" alt="image" src="https://github.com/user-attachments/assets/751d4646-70b9-4057-887f-df23feb72aad" />


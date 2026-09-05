# Отчет по лабораторной работе №2

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
> **Lab:** Lab2
> 
> **Date of create:** 05.09.2026
> 
> **Date of finished:** _Ожидается выполнение_

---


## # 1. Подготовка проекта

Для начала в папку lab2 были перемещены созданные ранее файлы из первой лабораторной работы (app.py, requirements.txt, Dockerfile). После чего создал аккаунт в Docker Hub и создал свой репозиторий my-flask-app.

<img width="1568" height="383" alt="image" src="https://github.com/user-attachments/assets/3bb03745-29c8-407e-adfb-a605656a6f2f" />
<img width="1210" height="300" alt="image" src="https://github.com/user-attachments/assets/842c5c4b-a2f6-4164-b587-ff04d413faaf" />

---

## # 2. Настройка GitHub Actions

В своем локальном репозитории создал папку ".github/workflows/", после чего проверил, что папка успешно создалась. В новой папке создал файл "docker-build.yml" с пайплайном, который включал в себя шаги для робота GitHub Actions. И в конце проверил, что файл был успешно создан.

<img width="661" height="976" alt="image" src="https://github.com/user-attachments/assets/7aba70ff-4f6e-454c-8ee3-3ed57cbc27a0" />

---

## # 3. Настройка секретов

После шага 2 было необходимо добавить секреты в гит хаб, чтобы не передавать конфиденциальные данные в рабочих файлах.

<img width="1558" height="860" alt="image" src="https://github.com/user-attachments/assets/811603e2-324a-4e80-bdfd-3fa3be019add" />

---

## # 4. Тестирование пайплайна

На данном этапе нужно было закоммитить доработку и запушить ее в main ветку. После чего можно увидеть зеленую галочку на своем репозитории, что говорит об успешном пайплане, а также появился тег в Docker Hub.

<img width="1147" height="70" alt="image" src="https://github.com/user-attachments/assets/7d4c472a-adcf-4cfd-bc30-fb3c85834bdb" />
<img width="649" height="303" alt="image" src="https://github.com/user-attachments/assets/8a2a1d43-ec60-4b90-9f57-555923814d7e" />
<img width="1310" height="562" alt="image" src="https://github.com/user-attachments/assets/0bd007d0-2246-4ccf-9d90-96920f708364" />
<img width="1273" height="617" alt="image" src="https://github.com/user-attachments/assets/04debed8-4258-4459-b09d-8a6cdb785786" />



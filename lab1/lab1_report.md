# Отчет по лабораторной работе №1

> **University:** [ITMO University](https://itmo.ru)
> **Faculty:** [FTMI] (https://ftmi.itmo.ru/)
> **Course:** [Введение в веб технологии] (https://itmo-ict-faculty.github.io/introduction-in-web-tech/)
> **Year:** 2026/2027
> **Group:** U4225
> **Author:** Seregin Artem Aleksandрович
> **Lab:** Lab1
> **Date of create:** 04.09.2026
> **Date of finished:** _Ожидается выполнение_

---


### #1. Пример использования команд Docker

На **рисунке 1** представлен пример работы со следующими командами:

* **`docker --version`** — проверяет, установлен ли Docker на компьютере, и выводит его текущую версию.
* **`docker run hello-world`** — ищет на компьютере тестовый образ `hello-world`. Если его нет, скачивает его из интернета (с Docker Hub), запускает внутри контейнера, выводит приветственный текст и завершает работу. *(Пример работы самого контейнера в докере показан на **рисунке 2**)*.
* **`docker images`** — выводит список всех образов (шаблонов для контейнеров), которые уже скачаны и сохранены на вашем жестком диске.
* **`docker ps`** — показывает список только тех контейнеров, которые работают в данный момент.
* **`docker ps -a`** — показывает вообще все контейнеры на компьютере (и те, которые работают сейчас, и те, которые уже остановились или завершили свою работу).



<img width="1889" height="834" alt="image" src="https://github.com/user-attachments/assets/424d7cfe-4912-4513-ad82-595dd3741a28" />
<center>рисунок 1 - первые команды в докере</center>

<img width="1543" height="235" alt="image" src="https://github.com/user-attachments/assets/3e5d8edf-42fd-42f6-8000-1c6aaeb8fe75" />
<center>рисунок 2 - контейнер в докере "hello-world"</center>

### #2. Образ Ubuntu

На **рисунке 3 и 4** пример скачивание и запуска образа Ubuntu, после чего была выполнена команда для проверки установки образа.

<img width="971" height="715" alt="image" src="https://github.com/user-attachments/assets/908021a8-f5e8-4407-b803-2e7b89ba8853" />
рисунок 3 - скачивание и запуск образа Ubuntu

<img width="1811" height="84" alt="image" src="https://github.com/user-attachments/assets/00a76170-37f6-4491-acd0-4ca13010e08d" />
рисунок 4 - проверка установки Ubuntu

### #3. Запуск веб-сервера

На рисунке 5 изображены команды по запуску контейнера с nginx, в результате которого получил веб-страничку (рисунок 6). Также запускал команду, чтобы проверить логи, где можно увидеть успешный метод по просмотру веб-странички. А также запускал команду, чтобы проверить версию nginx.

<img width="1491" height="934" alt="image" src="https://github.com/user-attachments/assets/490a5f2a-2e5c-4486-b276-2f459548c865" />
рисунок 5 - запуск, проверка логов и управление контейнером с консоли

<img width="1542" height="272" alt="image" src="https://github.com/user-attachments/assets/496768d7-5ba0-4d0e-a7b1-c7f8c3c9fd18" />
рисунок 6 - запущенный контейнер веб-сервера в докере

<img width="1394" height="421" alt="image" src="https://github.com/user-attachments/assets/f1eef521-8919-4774-8924-4260b6e24f2e" />
рисунок 7 - веб-страница локального хоста




University: [ITMO University](https://itmo.ru/ru/)

Faculty: [FTMI](https://itmo.ru/ru/viewfaculty/87/fakultet_tehnologicheskogo_menedzhmenta_i_innovaciy.htm)

Course: [Введение в веб технологии](https://itmo-ict-faculty.github.io/introduction-in-web-tech/)

Year: 2026/2027

Group: U4225

Author: Seregin Artem Aleksandrovich

Lab: Lab1

Date of create: 04.09.2026

Date of finished: 

### #1. Пример использования команд Docker

На **рисунке 1** представлен пример работы со следующими командами:

* **`docker --version`** — проверяет, установлен ли Docker на компьютере, и выводит его текущую версию.
* **`docker run hello-world`** — ищет на компьютере тестовый образ `hello-world`. Если его нет, скачивает его из интернета (с Docker Hub), запускает внутри контейнера, выводит приветственный текст и завершает работу. *(Пример работы самого контейнера в докере показан на **рисунке 2**)*.
* **`docker images`** — выводит список всех образов (шаблонов для контейнеров), которые уже скачаны и сохранены на вашем жестком диске.
* **`docker ps`** — показывает список только тех контейнеров, которые работают в данный момент.
* **`docker ps -a`** — показывает вообще все контейнеры на компьютере (и те, которые работают сейчас, и те, которые уже остановились или завершили свою работу).



<img width="1889" height="834" alt="image" src="https://github.com/user-attachments/assets/424d7cfe-4912-4513-ad82-595dd3741a28" />
<center>рисунок 1</center>

<img width="1543" height="235" alt="image" src="https://github.com/user-attachments/assets/3e5d8edf-42fd-42f6-8000-1c6aaeb8fe75" />
<center>рисунок 2</center>


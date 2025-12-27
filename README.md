## Docker: создание и управление контейнерами

## 1. Цель работы

Целью работы является изучение работы с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.

1. Установил Docker destop
2. Создали рабочую директорию
   
  <img width="974" height="98" alt="image" src="https://github.com/user-attachments/assets/203aa93f-7c03-4ae2-8bbe-de0c9697a761" />

4. В этой же директории создали Dockerfile

<img width="974" height="481" alt="image" src="https://github.com/user-attachments/assets/fbf0369b-a1c7-461e-bbe1-328f7140e58d" />

5. Создали образ Docker на основе созданного Dockerfile и проверили, что образ появился в системе 

<img width="974" height="481" alt="image" src="https://github.com/user-attachments/assets/f309d85a-8332-44e9-b5e9-2fa222d962ec" />


5. Запустили контейнер из собранного образа

   <img width="974" height="189" alt="image" src="https://github.com/user-attachments/assets/a0ac1272-29b3-4788-91fc-e8b2b48bda28" />

   Открыли веб-браузер и перешли по адресу http://localhost:1234/

<img width="780" height="295" alt="image" src="https://github.com/user-attachments/assets/697065fc-2326-4a2f-a845-01db9225e5e3" />


6. В той же директории создали файл docker-compose.yml для развертывания этого приложения вместе с базой данных PostgreSQL, предусмотреd проброс порта 1234, а также возможность расширения или подключения сторонних сервисов при необходимости

   <img width="974" height="695" alt="image" src="https://github.com/user-attachments/assets/a9e3d610-afc5-4f76-a015-a8a409e8db56" />

7. Далее запускаем стек через docker-copmose 

Итог

  <img width="822" height="423" alt="image" src="https://github.com/user-attachments/assets/e6af19b8-c413-468f-b373-829f6b7910b3" />


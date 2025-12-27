Docker: создание и управление контейнерами

## 1. Цель работы

Целью работы является изучение работы с программным обеспечением Docker для автоматизации развертывания и управления приложениями в средах с поддержкой контейнеризации.

1. установил Docker destop
2. Создали рабочую директорию
  <img width="974" height="98" alt="image" src="https://github.com/user-attachments/assets/203aa93f-7c03-4ae2-8bbe-de0c9697a761" />

3. В этой же директории создали Dockerfile

<img width="974" height="481" alt="image" src="https://github.com/user-attachments/assets/fbf0369b-a1c7-461e-bbe1-328f7140e58d" />


4. Создали образ Docker на основе созданного Dockerfile и проверили, что образ появился в системе 

<img width="974" height="481" alt="image" src="https://github.com/user-attachments/assets/f309d85a-8332-44e9-b5e9-2fa222d962ec" />


5. Запустили контейнер из собранного образа
   Открыли веб-браузер и перешли по адресу http://localhost:1234/

<img width="974" height="189" alt="image" src="https://github.com/user-attachments/assets/54cb9518-228d-4954-a612-304ce8986672" />


6. В той же директории создали файл docker-compose.yml для развертывания этого приложения вместе с базой данных PostgreSQL, предусмотреd проброс порта 1234, а также возможность расширения или подключения сторонних сервисов при необходимости

   <img width="974" height="695" alt="image" src="https://github.com/user-attachments/assets/a9e3d610-afc5-4f76-a015-a8a409e8db56" />



7. Далее запускаем стек через docker-copmose 


Итог

  <img width="780" height="295" alt="image" src="https://github.com/user-attachments/assets/fc67df0c-8766-41a1-bc3d-9d3076b46079" />

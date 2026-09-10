University: ITMO University  
Faculty: FTMI  
Course: Введение в веб технологии  
Year: 2026/2027  
Group: U4225  
Author: Soldatov Egor  
Lab: Lab1  

**1. Установка Docker** 
Была проверена установка Docker и запущен тестовый контейнер hello-world.  
<img width="665" height="222" alt="image" src="https://github.com/user-attachments/assets/7f8aef4f-754f-4ece-94dc-5f5a72dbb10c" />  
<img width="879" height="625" alt="image" src="https://github.com/user-attachments/assets/8d6fd429-2940-41f5-8d9f-e38e07d6414e" />  
<img width="561" height="156" alt="image" src="https://github.com/user-attachments/assets/2c3d2638-10b0-4e2f-b535-cd63522794ef" />  
<img width="968" height="258" alt="image" src="https://github.com/user-attachments/assets/190f156d-646a-4c42-b57b-b151e9e6e615" />  
Docker установлен корректно, базовые команды работают.  

**2. Работа с готовыми образами**  
Был скачан образ Ubuntu, запущен интерактивный контейнер, внутри которого был установлен пакет curl.  
<img width="934" height="820" alt="image" src="https://github.com/user-attachments/assets/87bb20b2-6b1d-46aa-98be-1ad668718b3a" />  
<img width="1045" height="186" alt="image" src="https://github.com/user-attachments/assets/3ad1cf8c-00c2-4baa-a00f-548da026e2fd" />  
Таким образом, был опробован процесс скачивания образов из Docker Hub и работы внутри контейнеров.  

**3. Запуск веб-сервера**  
Был запущен контейнер с nginx на порту 8080. Веб-сервер успешно доступен через браузер. Были изучены логи и выполнен вход в работающий контейнер.  
<img width="771" height="352" alt="image" src="https://github.com/user-attachments/assets/a6562cc9-b9a1-42f4-8e97-b6e02094d2ed" />  
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a719084a-cbd9-4b70-ad78-a675e2e3d9fa" />  
<img width="1049" height="771" alt="image" src="https://github.com/user-attachments/assets/ec89c09e-3415-49bb-9255-d10f5339dc41" />  
<img width="401" height="106" alt="image" src="https://github.com/user-attachments/assets/43d9914a-dca1-4128-926a-8a42b25fc2ac" />  

**4. Управление контейнерами**  
Были изучены команды для остановки, запуска и удаления контейнеров и образов.  
<img width="1046" height="168" alt="image" src="https://github.com/user-attachments/assets/76284017-aac5-438e-a18c-f3cc63039855" />  
<img width="1920" height="1016" alt="image" src="https://github.com/user-attachments/assets/3d2cadba-9c3c-4d20-9743-1a439bc997f1" />  
<img width="361" height="60" alt="image" src="https://github.com/user-attachments/assets/34ef3839-4eaf-4f3a-ae92-04c07d04dc2b" />  
<img width="1920" height="1025" alt="image" src="https://github.com/user-attachments/assets/94935f64-22ed-4807-8de5-62605b0b6495" />  
<img width="1045" height="461" alt="image" src="https://github.com/user-attachments/assets/98b43187-c99e-4fb4-bf0f-e12397e3496e" />  

**5. Работа с томами**  
Был создан том, подключён к контейнеру, в нём создан файл. После удаления контейнера и создания нового с тем же томом файл сохранился.  
<img width="749" height="382" alt="image" src="https://github.com/user-attachments/assets/42e2558f-6cd3-489b-ac62-fc8796c7a7b1" />  

**Вывод**  
В ходе лабораторной работы были изучены основы контейнеризации с использованием Docker. Освоены базовые команды для работы с образами и контейнерами, запуск веб-приложений, управление жизненным циклом контейнеров и работа с томами для сохранения данных.






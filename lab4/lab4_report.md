University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)  
Year: 2023/2024  
Group: K4111c  
Author: Kachmazov Artur<br>
Lab: Lab4  
Date of create: 06.11.2023  
Date of finished:

**1. Запуск minikube с подключенным плагином `calico` и двумя нодами командой `minikube start --network-plugin=cni --cni=calico --nodes 2 --driver=docker --no-vtx-check`.** <br>

![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/3f913ef6-3b86-48ef-9218-642acfacc588) <br>

Список запущенных нодов: <br>

![image](https://github.com/Mrtrieu69/2023_2024-introduction_to_distributed_technologies-k4111c-trieu_t_m/assets/87965299/6df865b0-fdcb-4089-970f-be4189ccc33b)<br>

**2. Установка лейблов для нод.**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/309514d0-74d4-4bdf-8770-59138e73871a) <br>

**3. Создание файла манифеста для назначения пула IP узлам на основе их меток.**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/7bb2d706-08ee-4a89-8e3f-f97255224258) <br>

При выполнении файла получен список ippool.<br> 
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/1edba54a-fdc1-4dd3-b534-bf70e16205d0) <br>

**4. Создание и запуск файла для деплоя приложения** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/9008646d-230f-4cb0-b224-5b28929cb01f) <br>

![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/001be6e1-51d4-480f-9a22-8f57c55aa4fb) <br>

5. Создание сервиса для получения доступа к сайту.<br> 
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/0cd6a7f7-887a-419b-a6aa-8306143215a5) <br>

![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/da507047-f32b-43a7-a3b7-45f70844a2c4) <br>

6. Авторизация через аккаунт master и пинг второого пода.<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/7dc81946-1a37-4553-8734-5bae678d671b) <br>

8. Схема<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/2f900342-9a76-4a93-97c6-21f478edd148) <br>





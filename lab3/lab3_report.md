University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)  
Year: 2023/2024  
Group: K4111c  
Author: Kachmazov Artur<br>
Lab: Lab3  
Date of create: 01.11.2023  
Date of finished:

**1. Создаём ConfigMap со значениями переменных.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/f5b2774f-64a8-4125-9a21-86d2388bb5d6) <br>

**2. Создаём ReplicaSet, в который передаём указанные переменные.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/07eb5a44-efac-4b42-a78c-c8d03a7df0ed) <br>

**3. Запускаем файл yaml для создания replicaset**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/d98530e3-f299-49aa-9803-1ef8b49a9701) <br>

**4. Запуск сервера комендой `kubectl expose deployment web-deployment --type=NodePort --port=3000 -n reactapp -n secretapp`**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/d9effa1d-d8ef-4efd-ae8b-2cf68a85942a) <br>

**5. Открытие доступа к контайнеру через port 31442**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/ac83b30e-541c-4083-89ef-6804cd79a9c4) <br>

**6. Запуск ingress.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/35ffbf81-ae01-4dab-b83e-23f19fad2115) <br>

**7. Создание сертификата** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/d3b56d3c-373c-4cab-9b9a-e8c5a43eca5c) <br>

**8. Импорт сертификата в кластер.**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/ecca4f5d-d05d-4ade-8a1f-93c3d5d297ad) <br>

**9. Создание и запуск файла `ingress.yaml`.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/95806020-adc9-4f88-8dc5-913d39fb6013) <br>

![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/5518b421-32ae-49ba-9c83-538cc09063ab) <br>

**10. Редактирование файл хостов: включение в него имени текущего хоста `secretapp.info`.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/df7dbb35-4ddf-46e7-be26-692e0216e5c8) <br>

**11. Открытие доступа к приложению через браузер, с использованием имени хоста `edu.info`.** <br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/c98633ea-1429-4520-b2f2-5e833d53828f) <br>

**12. Сертификат.**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/1a505672-0049-4430-86e7-a3fbcfc8de70) <br>

**13. Схема.**<br>
![image](https://github.com/KachmaZ/2022_2023-introduction_to_distributed_technologies-k4112--kachmazov_a_a/assets/59313334/759de2f7-207b-45e7-b5df-66dfd90f069e)









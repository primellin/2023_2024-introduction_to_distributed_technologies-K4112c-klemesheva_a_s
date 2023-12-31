University: [ITMO University](https://itmo.ru/ru/)  
Faculty: [FICT](https://fict.itmo.ru)  
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)  
Year: 2023/2024  
Group: K4112c  
Author: Klemesheva Anastasia Sergeevna  
Lab: Lab1  
Date of create: 01.10.2023  
Date of finished: 05.10.2023  

---

1) Запуск minikube:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/e6449757-db8d-4fb4-9060-a6a60a0ddd54)

2) Манифест для развёртывания Pod:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_s/assets/88944945/4bf53747-0944-4917-9e02-15a84b7ae8ef)

3) Развёртывание Pod:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/0b2bcf95-62f4-4fb1-943c-185f39858db6)

4) Создание сервиса для доступа к контейнеру:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/0e53b2b6-b04f-42ad-bcb3-3504cdfd3cf0)

5) Получение доступа к приложению в кластере:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/fbf5effc-5c13-453d-b063-4a7cf5a8af9b)

6) Прерход по ссылке http://localhost:8200:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/08075425-2fc4-4fe5-a598-97cd0c4fd6b9)

7) Просмотр логов Pod-а, чтобы найти токен для входа:


   ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/e3143c7e-453e-4f69-898d-d8469fad16bd)
 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/0eebff80-c387-499a-a762-336f8368b303)

8) Заходим:

 ![image](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_n/assets/88944945/5bd60515-119c-43d7-8f49-8f48135348a1)


Схема:  

![схема drawio (1)](https://github.com/primellin/2023_2024-introduction_to_distributed_technologies-K4112c-klemesheva_a_s/assets/88944945/eff369e0-a67e-4843-960e-6d9b0c0f204b)


Ответы на вопросы: 1. Был развернут кластер, затем по написанному манифесту в нем был развернут Pod с контейнером, запущенным из образа vault. Чтобы получить доступ к нему извне, был создан сервис, с его помощью мы включили маршрутизацию трафика с хост-машины (нашего ПК). 2. Токен в логах Pod-а.



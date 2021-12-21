# Создание и тестирование приложения для работы с API 
---

Перейдя на сайт Flasgger, я стала изучать API для сайта PetFriends. Указанные ниже функции я реализовала на Python 3.8 (они находятся в папке API): 

<img width="1438" alt="Снимок экрана 2021-12-21 в 13 59 03" src="https://user-images.githubusercontent.com/72348256/146919706-43908d56-9440-4ad5-83f9-b4c6a39b19f5.png">

Код каждой функции вы можете увидеть в директории **API**.

Результаты функций:

GET API key:

<img width="824" alt="Снимок экрана 2021-12-21 в 14 19 52" src="https://user-images.githubusercontent.com/72348256/146922183-ef45900e-3e4c-486b-a138-57862d4153fd.png">

POST new pet:

<img width="1348" alt="Снимок экрана 2021-12-21 в 14 23 41" src="https://user-images.githubusercontent.com/72348256/146922263-f75cf72f-dcb3-4455-bd34-0910c153f7a2.png">

GET pet list:

<img width="1357" alt="Снимок экрана 2021-12-21 в 14 24 22" src="https://user-images.githubusercontent.com/72348256/146922361-1ea4b4d9-88b5-45fb-a161-133032449bb6.png">

POST create pet simple:

<img width="855" alt="Снимок экрана 2021-12-21 в 14 30 38" src="https://user-images.githubusercontent.com/72348256/146923192-06355c3d-a6ef-4ca6-8968-b33430caa63c.png">

PUT info:

<img width="1361" alt="Снимок экрана 2021-12-21 в 14 28 29" src="https://user-images.githubusercontent.com/72348256/146922870-8f4ab560-ba17-4929-a036-3a3aee31e2df.png">

DELETE pet:

<img width="1355" alt="Снимок экрана 2021-12-21 в 14 28 20" src="https://user-images.githubusercontent.com/72348256/146922909-1ce4a416-3e82-4d2a-bfb1-d8e09216cf90.png">


После выполнения всех функций на Python с помощью библиотеки "requests", я начала их тестировать. В условии задания сказано, что мы должны использовать и фикстуры, и параметризацию. Фикстуры я буду использовать для всех функций, а параметризация подойдет для функции "POST".

Параметризация для функции POST: 

<img width="927" alt="Снимок экрана 2021-12-21 в 13 16 10" src="https://user-images.githubusercontent.com/72348256/146920604-443b67ab-621a-4209-a457-379e3619521e.png">

В параметрах указаны не только положительные, но и отрицательные кейсы, отмеченные как marks=pytest.mark.xfail

<img width="722" alt="Снимок экрана 2021-12-21 в 13 56 25" src="https://user-images.githubusercontent.com/72348256/146920628-daf8d665-5b5c-4aa9-97fb-ec35aa387f53.png">

Фикстура для удаления питомца: 

<img width="418" alt="Снимок экрана 2021-12-21 в 13 51 45" src="https://user-images.githubusercontent.com/72348256/146920767-a0b771ea-0c0d-4c36-8edf-841bbf59ac4d.png">


# Итоги
В процессе работы над этим заданием я изучила и создала простые функции API, а также протестировала их несколькими методами.












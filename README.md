<h1 align="center">Примеры простых запросов в Postman
<img src="https://yt3.ggpht.com/ytc/AKedOLQIA5bGUpBddHevyezEKLDniAsAnPtMQaXuOtwOOQ=s900-c-k-c0x00ffffff-no-rj" height="32"/>

# 1.Создание учетной записи пользователя:
![Create user](https://user-images.githubusercontent.com/108890950/182124046-bd5e73de-514e-4f35-bb7f-7fd5c5a2fb8a.JPG)

# 2. Удаление учетной записи пользователя:
![Delete user](https://user-images.githubusercontent.com/108890950/182124244-e4750d59-54de-4843-8b4c-db9d5cfd2ab6.JPG)

# 3. Вывод информации по всем пользователям:
![Get all users](https://user-images.githubusercontent.com/108890950/182124433-28204b3e-6afc-45fc-9b40-3c8fd1c0ef5f.JPG)

 # 4. Вывод инофрмации по одному пользователю:
 ![Get user](https://user-images.githubusercontent.com/108890950/182124875-28b7f9a8-7c08-457c-9ad9-380311f3a53a.JPG)

<h1 align="center">Примеры найденных багов при использовании запросов в Postman
<img src="https://yt3.ggpht.com/ytc/AKedOLQIA5bGUpBddHevyezEKLDniAsAnPtMQaXuOtwOOQ=s900-c-k-c0x00ffffff-no-rj" height="32"/>

# 1. Имя и фамилия пользователя имеет ограничение в 30 символов
![Баг Create символы ограничены до 30](https://user-images.githubusercontent.com/108890950/182127491-28da5c08-2bb0-4439-aa02-9b2922c46428.JPG)

# 2. Возможность при редактировании пользователя сохранить имя и фамилию из одного символа
![Баг PUT user (name 1 символ)](https://user-images.githubusercontent.com/108890950/182127601-0b657be4-2679-42fb-af91-a1119cf08c13.JPG)
  
# 3. Возможность при редактировании пользователя сохранить имя и фамилию из 60 символов
![Баг PUT user (name 60 символ)](https://user-images.githubusercontent.com/108890950/182128023-868e3d64-d9e5-4a87-95f8-d57402b04e3f.JPG)

# 4. Возможноcть изменения даты рождения пользователя на будущее время
![Баг PUT дата рождения в будущем](https://user-images.githubusercontent.com/108890950/182128115-b3c81aa6-4333-4190-b990-38858ca48c07.JPG)

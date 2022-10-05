##**инструкция**

#1. ПРОВЕРКА РАБОТАЕТ ЛИ

что бы проверить работает ли терминал,
заходим в "терминал" далее " создать терминал" 
и набираем git --version
если выдало строку, например,

PS D:\29 09> git version

git version 2.37.3.windows.1

PS D:\29 09> 

значит все ок.

#**2. идентификация**

Далее надо идентифитироваться в git:

git config --global user.name "Elena Forkunova"
и все запоминается
и email вводим:

git config --global user.email "forkelena@yandex.ru"

Как проверить мои данные, которые я ввела? 

вводим:
git config --global user.name
и выдается имя пользователя, например:

PS D:\29 09> git config --global user.name                       
Elena Forkunova
PS D:\29 09> 

#**3. СОЗДАЕМ репозиторий**

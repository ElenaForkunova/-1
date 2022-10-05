##**инструкция**

#1. ПРОВЕРКА РАБОТАЕТ ЛИ

что бы проверить работает ли терминал,
заходим в "терминал" далее " создать терминал" 
и набираем *git --version*
если выдало строку, например,

PS D:\29 09> git version

git version 2.37.3.windows.1

PS D:\29 09> 

значит все ок.

#**2. идентификация**

Далее надо идентифитироваться в git:

*git config --global user.name "Elena Forkunova"*
и все запоминается
и email вводим:

*git config --global user.email "forkelena@yandex.ru"*

Как проверить мои данные, которые я ввела? 

вводим:
*git config --global user.name*
и выдается имя пользователя, например:

PS D:\29 09> git config --global user.name                       
Elena Forkunova
PS D:\29 09> 

#**3. СОЗДАЕМ репозиторий**

Для того что бы инициализировать (СОЗДАТЬ) репозиторий, вводим:

*git init*

получаем:
PS D:\29 09> git init
Reinitialized existing Git repository in D:/29 09/.git/
PS D:\29 09>
  
и на компе появляется папка внутри 2909 с названием .git
это и есть доказательство работы.
Если нужно удалить репозиторий, то удаляем папку.

#**4. ЧТО ТЫ знаешь?**
а ты занешь, что то расскажет
 о репозитории - команда *git status*
на какой ветке мы стоим, есть ли комиты, и про файлы есть или нет, отслеживается или нет.

#**5. ОЧИЩЕНИЕ**

ТО БЫ ОЧИСТИТЬ ВСЕ КОМАНДЫ, КОТОРЫЕ БЫЛИ - ввести *clear* и все исчезнет.
# GIT

-------------------------------

## Основні команди

Створення репозиторію: 

    git init 

Додавання всіх файлів до індексу:

    git add .

Якщо потрібно додати до індексації окремий файл:

    git add <filename>

Переглянути статус файлів:
    
    git status

Створення коміту:

    git commit -m "commentar"

Завантаження віддаленого репозиторію на свій ПК:

    git clone <link_to_remote>

## Робота з гілками

Список всіх гілок:

    git branch

Перейменувати основну гілку (н-д з master в main):

    git branch -M main

Створити нову гілку і перейти в неї:
    
    git checkout -b <branch_name>

## Робота з віддаленими репозиторіями

Додавання віддаленого репозиторію:

    git remote add <remote_name> <remote_link>

_Наприклад:_
    
    git remote add origin git@github.com:Username/Project.git

Видалити зв'язок з віддаленим репозиторієм:

    git remote remove <remote_name>

Залити коміти з певної гілки на віддалений репозиторій:
    
    git push <remote_name> <branch_name>

_Наприклад:_ 
    
    git push origin main

Стягнути дані з віддаленого репозиторію:

    git pull <remote_name> <branch_name>

_Наприклад:_ 

    git pull origin main
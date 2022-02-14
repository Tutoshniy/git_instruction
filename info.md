# начало работы с репозиториями

создание репозиторий:

 >git init

 Если работаем с репозиторием в первый раз, нужно задать имя и почту пользователя:

 > git config --global user.name some_name

 > git config --global user.email some_mail@mail.com

 # Основные команды

 ##Добавление изменений

Для того, чтобы добавить файл, нужно:

> git add file_name

Чтобы зафиксировать добавленные файлы, нужно:

>git commit -m "Some message"

## Отсложеивание состояния репозитория

Состояние репозитория, проверить отслеживаемые файлы:

> git status

Разница между текущей версией и сохранениями:

>git diff

Показать историю комитов:

>git log

# Переход к прошлым коммитам

Чтобы перейти к комиту с номером commit_code:

>git checkout conmit_code (код коммита можно найти через git log)

Чтобы вернуться к прежнему состоянию:

> git checkout master

Добавление картинки или гифки:

![Мемдляподнятиянастроения](nitw_the_rock_raise_eyebrow_meme.gif)

## Работа с ветками

> git branch

>git branch branch_name

>git checkout branch_name

>git branch -d branch_name

>git merge branch_name
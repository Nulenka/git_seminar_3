# **Инструкция по работе с Git**

## What's Git?

![Git logo](images/git_logo.jpg)

~~Git description~~

## Local repository creation
Для того, чтобы создать (инит) локальный репозиторий, необходимо в терминале, находясь в папке проекта, набрать команду:

    git init
    
## Проверка остояния репозитория

Чтобы проверть состояние репозитория, используют команду:

    git status

## Adding of new commit

To add a new commit use:

    git add

## Commenting a new commit

To add some comment to the new commit use:

    git commit - m "text"

## Коммит всех прондексированных изменений  и добавление  к коммиту подставленного комментария

Для данной операции используйте комманду:

    git commit -am "text"

## Вывод истории коммитов

Чтобы увидеть последовательные изменения и комментарии к коммитам необходимо использовать команду:

    git log

С отображением всех и в одну стороку:

    git log --oneline --all

## Переход в коммит

Для перехода в ту или иную версию необходимо использовать комманду:

    git checkout (first 4 symbols of commit name)
(Hash - идентификатор коммита из лога)
## Обзор изменений

Для сравнения источников  данных git применяется комманда:

    git diff (two commits)


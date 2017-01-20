## Порядок работы над проектом
> Делаем fork этого репозитория.  
>
> Получаем ссылку, формат git@github.com:имя/репозиторий.git  
>
> В консоли переходим в папку c проектами и клонируем командой  
> git clone git@github.com:имя/репозиторий.git  
>
> Переходим в папку склонированного проекта, переключаемся на ветку dev, кодим.  
>
> По завершению блоков объединяем ветку dev с веткой master и делаем pull request для проверки.
>  
> Задаем вопросы, если что-то не получается.  

## Основные команды git

### git status
Команда git status показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе.

## git add
Команда git add добавляет содержимое рабочей директории в индекс для последующего коммита.

## git commit
Команда git commit берёт все данные, добавленные в индекс с помощью git add, и сохраняет изменения с текстом коммита, в формате git commit -m 'текст'

## git push [удал. сервер] [ветка]
Опубликовать локальные изменения на github, закрепленные в коммите, в указанной ветке, например git push origin dev

## git checkout -b имя ветки
Создать новую ветку с копией текущей версии проекта и перейти на неё, например git checkout -b test

## git checkout имя ветки
Перейти на имеющуюся ветку, например git checkout master

## git branch -D имя ветки
Удалить указанную ветку, например git branch -D test

## git merge имя ветки
Объединить изменения из указанных веток, например git merge test, переносит изменения из ветки test в текущую

## git diff ветка1 ветка2
Сравнить изменения на ветках, например git diff master test

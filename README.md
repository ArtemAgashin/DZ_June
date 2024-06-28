# DZ_June
# Инструкция по работе с git (команды)

1. Команда git init создает локальный репозиторий
2. Команда git add добавляет файлу версионность в локальном репозитории
3. Команда git checkout позволяет перемещаться между ветками.
4. Команда git diff позволяет увидеть разницу между текущей и зафиксированной версией файла.
5. Команда git commit позволяет зафиксировать изменения в репозитории.
6. Команда git branch выводит список всех имеющихся веток на экран.
7. Команда git branch new_branch позволяет создать новую ветк.
8. Команда git merge позволяет слить ветки.
9. Коамнда git diff позволяет увидеть разницу между текущей и зафиксированной версией файла.
10. Команда git log выводит перечень коммитов.

# Инструкция по работе с Markdown

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойным звездочками(**) или двойным знаком нижнего подчеркивания (__).
Например, __вот так__.

Альтеранитвные способы выделения текста полужирным или курсивом нужны для того, чтобы мы могли совмещать оба эти способа.
Например, _текст может быть выделен курсивом и при этом быть **полужирным**_

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*).
Например вот так:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добавить ненумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы встаить изображение в текст, достаточно написать следующее:
![Красивая природа](picture.jpeg)

## Ссылки

Чтобы оформить ссылкой часть текста, используется такой синтаксис:
[ссылка на сайт](https://ru.stackoverflow.com/questions/789389/Как-в-markdown-сделать-ссылку-для-перехода-к-заголовку)

## Работа с таблицами

Для создания таблицы необходимо использовать символ pipe или | для разделения ячеек и дефиса (-) для создания строки заголовка.

|Яблоки|Груши|Персики|
|------|-----|-------|
|   5  |   2 |    8  |


## Цитаты
добавил информацию под цитатами в ветке main
Чтобы часть текста отобразилась как цитата нужно перед ним поставить закрывающу угловую скобку.
Например,
> Кто не работает, тот не ест!

## Инструкция по регистрации на GitHub и созданию удаленного репозитория

1. Создать аккаунт на GitHub.com
2. Создать локалльный репозиторий.
3. Подружить локальный и удаленный репозиторий. GitHub при создании нового репозитория git подскажет как это можно сдделать.
4. Отправить (push) ваш локальный репозиторий в удаленный (на GitHub), при это вам, возможно, нужно будет авторизоваться на удаленном репозитории.
5. Провести изменения с другого компьютера
6. Выкачать (pull) актуальное состояние из удаленного репозитория.

## PullRequest

1. Делаем форк (fork) интересующего нас репозитория.
2. Мы делаем git clone для нашей версии этого репозитория.
3. Мы создаем ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке.
5. Отправляем изменения на свой аккаунт (push).
6. В окне на GitHub появляется возможность отправить pull request.
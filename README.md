# Памятка Git + Github

## Проверка на наличие .git

`$ ls -la`

## Инициализация git (если нет .git)

`$ git init`

## В случае промаха папки, удаляем .git

`$ rm -rf .git/`

## Индексация файлов перед коммитом

`$ git add .`

## Проверить статус репозитория

`$ git status`

## Проверить git пользователя

`$ git config --list | grep user`

## Изменить пользователя git

`$ git config --global user.name "Alex Dmit"`

`$ git config --global user.email alex@gmail.com`

## Сохраняем изменения в истории git

`$ git commit -m "Commit description"`

## Посмотреть историю коммитов

`$ git log`


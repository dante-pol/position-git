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

## Проверить наличие удаленного репозитория (Github)

`$ git remote show origin`

## Можно удалить origin

`$ git remote rm origin`

## Добавить удаленный репозиторий

`$ git remote add origin https://github.com/username/repository_name.git`

## Отправляем коммиты на Github (ветка main)

`$ git push origin main`
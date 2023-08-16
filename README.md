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

## При первом скачивании проекта с Github делаем его клон (выполняется один раз)

`$ git clone https://github.com/username/repository_name.git`

## Переходим в папку repository_name

`$ cd repository_name`

## Открываем папку в VS code

`$ code .`

## Для скачивания обновлений с Github в уже существующий репозиторий

`$ git pull origin main`

## Совмещенная команда git add и git commit

`$ git commit -am "Commit text"`

## В случае ошибки push можно использовать флаг --force

`$ git push pages main --force`
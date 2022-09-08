# Шпаргалка по консольным командам Git

## Настройки

git config --global user.name "Your Name" - указать имя, которым будут подписаны коммиты
git config --global user.email "e@w.com"  - указать электропочту, которая будет в описании коммитера

## Консольные команды

git init   - создать новый проект в текущей директории

git init folder-name - создать новый проект в указанной директории

## Просмотр изменений

git status  - показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)

git diff  - сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

## Добавление изменений в индекс

git add .  - добавить в индекс все новые, изменённые, удалённые файлы из текущей директории и её поддиректорий

## Коммиты

git commit -m "Name of commit" - зафиксировать в коммите проиндексированные изменения (закоммитить), добавить сообщение

git checkout master  - переключиться на коммит, на который указывает master 

git log - показать все коммиты

## Ветки

git branch - показать список веток

git branch new_branch - создать новую ветку с указанным именем на текущем коммите

git checkout new_branch  - перейти в указанную ветку

git merge hotfix  - влить в ветку, в которой находимся, данные из ветки hotfix

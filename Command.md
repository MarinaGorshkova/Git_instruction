# Команды GIT
___
**git config --global user.name "your name"** - настройка имени;

**git config --global user.email "your email"** - настройка почты;

**git init** - создание локального репозитория;

**git clone "address"** - сщздание удаленного репозитория;

**git add** - добавить для сохранения;

**git commit** - сохранить;



## Ветки

**git branch** - просмотр всех веток;

**git branch "name"** - создание новой ветки;

**git checkout "name"**  - переход на другую ветку;

**git branch -d "name"** - удаление ветки;



## Просмотр изменений
**git status** - показать состояние репозитория (отслеживаемые, измененные, новые файлы и т.д.);

**git diff** - сравнить рабочую директорию и индекс;

**git diff --master future** - посмотреть что сделано в ветке future по сравнению с веткой master;


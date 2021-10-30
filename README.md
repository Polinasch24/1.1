# Домашнее задание к лекции «История и работа с ветками»

## Задача №1 - Работа с историей и переключение между коммитами

### Легенда

Проект NeuroStartUp всё больше развивается и всё больше разработчиков подключается к проекту. Лендинг постоянно оптимизируется по маркетинговые компании и запросы. Но тут выясняется, что перестала работать функция - "Подписаться на новости", а это достаточно важная функция. Вы знаете лишь о том, что эта функция работала в коммите `c2e06a`, а когда она перестала работать - никто не знает. Вам нужно найти в каком из коммитов эта функция сломалась и кто её сломал (чтобы он потом починил :smiley:)

### Задача

1. Склонируйте Git-репозиторий [по ссылке](https://github.com/netology-code/git-homeworks-neuro-broken);
1. Переключитесь на коммит `c2e06a`, удостоверьтесь, что функция работает;
1. Переключитесь на последний коммит;
1. Используя команды переключения между коммитами, определите в каком коммите и кем была внесена ошибка.

**В качестве результата пришлите проверяющему Имя автора коммита и хэш-коммита**

## Задача №2 - Создание веток

### Легенда

Вам поставили важную задачу - необходимо реализовать функцию "Обратный звонок" на лендинг странице. Воспользуйтесь для этого инструкцией по подключению скрипта - [Ссылка на инструкцию CallbackUp](branches/callbackup.md). Вы прекрасно понимаете, что для разработки новых функций необходимо использовать ветки (branches), поэтому ваша задача - создать новую ветку и в ней произвести интеграцию с CallbackUp.

### Задача

1. Склонируйте Git-репозиторий [по ссылке](https://github.com/netology-code/git-homeworks-neuro-callbackup);
1. Создайте ветку **feature/callbackup** и переключитесь на неё;
1. Интегрируйте CallbackUp согласно [инструкции](branches/callbackup.md);
1. Создайте отдельный репозиторий на GitHub'е;
1. Добавьте remote origin в свой локальный репозиторий и отправьте сделанные вами изменения на GitHub;
1. Убедитесь, что ветка **feature/callbackup** тоже попала на GitHub.


**В качестве результата пришлите проверяющему ссылку на ваш GitHub проект**


## Задача №3 - Слияние изменений

### Легенда

Поскольку разработка новых функций в ветках - ключевой подход при работе с Git'ом, то ваши коллеги также разрабатывают функции в новых ветках. Один из ваших коллег попросил помочь ему со слиянием тех изменений, которые он сделал в ветку **master**. Помогите ему.

### Задача

1. Склонируйте Git-репозиторий [по ссылке](https://github.com/netology-code/git-homeworks-neuro-merge/tree/master) ;
1. Слейте ветку **feature/earlyorder** с веткой **master** (не забудьте разрешить конфликт);
1. Удалите ветку **feature/earlyorder**;
1. Создайте отдельный репозиторий на GitHub'е;
1. Добавьте remote origin в свой локальный репозиторий и отправьте сделанные вами изменения на GitHub.


**В качестве результата пришлите проверяющему ссылку на ваш GitHub проект**

# Основные команды Git первого семинара

* **git init** - создание локального репозитория

* **git status** - получить информацию от Git и текущее его состояние

* **git add** - добавить файл или файлы к следующему коммиту

* **git commit -m "message** - создание коммита

* **git log** - вывод на экран истории всех коммитов с их хеш-кодами

* **git checkout** - переход от одного коммита к другому

* **git checkout master** - вернуться к актуальному состоянию и продолжить

* **git diff** - увидеть разницу между текущим файлом и закомиченным

* __git branch__ - выводим список веток в репозитории, также видим на какой ветки находимся

+ __git branch new_branch_name__ - создаём ветку с именем _new_branch_name_

+ __git branch -d branch_to_delete__ - удаляем ветку с именем _branch_to_delete_

+ __git checkout branch_name__ - переходим в ветку с именем _branch_name_

+ __git log --graph__ - выводим список в виде красивого графа/дерева

+ __git merge branch_name__ - сливаем ветку _branch_name_ с текущей веткой

+ __git commit -am "message"__ - Одновременно делает команды __git add__ и __git commit "message"__. Нужно  помнить что __add__ работает для всех недобавленных файлов.

* **git log --oneline** -Выводи хэши с комментами компактно.

* __git branch -m old_branch_name new_branch_name__ -переименовать ветку

* __git checkout -b branch_name__ - создать новую ветку и перейти на неё

* __git merge --abort__ - отменить слияние с конфликтом

# Информация и команды третьей[2] лекции 

## Как сделать pull request

* Делаем **fork** репозитория
* Делаем **clone** СВОЕЙ версии репозитория
* Создаём новую ветку и в НЕЁ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой [GitHub](https://github.com)
* В [GitHub](https://github.com) нажимаем кнопку PullRequest

## Команды для работы с удаленными репозиториями

* **git clone** - эта команда позволяет склонировать внешний репозиторий на наш ПК

* **git pull** - эта команда позволяет скачать всё из текущего репозитория и автоматически сделать merge с нашей версией

* **git push** - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. **ТРЕБУЕТ АВТОРИЗАЦИИ** на внешнем репозитории
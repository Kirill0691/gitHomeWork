# Репозиторий для pull request

* В своём аккаунте на *GitHub* создать копию репозитория **maxim-stoma/gitHomeWork** с помощью кнопки "Fork".
* Клонировать копию репозитория на локальный компьютер.
* **Создать новую ветку.**
* Добавить файл с инструкцией в новую ветку.
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
* Зафиксировать изменения (коммиты).
* Отправить изменения на GitHub.
* На сайте GitHub выполнить Pull request.
# Основные команды Git
## Введение в контроль версий. Работа с Git. Составление инструкции по работе с Git.
* git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git branch – посмотреть список веток в репозитории
* git branch <название ветки> – создать новую ветку
* git checkout <название ветки> – переход к другой ветке
* git branch -d <название ветки> – удалить ветку
# Работа с репозиторием
 Создать репозиторий — git init. Инициализирует пустой репозиторий.

 Склонировать удалённый репозиторий — git clone [ссылка на удалённый репозиторий]. Проект появится в директории, где вы находились в момент клонирования.

 Связать удалённый и локальный репозитории — git remote add origin [ссылка на удалённый репозиторий].

# Работа с изменениями
Любая работа с изменениями начинается с получения последней версии проекта из удалённого репозитория. Далее вы можете внести правки в проект, добавить изменения в индекс и сделать коммит. В конце нужно отправить изменения в удалённый репозиторий или удалить, если они больше не нужны.

Подтянуть изменения — git pull. Подтягивает в локальный репозиторий последнюю версию проекта. Будьте внимательны, вызов этой команды сотрёт все незафиксированные изменения. Иногда после ввода этой команды появляется конфликт.
# Как настроить окружение и инструменты для Node.js

## Система контроля версий git

- Откройте командную строку и напишите `git`
  - Скорее всего git уже установлен, тогда Вы увидите справку по использованию
  его команд и можете приступать к следующему пункту
  - Возможно, будет предложено его устаносить, соглашайтесь
  - Или Вы увидите ошибку, тогда нужно следовать
  [инструкции с сайта git](https://git-scm.com/book/ru/v1/Введение-Установка-Git)
- Теперь нужно изучить конанды, почитать документацию
  - Краткую и простую шпоргалку по конандам `git` можно
  [найти тут](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
  - А тут мы собрали для Вас все необходимые материалы для глубокого изучения:
  [HowProgrammingWorks/VersionControl](https://github.com/HowProgrammingWorks/VersionControl/blob/master/README.ru.md)
- Зарегистрируйтесь [на github](https://github.com/)
  - И создайте свой пробный репозиторий
  - Склонируйте его к себе на машину через `git clone <url>`
  - Попробуйте сделать: `branch, add, commit, push`
  - Попробуйте сделать: `pull request, merge` (через веб интерфейс)
  - Потом осваивайте разрешение конфликтов для: `merge, cherry-pick, rebase`
  - Посмотрите на другие возможности веб-интерфейса github: `issues, projects, insights`

## Установите Node.js

  - Через `nvm` по [инструкции](https://github.com/creationix/nvm/blob/master/README.md)
  - Или через `nvs` по [другой инструкции](https://github.com/jasongin/nvs/blob/master/doc/SETUP.md)
  - или через пакетный менеджер вашей ОС [по инструкции](https://nodejs.org/en/download/package-manager/)
  - Или из исходников собрать по [инструкции тут](https://github.com/nodejs/node/blob/master/BUILDING.md)

##  Инициализация проекта

  - Добавьте в проект `package.json` при помощи `npm init`
  - Пакетный менеджер `npm` и веб-каталог пакетов тут [npmjs.com](https://www.npmjs.com/)
  - Добавьте зависимость, например: `npm install metasync`
  - Добавьте в проект файлы: `.npmignore` и `.gitignore` из примеры можно взять
  в тут: [npmignore](https://github.com/metarhia/metasync/blob/master/.npmignore)
  и [.gitignore](https://github.com/metarhia/metasync/blob/master/.gitignore)

## Установите и настройте eslint

  - Сайт и инструкция по установке: [eslint](https://eslint.org/)
  - [Пример конфигурации](https://github.com/HowProgrammingWorks/Tools/blob/master/JavaScript/examples/.eslintrc.yml)

## Что должно получиться

  - Примерно такое:
  [github.com/HowProgrammingWorks/Project](https://github.com/HowProgrammingWorks/Project)

## Полезные ссылки

  - Все примеры можно будет брать в нашей организации: http://how.programming.works
  - Разработки нашего КБ Metarhis тут: http://metarhia.com

## Мои контакты и профили

  - на Github: https://github.com/tshemsedinov
  - на Habrahabr: https://habrahabr.ru/users/marcusaurelius/
  - на LinkedIn: https://www.linkedin.com/in/shemsedinov/
  - на NPM: https://www.npmjs.com/~timur.shemsedinov
  - на Facebook: https://www.facebook.com/tshemsedinov
  - на Instagram: https://www.instagram.com/tshemsedinov/
  - на Twitter: https://twitter.com/ImpressAppSrv

<<<<<<< HEAD
<<<<<<< HEAD
# Gulp Front

*Шаблон для быстрого старта разработки с [Gulp](http://gulpjs.com/), [Jade](http://jade-lang.com/) и [Stylus](https://learnboost.github.io/stylus/)*

[![Build Status](https://api.travis-ci.org/zoxon/gulp-front.svg)](https://travis-ci.org/zoxon/gulp-front)
[![devDependency Status](https://david-dm.org/zoxon/gulp-front/dev-status.svg)](https://david-dm.org/zoxon/gulp-front#info=devDependencies)
[![GitHub issues](https://img.shields.io/github/issues/zoxon/gulp-front.svg?style=flat)](https://github.com/zoxon/gulp-front/issues)
[![GitHub forks](https://img.shields.io/github/forks/zoxon/gulp-front.svg?style=flat)](https://github.com/zoxon/gulp-front/network)
[![GitHub stars](https://img.shields.io/github/stars/zoxon/gulp-front.svg?style=flat)](https://github.com/zoxon/gulp-front/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/zoxon/gulp-front/blob/master/LICENSE)
[![Join the chat at https://gitter.im/zoxon/gulp-front](https://img.shields.io/badge/gitter-join%20chat-green.svg?style=flat)](https://gitter.im/zoxon/gulp-front?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Демо
[zoxon.github.io/gulp-front](http://zoxon.github.io/gulp-front/)

## Преимущества и возможности

* Быстрый и удобный сборщик (gulp)
* Простейшие модули (js, styl, jade, json, прочие файлы)
* Базовые модули (bread-crumbs, button, footer, form, form-item, header, input-group, logo, main-menu, page-title, pagination и др.)
* Сборка svg спрайтов для инлайн подлючения (gulp-svg-symbols)
* Сборка png спрайтов и ретина спрайтов (gulp-spritesmith)
* Jade миксины для @media (rupture)
* Склейка @media и перенос в конец файла (gulp-combine-mq)
* Сервер и синхронное тестирование сайта в браузерах (с помощью browser-sync)
* Авто-подстановка вендорных префиксов в CSS (autoprefixer-stylus)
* Шаблонизатор Jade и препроцессор HTML (gulp-jade)
* Конкатенация JavaScript файлов (gulp-include)
* Форматирование CSS (gulp-csscomb)
* Сжатие изображений (gulp-imagemin)
* Препроцессор CSS (gulp-stylus)
* Минификация CSS (gulp-csso)
* Форматирование HTML (gulp-html-prettify)
* Минификация JavaScript (gulp-uglify)
* Перехват и вывод ошибок без остановки gulp (gulp-plumber)
* Jade миксины для елементов форм
* Настроенная типографика на базе normalize.css
* Миксины сетки (fluid и fixed)
* Миксины для font-face и др.
* Настроенные конфиги для TravisCI и EditorConfig
* Упаковка скомпилированных файлов в zip архив


## Быстрый старт

* Установить [node.js](https://nodejs.org)

* Зайти в папку с установленной nodejs и обновить npm до последней версии

	```bash
	cd "C:\Program Files\nodejs"
	```

	или

	```bash
	cd "C:\Program Files (x86)\nodejs"
	```

	в зависимости от того где у вас установленна nodejs, и выполнить

	```bash
	npm install npm@latest
	```

* Склонировать проект либо [скачать архив](https://github.com/zoxon/gulp-front/archive/master.zip)

	```bash
	git clone git@github.com:zoxon/gulp-front.git my-project && cd my-project
	```

	Все новые фишки появляются сначала в ветке [develop](https://github.com/zoxon/gulp-front/tree/develop), но там могут быть баги

* Установить `gulp` глобально (один раз!)

	```bash
	npm i -g gulp
	```

* Установить зависимости (1 раз на проект)

	```bash
	npm i
	```

* Запустить gulp.js

	```bash
	gulp dev
	```

* В браузере откроется страница с проектом, по адрессу [`http://localhost:3000/`](http://localhost:3000/)

## Основные таски

* `gulp dev` - запускает вотчеры и сервер
* `gulp build` - собирает проект
* `gulp zip` - собирает проект и архивирует его в zip архив

## Структура папок и файлов

```
gulp-front/                             # Корень проекта
├── dest                                # Скомилированные файлы
├── source                              # Исходные файлы
│   ├── modules                         # Простейшие модули
│   ├── pages                           # Страницы
│   └── static                          # Статичные файлы
│       ├── assets                      # Прочие файлы
│       ├── scripts                     # JavaScript файлы
│       │   ├── plugins                 # Папка с плагинами
│       │   ├── main.js                 # Основной js файл
│       │   └── plugins.js              # Точка сборки плагинов
│       └── styles                      # Статичные стили
│           ├── components              # Компоненты
│           ├── plugins                 # Стили плагинов
│           ├── _common.styl            # Различные стили
│           ├── _media.styl             # @media
│           ├── _variables.styl         # Переменные
│           ├── main.styl               # Основной файл стилей
│           └── reset.styl              # Сброс стилей + типографика
├── tmp                                 # Временная папка
├── zip                                 # Папка с zip архивами
├── package.json                        # Зависимости для node.js
├── .csscomb.json                       # Конфиг для gulp-csscomb
├── .editorconfig                       # Конфиг для EditorConfig
├── .travis.yml                         # Конфиг для TravisCI
├── gulpfile.js                         # Конфиг gulp.js
├── LICENSE                             # Лицензия
└── README.md                           # Файл который вы читаете
```

## Лицензия
[The MIT License (MIT)](LICENSE)
=======
# gf3016
Demo project of my skills
>>>>>>> 8ea38f7e9ddc8b6f2d3e43581c0b1651f426e690
=======
# gf3016
Demo project of my skills
>>>>>>> 8ea38f7e9ddc8b6f2d3e43581c0b1651f426e690

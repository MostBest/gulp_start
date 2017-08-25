# Gulp - быстрый старт
Сборка gulp от компании mostbest.ru. Автор: Чернов Алексей

# Используемые технологии
_Для работы требуется установка [Node.js](https://nodejs.org/en/), [Git](https://git-scm.com/)_

# Подготовка рабочей области
Создаем репозиторий проекта на локальном сервере.  
1. Открываем окно команд **shift + левая кнопка мыши** из папки проекта.
1. В открывшемся окне пишим команду **npm i gulp -g** - установка gulp (глобально). Данная операция выполняется однократно так как при этом gulp будет установлен глобально.  
1. **npm init** - стартовая команда для создание файла **package.json**. В него будет записаваться информация об установленных пакетах.  
1. **npm i gulp -D** - устанавливаем пакет gulp локально.
1. **копируем/создаем структуру каталогов** - основными делаем дериктивы **src** и **build**.
1.1 **src** - 



## Сборка CSS
**gulp-sass** - CSS препроцессор/шаблонизатор. Возможная альтернатива [gulp-stylus](http://stylus-lang.com/). 
**gulp-cssnano** - CSS компрессор. [Официальный сайт](http://cssnano.co/).
**gulp-autoprefixer** - автоматическое добавление вендорных префиксов. 

## Сборка JS
**gulp-uglify** - JavaScript компрессор. 
**gulp-concat** - объединение JavaScript файлов. 

## Оптимизация изображений
**gulp-imagemin** - компрессор изображений. 
**imagemin-pngquant** - PNG плагин для gulp-imagemin.
**gulp.spritesmith** - объединяет изображения в спрайты, формирует вызов из CSS.
**gulp-cache** - формирует кэш из временных файлов. Необходим для оптимизации работы с изображениями. 

## Оптимизация SVG изображений
**gulp-svgmin** - минификация SVG/SVGO.
**gulp-svg-spritesheet** - объединяет SVG изображения в спрайты, формирует вызов из CSS.

## Автоматическая перезагрузка страницы браузера
**browser-sync** - сервер, перезагрузка страницы при внесении изменений. Возможная альтернатива [gulp-livereload](https://www.npmjs.com/package/livereload).

## Вспомогательные плагины
**gulp-rename** - переименование файлов.
**del** - очистка выбранной директории. 
**gulp-rigger** - подключает содержимое одного файла в тело другого. 

Структура файлов и папок:

    ./src

        /css

            /*.scss *.sass *.less *.styl *.css 
            /*.scss *.sass *.less *.styl *.css 

        /js

            /lib.js  
            /main.js  

    ./gulpfile.js
    ./package.json
    ./index.html
Ввести в терминале/командной строке команду: npm i (должен быть установлен node.js)
Выполнить команду: gulp (запуск таска default, который очистит каталог build и запустит таск scripts и styles, а так же watch - отслеживает изменения в файлах html, css, sass, scss, less, styl и js)

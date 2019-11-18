bsl-styleguide
==============
Анализ стиля кода на языке 1С. 



Быстрый старт.
=============

```sh
git clone https://github.com/bsl-styleguide/bsl-styleguide.git
raco exe -o bin/styleguide main.rkt
```

Добавить каталог bin в переменную PATH. 

Переходим в каталог проекта с анализируемыми файлами
```sh
styleguide -g
```

Редактируем (при необходимости ) файл настроек .styleguide.yaml

Запускаем анализ
```sh
styleguide 
```


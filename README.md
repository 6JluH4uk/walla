# walla

Сервис для съема позиций в Yandex и Google(с морды, используется selenium).

Проект достаточно легко масштабируется под любые требования(по сути ограничен только вашими мощностями).

Итак, для того, чтобы развернуть базовую версию необходимо выполнить следующие шаги:


1) Клонируем проект
```
git clone ...
```
2) Настраиваем config.py в корне проекта(config_sample.py в помощь)
3) Запускаем docker-compose
```
docker-compose up
```
Заходим на localhost:5000 и радуемся жизни :)
Первая загрузка слов будет долго отвечать(инициализируются браузеры)

Что хочется сделать:
- [ ] Добавить возможность съема "мобильных" позиций
- [ ] Добавить проверку позиций сайта по списку
- [ ] Добавить выбор региона и кэширование

По любым вопросам пишите на почту bJluH4uk@gmail.com

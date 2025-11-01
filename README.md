![logo](http://www.robrowser.com/logo.png)

roBrowser is a web-based clone of the popular MMORPG [Ragnarok Online](http://iro.ragnarokonline.com/) built with WebGL, JavaScript, HTML5, and more. The project is entirely free and opensource, so you're welcome to setup roBrowser on your own server or try a [demo](http://demo.robrowser.com/).

You can learn more at http://robrowser.com

## Screenshots
![screen](http://upload.robrowser.com/demo.jpg)


## Установка

### Предварительные требования

Для запуска roBrowser вам понадобится браузер с поддержкой [WebGL](http://www.chromeexperiments.com/webgl/) и совместимостью с OpenGL ES 2.0. Мы протестировали следующие браузеры:

* Chrome
* FireFox
* Opera
* IE11

Если вы не запускаете roBrowser в приложении Chrome, вам потребуется установить плагин Java.

### Быстрый старт

1.  [Скачайте roBrowser](https://github.com/vthibault/roBrowser/archive/master.zip) и распакуйте его.
2.  [Конвертируйте БД](https://github.com/vthibault/roBrowser/tree/master/tools/converter/), чтобы получить пользовательский контент для roBrowser.
3.  [Скомпилируйте скрипты](https://github.com/vthibault/roBrowser/tree/master/tools/build/), чтобы сократить время загрузки.
4.  Установите [удаленный клиент](https://github.com/vthibault/roBrowser/tree/master/client) и установите параметр *remoteClient* на ваш сервер.
5.  Установите [прокси websocket](https://github.com/herenow/wsProxy/blob/master/README.md) и установите параметр *socketProxy* на URL вашего прокси-сервера.
6.  Настройте roBrowser - [документация](http://www.robrowser.com/getting-started#API) и несколько [примеров](https://github.com/vthibault/roBrowser/tree/master/examples).

## Contributing

roBrowser is developed by a [team](https://github.com/vthibault/roBrowser/graphs/contributors) located around the world. Check out the [documentation](http://www.robrowser.com/getting-started#API) and submit a pull request!

## Структура проекта

*   `applications/`: Приложения, использующие roBrowser.
*   `client/`: Файлы на стороне клиента.
*   `examples/`: Примеры использования API roBrowser.
*   `src/`: Исходный код roBrowser.
*   `tools/`: Инструменты для сборки и конвертации.

## Contact

* [Demo](http-:-//demo.robrowser.com/)
* [roBrowser website](http-:-//www.robrowser.com/)
* [roBrowser forum](http-:-//forum.robrowser.com/)
* IRC Channel: *irc.rizon.net* / Channel: *#roBrowser*

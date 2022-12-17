# Писать код – это просто

## О чём тут?
*В этом репозитории я собрал коллекцию расширений, инструкций и просто приятных бонусв, которыми пользуюсь в своей повседневной работе сам и, если вы уж зашли сюда, то может они заинтересуют и вас.*

## Шпаргалка для работы и написания кода:
### Редактор исходного кода:
- Скачать редактор [Visual Studio Code](https://code.visualstudio.com)
- Всё о "горячих" клавишах [здесь](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

### Полезные плагины "*от мала до велика*":
#### **HTML**:
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
    + Запускайте локальный сервер разработки с функцией перезагрузки в реальном времени для статических и динамических страниц. (*Внимание, нужна дополнительная настройка плагина в `settings.json` под себя*)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
    + Заполнение атрибутов HTML `id` и `class`.
    + Поддерживает связанные и встроенные таблицы стилей.
    + Поддерживает наследование шаблонов.
    + Поддержка дополнительных таблиц стилей.
    + Поддерживает другие HTML-подобные языки.
    + Валидирует селекторы CSS по требованию.
- [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
    + Расширение Visual Studio Code, которое обеспечивает заполнение имени класса CSS `class` для атрибута класса HTML на основе определений, найденных в вашем рабочем пространстве или внешних файлах, на которые ссылается элемент ссылки.
- [htmlTagWrap](https://marketplace.visualstudio.com/items?itemName=bradgashler.htmltagwrap)
    + Обертывает выделение в HTML-теги. Может обернуть строчные выделения и выделения, охватывающие несколько строк (работает как с одиночными выделениями, так и с несколькими выделениями одновременно).
    + Для использования выделите один или несколько фрагментов кода и нажмите "Alt + W" ("Option + W" для Mac).
****
#### **CSS & SASS/SCSS**
- [eCSStractor](https://marketplace.visualstudio.com/items?itemName=diz.ecsstractor-port)
    + Плагин VSCode для извлечения имен классов из HTML и генерации таблицы стилей CSS для последующей работы.
- [CSS Navigation](https://marketplace.visualstudio.com/items?itemName=pucelle.vscode-css-navigation)
    + Позволяет перейти к определению из HTML в CSS / Sass / Less, обеспечивает завершение строки и символы рабочей области для имени класса `class` и `id`, а также поддерживает поиск ссылок из CSS в HTML по клику на них
        - для Win: `Ctrl + left-click`
        - для Mac: `Cmd + left-click`
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
    + Позволяет подсматривать строки в СSS `id` и `class` в качестве определений из html-файлов в соответствующие CSS. Позволяет подсматривать и переходить к определению.
- [Live SASS Compiler](https://marketplace.visualstudio.com/items?itemName=glenn2223.live-sass)
    + Расширение VSCode, которое поможет вам компилировать/транспонировать ваши файлы SASS/SCSS в файлы CSS в режиме реального времени. (*Во время использования достаточно нажать `Watch SASS/SCSS`*)
****
#### **Расширения Git для среды разработки**
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
    + Просмотр и поиск журнала git вместе с графиком и деталями
    + Просмотр предыдущей копии файла
    + Просмотр и поиск в истории
    + Различные сравнения (ветки, версии, файлы...)
    + Другие функции расширения
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
    + Просмотр Git-графика вашего репозитория и легкое выполнение Git-действий прямо внутри графического интерфейса. Настраивается так, как вам удобно!
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    + GitLens расширяет возможности Git внутри VS Code и раскрывает неиспользованные знания в каждом репозитории. Он помогает вам с первого взгляда визуализировать авторство кода с помощью аннотаций Git blame и CodeLens, легко перемещаться и исследовать репозитории Git, получать ценные сведения с помощью богатых визуализаций и мощных команд сравнения и многое другое.
****
#### **Расширения от Google**
- [Google Fonts](https://marketplace.visualstudio.com/items?itemName=lior-chamla.google-fonts)
    + Это расширение позволяет просматривать список шрифтов Google Fonts и вставлять в код HTML или CSS @import url(...)
        - для Mac: `Shift+Cmd+P`
    *Пользуйтесь шрифтами от Google легко*
- [GoogleTranslate](https://marketplace.visualstudio.com/items?itemName=hancel.google-translate)
    + Простое расширение для VSCode для удобного поиска или перевода в Интернете с помощью различных движков.
****
## Дополнительные полезные плюшки
#### **CSS генератор веб-кода**
- [Grid layouts](https://grid.layoutit.com/)
- [Gradients](https://cssgradient.io/)
- [Animations](https://animista.net/)
- [Border-radius](https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Backgrounds_and_Borders/Border-radius_generator)

#### **Работа с FTP-сервером**
- [FTP-Simple](https://marketplace.visualstudio.com/items?itemName=humy2833.ftp-simple)
    + Прямое открытие, редактирование и сохранение файлов на сервере.
    + Сохранение локально созданных файлов или каталогов на сервере (опция загрузки и резервного копирования)
    + Загрузка файла или каталога с ftp-сервера.
    + Создание каталога на удаленном сервере напрямую.
    + Открытие удаленного каталога в рабочей области (бета-версия)
    + Удаление каталога (рекурсивно) и файлов непосредственно с сервера.
    + Переименование имени файла на FTP-сервере.
    + Сравнение файлов локального файлового сервера.
### Ну, и на десерт – bonus:
- [Слепая печать](https://www.edclub.com/typingclub)
- [Punto Switcher](https://free-software.com.ua/system/punto-switcher/)
- [Learn Git Branching](https://learngitbranching.js.org/)

------------------
#### *Собрано, протестировано, и упаковано в одну шпаргалку*
##### by SolidadosWeb &copy; 2020
###### _Все совпадения случайны и на любителя_
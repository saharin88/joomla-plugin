## Платежный модуль TRANZZO для CMS Joomla 3.6.5 + VirtueMart

### Установка
1. Создать архив папки **tranzzo**.
2. В панели управления зайти в раздел меню _**Расширения → Менеджер расширений → Установка**_.
3. Загрузить созданый архив для установки.
4. Загрузить логотип платежной системы (файл _**tranzzo.png**_) по пути **[корень_сайта]/images/virtuemart/payment/**

### Настройка
1. Получите ключи авторизации и идентификации сервиса TRANZZO (*POS_ID, API_KEY, API_SECRET, ENDPOINTS_KEY*).
2. Заполнить настройки модуля открыв страницу через меню _**Настройки → Настройки модулей → TRANZZO**_
3. Создать новый способ оплаты:  _**VirtueMart → Способы оплаты → Создать**_

Выбрать из списка обработчиков "TRANZZO", выбрать в поле "Опубликовано" значение "Да" и сохранить.

4. Перейти во вкладку "Конфигурация" и заполнить настройки, сохранить.

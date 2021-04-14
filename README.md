# rfibank-opencart
"Оплата через ЗАО "РФИ БАНК" - rficb.ru" - OpenCart модуль
Исходный код модуля распространяется по лицензии FreeBSD (license.txt)

Поддерживаемые версии OpenCart: 1.5.x в папке opencart_1_5, OpenCart: 2.x в папке opencart_2

Инструкция по установке платежного модуля ЗАО "РФИ БАНК"

1. Распаковать  содержимое  архива. Содержимое папки upload из архива
скопировать поверх структуры папок сайта.

2. В системе  администрирования  в разделе "Дополнения-Оплата" должен появиться платежный
модуль "rficb". Его необходимо установить.

3. В разделе  системы администрирования "Система-Пользователи-Группы
пользователей" для группы пользователей "Главные администраторы"
необходимо  отметить  галку  "payment/rficb" для просмотра и
для редактирования.

4.Открыть  форму  редактирования  настроек  модуля  - раздел системы
администрирования "Дополнения-Оплата" напротив модуля "rficb"
ссылка "[изменить]"

5. Данные для кабинета РФИ представлены на странице настроек

6. На сайте https://home.rficb.ru/a1lite/index/ создаете платежный сервис,
отвечающий за ваш интернет-магазин.

7. Вводите в формы настройки модуля и настроки платежного сервиса одинаковые данные.

ВАЖНО: Платежный шлюз РФИ банка принимает платежи только в рублях, поэтому
в OpenCart должна присутствовать валюта "Рубль" с кодом RUB. Платежный модуль и
платежная система поддерживают только русский язык.
Настоятельно рекомендуется использовать модуль только если рубль - основная валюта магазина.
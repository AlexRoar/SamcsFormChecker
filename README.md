# SamcsFormChecker

Вопросы можно задавать в t.me/yaishenka

## Описание

Скрипт ищет ключи в таблицах с ответами и пишет напротив найденных ключей текст

## Инструкция

### Настройка

- надо создать аккаунт для работы с гугловской апишкой https://developers.google.com/identity/sign-in/web/sign-in
- раздать на все нужные таблицы доступ на редактирование на этот аккаунт (ЭТО ВАЖНО)
- положить json с аккаунтом в корень проекта
- создать файл settings.py и заполнить его аналогично файлу settings_example.py

### Запуск

  `pip install - r req.txt`

  `python3 main.py`

### Замечания

1. Скрипт не учитывает uppercase, поэтому если ключи отличаются только в регистре некоторых символов, то они равны
2. Верхний пункт сделан намеренно для минимизации продолбов со стороны студентов
3. Лучше скрипт ставить по крону на каком-нибудь серваке (Гуглить cron linux)
4. Файлик с аккаунтом гугла конечно можно попросить у автора, но лучше создать свой
5. Запускать скрипт лучше не чаще чем раз в час, ибо квоты у гугла небольшие, а студентов у нас много))
6. Файлик settings.py намеренно скрыт, чтобы ссылки на таблицы не попадали в открытый доступ




  

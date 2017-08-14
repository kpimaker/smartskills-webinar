# Примеры вебинара Skillfactory

### Поиск дубликатов в выгрузке (Дубликаты заявок.ipynb)
С помощью Pandas строим пересечение выгрузок из файлов channel_1_data.txt и channel_2_data.txt, используя столбец tel. В примере все данные зашифрованы, адреса созданы случайным образом.

<br />

### Статистика всех поисковых фраз за период по дням (Поисковые фразы.ipynb)
Скрипт выгружает визиты и посетителей в разбивке по поисковым фразам и системам для заданного счетчика Яндекс Метрики. Выгрузка происходит за каждый день периода по-отдельности. Итоговая выгрузка пишется в файл data.txt.

Перед запуском скрипта добавьте в переменную counterID (строка 3) номер счетчика, в переменную token (строка 5) - токен для доступа к данным счетчика по API. 

Как получить токен описано в документации https://tech.yandex.ru/metrika/doc/api2/intro/authorization-docpage/. 

Для простоты используйте опцию получения отладочного токена https://tech.yandex.ru/oauth/doc/dg/tasks/get-oauth-token-docpage/.

Если у вас нет доступа к счетчикам метрики, то можно взять тестовый токен и данные из примеров https://tech.yandex.ru/metrika/doc/api2/api_v1/examples-docpage/.
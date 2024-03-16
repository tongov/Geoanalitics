Предсказания локаций снятия наличных в банкоматах на основе транзакций клиентов банка.

Данные по транзакциям ограничены 200000 записями. В целях борьбы с нехваткой памяти.

Это неокончательное, но работающее решение.

Данные родные:

!cd /content && wget https://storage.yandexcloud.net/ds-ods/files/data/docs/competitions/DataFusion2024/Data/geo/hexses_target.lst

!cd /content && wget https://storage.yandexcloud.net/ds-ods/files/data/docs/competitions/DataFusion2024/Data/geo/hexses_data.lst

!cd /content && wget https://storage.yandexcloud.net/ds-ods/files/data/docs/competitions/DataFusion2024/Data/geo/transactions.parquet

!cd /content && wget https://storage.yandexcloud.net/ds-ods/files/data/docs/competitions/DataFusion2024/Data/geo/target.parquet

!cd /content && wget https://storage.yandexcloud.net/ds-ods/files/data/docs/competitions/DataFusion2024/Data/geo/moscow.parquet

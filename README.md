# zfs_courses

1. Для создания пула была использована команда
zpool create pool_test sdb

2.Сравнение различных видов сжатие

Исходя из результата, можно сказать, что gzip - лучший алгоритм сжатия, чем другие


2. Cписок команд, которыми был восстановлен pool, находится в файле recovery_pool

Файл с описанием настроек settings находится в settings_file


3. Cписок шагов:
    1.  zpool create recovery
    2.  zfs recv -F recovery < otus_task2.file
    3.  зашифрованное сообщение https://github.com/sindresorhus/awesome

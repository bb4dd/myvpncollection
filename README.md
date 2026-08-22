# 🇷🇺 Готовые настройки для Shadowrocket на Wi-Fi/LTE + белые списки

[ru.conf](./conf/ru.conf) – всё в прокси, российские сервисы, Apple и некоторые сервисы напрямую;

[ru_direct.conf](./conf/ru_direct.conf) – всё напрямую, отдельный список заблокированного в прокси;

[ru_whitelist.conf](./conf/ru_whitelist.conf) – белый список напрямую, всё остальное в прокси.

### Прочие файлы репозитория

[direct.list](./rules/direct.list) – отдельный список доменов напрямую (для `ru.conf`);

[proxy.list](./rules/proxy.list) – отдельный список доменов в прокси, (для `ru_direct.conf`);

[whitelist.list](./rules/whitelist.list) – домены из белого списка, (для `ru_whitelist.conf`).

В конфигурациях также используются наборы правил из репозиториев [misha-tgshv](https://github.com/misha-tgshv/shadowrocket-configuration-file/tree/main), [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script/tree/master) и других.

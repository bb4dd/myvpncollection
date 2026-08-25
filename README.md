# 🇷🇺 Готовые настройки для Shadowrocket на Wi-Fi/LTE + белые списки

[ru.conf](./conf/ru.conf) – всё в прокси, российские сервисы, Apple и некоторые сервисы напрямую;

[ru_direct.conf](./conf/ru_direct.conf) – всё напрямую, отдельный список заблокированного в прокси;

[ru_whitelist.conf](./conf/ru_whitelist.conf) – белый список напрямую, всё остальное в прокси.

### Прочие файлы репозитория

[direct.list](./rules/direct.list) – отдельный список доменов напрямую (для `ru.conf`);

[proxy.list](./rules/proxy.list) – отдельный список доменов в прокси, (для `ru_direct.conf`);

[whitelist.list](./rules/whitelist.list) – домены из белого списка, (для `ru_whitelist.conf`).

В конфигурациях также используются наборы правил из репозиториев [misha-tgshv](https://github.com/misha-tgshv/shadowrocket-configuration-file/tree/main), [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script/tree/master) и других.

---

# 🇺🇸/🇬🇧 Ready-to-use Shadowrocket settings for Wi-Fi/LTE + whitelists

[ru.conf](./conf/ru.conf) – everything goes through the proxy, while Russian services, Apple, and some other services connect directly;

[ru_direct.conf](./conf/ru_direct.conf) – everything connects directly, with a separate list of blocked domains going through the proxy;

[ru_whitelist.conf](./conf/ru_whitelist.conf) – the whitelist connects directly, while everything else goes through the proxy.

### Other repository files

[direct.list](./rules/direct.list) – a separate list of domains that connect directly (for `ru.conf`);

[proxy.list](./rules/proxy.list) – a separate list of domains that go through the proxy (for `ru_direct.conf`);

[whitelist.list](./rules/whitelist.list) – domains from the whitelist (for `ru_whitelist.conf`).

The configurations also include rule sets from the repositories of [misha-tgshv](https://github.com/misha-tgshv/shadowrocket-configuration-file/tree/main), [blackmatrix7](https://github.com/blackmatrix7/ios_rule_script/tree/master), and others.

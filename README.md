# MDRT Network Resource Pack

Полный объединённый ресурс-пак сервера MDRT Network.

## Скачать

[Полный ZIP 2.6.5 HOVER](https://github.com/TimaImperator/MDRT-Network-ResourcePack/releases/download/v2.6.5/MDRT-NetworkPack-2.6.5-HOVER-TEST.zip) · [Все выпуски](https://github.com/TimaImperator/MDRT-Network-ResourcePack/releases)

Скачивайте именно файл пака из Assets. Автоматические архивы GitHub Source code не являются ресурс-паком. Для ручной установки отключите предыдущий общий MDRT-пак и включите новый ZIP.

## Настройка Paper 1.21.1

На остановленном Paper-сервере замените соответствующие строки в server.properties, затем запустите сервер:

```properties
resource-pack=https://github.com/TimaImperator/MDRT-Network-ResourcePack/releases/download/v2.6.5/MDRT-NetworkPack-2.6.5-HOVER-TEST.zip
resource-pack-sha1=0ad50588747f20be164b24f38ce154239f58ed7f
require-resource-pack=false
```

Это настройки Paper backend (например, MELL), не velocity.toml. Если пак нужен и в HUB, настройте нужные backend-серверы согласованно; не включайте параллельно старые отдельные выдачи пака другими плагинами.

require-resource-pack=false сохраняет возможность отказаться от пака и играть без него. При первом входе Minecraft может спросить согласие; при разрешённых серверных паках загрузка автоматическая.

При следующем обновлении заменяйте вместе URL и SHA-1. Не заменяйте содержимое уже опубликованного файла под той же версией.

## Контрольные суммы 2.6.5

- ZIP: MDRT-NetworkPack-2.6.5-HOVER-TEST.zip
- Размер: 6 190 897 байт
- SHA-1: `0ad50588747f20be164b24f38ce154239f58ed7f`
- SHA-256: `e53d0e1f4c22f10e61a92abf7ce77ffcf514344bf5aeb109a15ace84f65187f8`

Опубликован неизменённый архив ранее подготовленной сборки 2.6.5 HOVER. Базовый клиент — Java 1.21.1; в паке есть слои для новых форматов, но совместимость со всеми версиями и шейдерами не заявляется как протестированная. Репозиторий не содержит серверных конфигов, баз, миров или JAR плагинов.

[Документация Paper: server.properties](https://docs.papermc.io/paper/reference/server-properties/)

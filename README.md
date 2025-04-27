# Кастомный роутинг AllowDomains для приложения [Happ](https://happ.su)

Ссылки генерируются при обновлении списков [KazZzeL/allow-domains-dat](https://github.com/KazZzeL/allow-domains-dat)

## Статические ссылки с редиректом на deeplink (открывать с устройства, на которое добавляется)

- **[AllowDoamins-RussiaInside](https://happ-routing.redirectme.net/adri)**
- **[AllowDoamins-RussiaOutside](https://happ-routing.redirectme.net/adro)**
- **[AllowDoamins-UkraineInside](https://happ-routing.redirectme.net/adui)**
- **[GlobalProxy-RussiaInside](https://happ-routing.redirectme.net/gpri)**
- **[GlobalProxy-UkraineInside](https://happ-routing.redirectme.net/gpui)**

## Особенности роутингов со списками ITDog:
- **Малые размеры геофайлов**: в прокси отправляются только домены и IP, блокирующие доступ из РФ или скрывающие часть информации
- **FakeDNS**: провайдер не сможет заблокировать dns-запрос или подменить ответ для проксируемых доменов
- **Domestic DNS** для Inside - DoU от Google: самый быстрый
- **Domestic DNS** для Outside - DoH от Google: безопасный, но более медленный

## Особенности роутингов со списками Loyalsoldier:
- **Большие размеры геофайлов**: в прокси отправляется всё, кроме CurrentCountry-доменов и IP
- **Domestic DNS** - DoH от Google: безопасный, но более медленный
- **Remote DNS** - DoH от Cloudflare: безопасный, но более медленный
- являются скорее демонстрационными, обновление не привязано к обновлению геофайлов

## Deeplink-и с контентом роутинга

- **AllowDoamins-RussiaInside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink.sha256sum)
- **AllowDoamins-RussiaOutside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink.sha256sum)
- **AllowDoamins-UkraineInside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink.sha256sum)
- **GlobalProxy-RussiaInside** (содержит геофайлы Loyalsoldier, очень тяжёлые для ОЗУ): 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink.sha256sum)
- **GlobalProxy-UkraineInside** (содержит геофайлы Loyalsoldier, очень тяжёлые для ОЗУ): 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink.sha256sum)

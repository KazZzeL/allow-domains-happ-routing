# Кастомный роутинг AllowDomains для приложения [Happ](https://happ.su)

Ссылки генерируются при обновлении списков [KazZzeL/allow-domains-dat](https://github.com/KazZzeL/allow-domains-dat)

## Статические ссылки с редиректом на deeplink (открывать с устройства, на которое добавляется)

- **[russia-inside](https://happ-routing.redirectme.net/ri)**
- **[russia-outside](https://happ-routing.redirectme.net/ro)**
- **[ukraine-inside](https://happ-routing.redirectme.net/ui)**
- **[global-proxy-russia-inside](https://happ-routing.redirectme.net/gpri)**
- **[global-proxy-ukraine-inside](https://happ-routing.redirectme.net/gpui)**

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

- **russia-inside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-inside.deeplink.sha256sum)
- **russia-outside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/russia-outside.deeplink.sha256sum)
- **ukraine-inside**: 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/ukraine-inside.deeplink.sha256sum)
- **global-proxy-russia-inside** (содержит геофайлы Loyalsoldier, очень тяжёлые для ОЗУ): 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-russia-inside.deeplink.sha256sum)
- **global-proxy-ukraine-inside** (содержит геофайлы Loyalsoldier, очень тяжёлые для ОЗУ): 
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink)
  - [https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink.sha256sum](https://github.com/KazZzeL/allow-domains-happ-routing/releases/latest/download/global-proxy-ukraine-inside.deeplink.sha256sum)

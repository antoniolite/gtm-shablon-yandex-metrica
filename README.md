# Шаблон Яндекс.Метрики для GTM

This custom template (non official) allows you implement **Yandex.Metrica** with Google Tag Manager.

**Also available in English and Spanish language.**

- [Changelog and updates](https://www.antoniolite.com/plantilla-de-yandex-metrica-para-gtm/)
- [More information about Yandex.Metrica](https://metrica.yandex.com)
- [Yandex.Metrica documentation](https://yandex.com/support/metrica/index.html)

# Author

Antonio Lite (https://www.antoniolite.com/)

# Information

This template allows you configure these methods:

- init
- hit
- extLink
- file
- reachGoal
- params
- userParams
- setUserID
- notBounce

Supports parameter and option configuration for all methods that allow it, including goal cost and currency (_order\_price_ y _currency_)

Allows you to configure the Yandex.Metrica tracking code:

- Do not send data automatically
- Block page indexing
- Do not register bounce
- Use alternative CDN
- Click map
- Session recording
- Register outgoing links
- Register hash in URLs
- More accurate bounce
- Initialization event
- Iframe recording
- Trusted domains
- Additional file extensions
- Session parameters
- User parameters

It also allows activating Yandex.Metrica's native debugging mode.

It is recommended to read these three articles (in Spanish) to know all the functionalities and characteristics of the template. All the functions that have been added are explained in detail:

[Plantilla de Yandex.Metrica para GTM](https://www.antoniolite.com/2019/06/plantilla-de-yandex-metrica-para-gtm/)

[Plantilla de Yandex.Metrica para GTM (09.2019)](https://www.antoniolite.com/2019/09/plantilla-de-yandex-metrica-para-gtm-09-2019/)

[Plantilla de Yandex.Metrica para GTM (07.2020)](https://www.antoniolite.com/2020/07/plantilla-de-yandex-metrica-para-gtm-07-2020)

# Updates

## 16.09.2020

- Text review
- English version available
- Russian version available

## 31.07.2020

- Added goal's price parameter to hit event
- Added goal's price parameter to reachGoal event
- Added goal's price parameter to file event
- Added goal's price parameter to extLink event
- Re-ordered some field's blocks
- Fixed minor bugs
- Code optimization

## 25.09.2019

- Added trustedDomains parameter when initialized
- Added childIframe parameter when initialized
- Added userParams parameter when initialized
- Added triggerEvent parameter when initialized
- Fixed bug setting User ID
- Fixed bug adding file extensions
- Code optimization

## 16.06.2019

- First release

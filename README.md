# RechevLab (רכב לאב) – site

Public website of the RechevLab Android app by [RabieMan Labs](https://rabieman.github.io/), served by GitHub Pages.

## Pages

| Page | URL |
|---|---|
| Landing page (he / ar / en, language switcher) | https://rabieman.github.io/rechevlab-site/ |
| Privacy policy (he / ar / en) | https://rabieman.github.io/rechevlab-site/privacy.html |
| Terms of use (he / ar / en) | https://rabieman.github.io/rechevlab-site/terms.html |
| Third-party notices | https://rabieman.github.io/rechevlab-site/licenses.html (linked only from the end of the terms) |

The privacy policy and terms can be opened in a single language with `?lang=he`, `?lang=ar` or `?lang=en`. The privacy policy URL is the one registered in Google Play.

## Content

- Language switcher (עברית · العربية · English) at the top, in the app's colour, like the studio home page: one language at a time, remembered with the same `rl_lang` key as rabieman.github.io; `?lang=he|ar|en` or `#ar` / `#en` open a language directly, and the footer's legal links carry the chosen language.
- Promo video (YouTube `1lW4trNxEYA`) under the hero in every language: click-to-load `youtube-nocookie` embed with a local poster `img/promo-poster.jpg`, so the page does not contact YouTube until the visitor clicks.
- Features, a 6-screenshot grid in Hebrew (4 in Arabic and in English), and a mention of loading your own GLB model in the 3D workshop.
- Contact: rabieman.labs+rechevlab@gmail.com
- RabieMan Labs logo in the footer, privacy and terms.
- Share preview: Open Graph and Twitter tags on every page, with `img/og.jpg` (1200×630, Hebrew). After changing it, bump `?v=` in the tags and re-scrape in the Facebook Sharing Debugger.

## Status

The app is in Google Play closed testing. Testers join at https://play.google.com/apps/testing/com.rabieman.autopedia. When the app goes public: add a Google Play badge and change "בקרוב ב-Google Play" in the share image.

## Images

`img/` holds the screenshots (`01`–`10`, he/ar/en; the Arabic ones are cut from the store screenshots), the app icon, the RabieMan Labs logo and the share image. Screenshots use demo data.

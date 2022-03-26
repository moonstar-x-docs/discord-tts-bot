# Microsoft Provider (TTS Tool)

This provider uses the Text-to-Speech functionality available at [TTS Tool](https://ttstool.com). It uses the Microsoft voices available from said service.

These voices appear to be the ones available on Windows.

## ℹ️ Source Information

This provider uses a public API exposed by the [TTS Tool](https://ttstool.com) site. It is a web API which means that it is consumed with just an HTTP request. HTTP requests in this project are handled by [axios](https://www.npmjs.com/package/axios).

## 🌎 Language Support

The provider offers support for the following languages:

| Language                       | Language Code | Command                         |
|--------------------------------|---------------|---------------------------------|
| :flag_us: American English     | en            | `/ms_set_my language en`        |
| :flag_au: Australian English   | en-au         | `/ms_set_my language en-au`     |
| :flag_at: Austrian German      | de-at         | `/ms_set_my language de-at`     |
| :flag_be: Belgian Dutch        | nl-be         | `/ms_set_my language nl-be`     |
| :flag_br: Brazilian Portuguese | pt-br         | `/ms_set_my language pt-br`     |
| :flag_gb: British English      | en-gb         | `/ms_set_my language en-gb`     |
| :flag_bg: Bulgarian            | bg            | `/ms_set_my language bg`        |
| :flag_ca: Canadian English     | en-ca         | `/ms_set_my language en-ca`     |
| :flag_ca: Canadian French      | fr-ca         | `/ms_set_my language fr-ca`     |
| :flag_es: Catalan              | ca            | `/ms_set_my language ca`        |
| :flag_cn: Chinese              | cn            | `/ms_set_my language cn`        |
| :flag_hr: Croatian             | hr            | `/ms_set_my language hr`        |
| :flag_cz: Czech                | cs            | `/ms_set_my language cs`        |
| :flag_dk: Danish               | da            | `/ms_set_my language da`        |
| :flag_nl: Dutch                | nl            | `/ms_set_my language nl`        |
| :flag_eg: Egyptian Arabic      | ar-eg         | `/ms_set_my language ar-eg`     |
| :flag_fi: Finnish              | fi            | `/ms_set_my language fi`        |
| :flag_fr: French               | fr            | `/ms_set_my language fr`        |
| :flag_de: German               | de            | `/ms_set_my language de`        |
| :flag_gr: Greek                | el            | `/ms_set_my language el`        |
| :flag_il: Hebrew               | he            | `/ms_set_my language he`        |
| :flag_in: Hindi                | hi            | `/ms_set_my language hi`        |
| :flag_hk: Hong Kong Chinese    | cn-hk         | `/ms_set_my language cn-hk`     |
| :flag_hu: Hungarian            | hu            | `/ms_set_my language hu`        |
| :flag_in: Indian English       | en-in         | `/ms_set_my language en-in`     |
| :flag_id: Indonesian           | id            | `/ms_set_my language id`        |
| :flag_ie: Irish English        | en-ie         | `/ms_set_my language en-ie`     |
| :flag_it: Italian              | it            | `/ms_set_my language it`        |
| :flag_jp: Japanese             | ja            | `/ms_set_my language ja`        |
| :flag_kr: Korean               | ko            | `/ms_set_my language ko`        |
| :flag_my: Malay                | ms            | `/ms_set_my language ms`        |
| :flag_mx: Mexican Spanish      | es-mx         | `/ms_set_my language es-mx`     |
| :flag_no: Norwegian            | nb            | `/ms_set_my language nb`        |
| :flag_pt: Portuguese           | pt            | `/ms_set_my language pt`        |
| :flag_ro: Romanian             | ro            | `/ms_set_my language ro`        |
| :flag_ru: Russian              | ru            | `/ms_set_my language ru`        |
| :flag_sa: Saudi Arabic         | ar            | `/ms_set_my language ar`        |
| :flag_sk: Slovak               | sk            | `/ms_set_my language sk`        |
| :flag_si: Slovenian            | sl            | `/ms_set_my language sl`        |
| :flag_es: Spanish              | es            | `/ms_set_my language es`        |
| :flag_se: Swedish              | sv            | `/ms_set_my language sv`        |
| :flag_ch: Swiss French         | fr-ch         | `/ms_set_my language fr-ch`     |
| :flag_ch: Swiss German         | de-ch         | `/ms_set_my language de-ch`     |
| :flag_in: Tamil                | ta            | `/ms_set_my language ta`        |
| :flag_th: Thai                 | th            | `/ms_set_my language th`        |
| :flag_tr: Turkish              | tr            | `/ms_set_my language tr`        |
| :flag_vn: Vietnamese           | vi            | `/ms_set_my language vi`        |

### 🗣 Available Voices

Here's a list of all the available voices for each language:

| Language                       | Voice Name        | Command                       |
|--------------------------------|-------------------|-------------------------------|
| :flag_us: American English     | :man: David       | `/ms_set_my voice David`      |
| :flag_us: American English     | :man: Mark        | `/ms_set_my voice Mark`       |
| :flag_us: American English     | :woman: Zira      | `/ms_set_my voice Zira`       |
| :flag_au: Australian English   | :woman: Catherine | `/ms_set_my voice Catherine`  |
| :flag_au: Australian English   | :man: James       | `/ms_set_my voice James`      |
| :flag_at: Austrian German      | :man: Michael     | `/ms_set_my voice Michael`    |
| :flag_be: Belgian Dutch        | :man: Bart        | `/ms_set_my voice Bart`       |
| :flag_br: Brazilian Portuguese | :man: Daniel      | `/ms_set_my voice Daniel`     |
| :flag_br: Brazilian Portuguese | :woman: Maria     | `/ms_set_my voice Maria`      |
| :flag_gb: British English      | :man: George      | `/ms_set_my voice George`     |
| :flag_gb: British English      | :woman: Hazel     | `/ms_set_my voice Hazel`      |
| :flag_gb: British English      | :woman: Susan     | `/ms_set_my voice Susan`      |
| :flag_bg: Bulgarian            | :man: Ivan        | `/ms_set_my voice Ivan`       |
| :flag_ca: Canadian English     | :woman: Linda     | `/ms_set_my voice Linda`      |
| :flag_ca: Canadian English     | :man: Richard     | `/ms_set_my voice Richard`    |
| :flag_ca: Canadian French      | :woman: Caroline  | `/ms_set_my voice Caroline`   |
| :flag_ca: Canadian French      | :man: Claude      | `/ms_set_my voice Claude`     |
| :flag_ca: Canadian French      | :woman: Nathalie  | `/ms_set_my voice Nathalie`   |
| :flag_es: Catalan              | :woman: Herena    | `/ms_set_my voice Herena`     |
| :flag_cn: Chinese              | :woman: Huihui    | `/ms_set_my voice Huihui`     |
| :flag_cn: Chinese              | :woman: Kangkang  | `/ms_set_my voice Kangkang`   |
| :flag_cn: Chinese              | :woman: Yaoyao    | `/ms_set_my voice Yaoyao`     |
| :flag_hr: Croatian             | :man: Matej       | `/ms_set_my voice Matej`      |
| :flag_cz: Czech                | :man: Jakub       | `/ms_set_my voice Jakub`      |
| :flag_dk: Danish               | :woman: Helle     | `/ms_set_my voice Helle`      |
| :flag_nl: Dutch                | :man: Frank       | `/ms_set_my voice Frank`      |
| :flag_eg: Egyptian Arabic      | :woman: Hoda      | `/ms_set_my voice Hoda`       |
| :flag_fi: Finnish              | :woman: Heidi     | `/ms_set_my voice Heidi`      |
| :flag_fr: French               | :woman: Hortense  | `/ms_set_my voice Hortense`   |
| :flag_fr: French               | :woman: Julie     | `/ms_set_my voice Julie`      |
| :flag_fr: French               | :man: Paul        | `/ms_set_my voice Paul`       |
| :flag_de: German               | :woman: Hedda     | `/ms_set_my voice Hedda`      |
| :flag_de: German               | :woman: Katja     | `/ms_set_my voice Katja`      |
| :flag_de: German               | :man: Stefan      | `/ms_set_my voice Stefan`     |
| :flag_gr: Greek                | :man: Stefanos    | `/ms_set_my voice Stefanos`   |
| :flag_il: Hebrew               | :man: Asaf        | `/ms_set_my voice Asaf`       |
| :flag_in: Hindi                | :man: Hermant     | `/ms_set_my voice Hermant`    |
| :flag_in: Hindi                | :woman: Kalpana   | `/ms_set_my voice Kalpana`    |
| :flag_hk: Hong Kong Chinese    | :man: Danny       | `/ms_set_my voice Danny`      |
| :flag_hk: Hong Kong Chinese    | :woman: Tracy     | `/ms_set_my voice Tracy`      |
| :flag_hu: Hungarian            | :man: Szabolcs    | `/ms_set_my voice Szabolcs`   |
| :flag_in: Indian English       | :woman: Heera     | `/ms_set_my voice Heera`      |
| :flag_in: Indian English       | :man: Ravi        | `/ms_set_my voice Ravi`       |
| :flag_id: Indonesian           | :man: Andika      | `/ms_set_my voice Andika`     |
| :flag_ie: Irish English        | :man: Sean        | `/ms_set_my voice Sean`       |
| :flag_it: Italian              | :man: Cosimo      | `/ms_set_my voice Cosimo`     |
| :flag_it: Italian              | :woman: Elsa      | `/ms_set_my voice Elsa`       |
| :flag_jp: Japanese             | :woman: Ayumi     | `/ms_set_my voice Ayumi`      |
| :flag_jp: Japanese             | :woman: Haruka    | `/ms_set_my voice Haruka`     |
| :flag_jp: Japanese             | :man: Ichiro      | `/ms_set_my voice Ichiro`     |
| :flag_jp: Japanese             | :woman: Sayaka    | `/ms_set_my voice Sayaka`     |
| :flag_kr: Korean               | :woman: Heami     | `/ms_set_my voice Heami`      |
| :flag_my: Malay                | :man: Rizwan      | `/ms_set_my voice Rizwan`     |
| :flag_mx: Mexican Spanish      | :man: Raul        | `/ms_set_my voice Raul`       |
| :flag_mx: Mexican Spanish      | :woman: Sabina    | `/ms_set_my voice Sabina`     |
| :flag_no: Norwegian            | :man: Jon         | `/ms_set_my voice Jon`        |
| :flag_pt: Portuguese           | :woman: Helia     | `/ms_set_my voice Helia`      |
| :flag_ro: Romanian             | :man: Andrei      | `/ms_set_my voice Andrei`     |
| :flag_ru: Russian              | :woman: Irina     | `/ms_set_my voice Irina`      |
| :flag_ru: Russian              | :man: Pavel       | `/ms_set_my voice Pavel`      |
| :flag_sa: Saudi Arabic         | :man: Naayf       | `/ms_set_my voice Naayf`      |
| :flag_sk: Slovak               | :man: Filip       | `/ms_set_my voice Filip`      |
| :flag_si: Slovenian            | :man: Lado        | `/ms_set_my voice Lado`       |
| :flag_es: Spanish              | :woman: Helena    | `/ms_set_my voice Helena`     |
| :flag_es: Spanish              | :woman: Laura     | `/ms_set_my voice Laura`      |
| :flag_es: Spanish              | :man: Pablo       | `/ms_set_my voice Pablo`      |
| :flag_se: Swedish              | :man: Bengt       | `/ms_set_my voice Bengt`      |
| :flag_ch: Swiss French         | :man: Guillaume   | `/ms_set_my voice Guillaume`  |
| :flag_ch: Swiss German         | :man: Karsten     | `/ms_set_my voice Karsten`    |
| :flag_in: Tamil                | :man: Valluvar    | `/ms_set_my voice Valluvar`   |
| :flag_th: Thai                 | :man: Pattara     | `/ms_set_my voice Pattara`    |
| :flag_tr: Turkish              | :man: Tolga       | `/ms_set_my voice Tolga`      |
| :flag_vn: Vietnamese           | :woman: An        | `/ms_set_my voice An`         |

## ⌨️ Source Code

If you're interested in seeing how this provider works, you can head over to the [MicrosoftProvider.js](https://github.com/moonstar-x/discord-tts-bot/blob/master/src/classes/tts/providers/MicrosoftProvider.js) file in the repo, or check this embed.

<script src="https://emgithub.com/embed.js?target=https%3A%2F%2Fgithub.com%2Fmoonstar-x%2Fdiscord-tts-bot%2Fblob%2Fmaster%2Fsrc%2Fclasses%2Ftts%2Fproviders%2FMicrosoftProvider.js&style=github-gist&showBorder=on&showLineNumbers=on&showFileMeta=on&showCopy=on&fetchFromJsDelivr=on"></script>
